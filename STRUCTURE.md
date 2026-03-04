## Comprehensive Guide of the Data Structure of each data files

### Health Institution
This is a instance of health facility around it includes hospitals, clinics, diagnostic centers and more.

#### Data Strucutre
```json
{
  "id": Number,
  "name": String,
  "bgImageURL": String,
  "source": String,
  "description": String,
  "type": String,
  "location": String,
  "latitude": Float,
  "longitude": Float,
  "schedule": [
                "isWholeWeek": Boolean,
                "day": [
                         {
                            "day": String,
                            "timeIn": String,
                            "timeOut": String
                          }   
                       ]
              ],
   "contacts":[
                {
                  "contact_id": Number,
                  "type": String,
                  "contact_details": String
                }
              ],
  "services": [
                {
                  "serviceID": Number,
                  "source": String,
                  "service_name": String,
                  "service_description": String,
                  "requirements": [
                                    {
                                      "requirement_id": Number,
                                      "requirement_description": String
                                    }
                                  ],
                  "procedure": [
                                  {
                                    "step": Number,
                                    "instruction": String
                                  }
                               ]
                }
              ]
}
```

---

### Financial Institution (Financial Assistance Providers)
This is a institutions include Government and Private angencies (Philhealth, Malasakit Centers, etc) that provides financial assistance for the patient, these insitutions also includes to partylist as long as the patient can benefit with zero fund from his/her pocket.

#### Data Strucutre
```json
{
  "id": Number,
  "name": String,
  "bgImageURL": String,
  "source": String,
  "description": String,
  "type": String,
  "location": String,
  "latitude": Float,
  "longitude": Float,
  "schedule": [
                "isWholeWeek": Boolean,
                "day": [
                         {
                            "day": String,
                            "timeIn": String,
                            "timeOut": String
                          }   
                       ]
              ],
   "contacts":  [
                  {
                    "contact_id": Number,
                    "type": String,
                    "contact_details": String
                  }
                ],
  "programs": [
                {
                  "programID": Number,
                  "source": String,
                  "program_name": String,
                  "program_description": String,
                  "benefits": [
                                    {
                                      "benefit_id": Number,
                                      "benefit_description": String
                                    }
                                  ],
                  "requirements": [
                                    {
                                      "requirement_id‎": Number,
                                      "requirement_description": String
                                    }
                                  ],
                  "procedure": [
                                  {
                                    "step": Number,
                                    "instruction": String
                                  }
                               ]
                }
              ]
}
```
---

### Medical Specialist (Medical Practitioners/Doctors)
These are practitioners from both Government and Private health institutions (Hospitals, Clinics, etc).

#### Data Strucutre
```json
{
  "id": Number,
  "firstname": String,
  "lastname": String,
  "field‎": String,
  "imageURL": String,
  "source": String,
  "description": String,
  "clinics": [
              {
                "clinicid": Number,
                "clinicName": String
                "isAcceptWalkIns": Boolean,
                "isAcceptBoth": Boolean,
                "location": String,
                "contacts": {
                              "contact_id": Number,
                              "type": String,
                              "contact_details": String
                            },
                "schedule": [
                             {
                              "day": String,
                              "timeIn": String,
                              "timeOut": String
                             }   
                           ]
                
              }
             ],
}
```
---

### Support Groups (Community Groups)
These are groups around that supports patients with their emotional and social aspect of journey.

#### Data Strucutre
```json
{
  "id": Number,
  "name": String,
  "description": String,
  "type": String,
  "bgImageURL": String,
  "socmedURL": String,
  "location": String,
  "longitude": Float,
  "Latitude": Float,
  "founder": String,
  "contacts": [
                {
                  "contact_id": Number,
                  "type": String,
                  "contact_details": String
                }
              ]
}
```
---

### Feeds (Cancer related Educational resources )
These are resources that educated not just cancer patients but the whole ecosystem, its a way of educating people. It includes (Blogs, News, Articles, etc).

#### Data Strucutre
```json
{
  "id": Number,
  "title": String,
  "bgImageURL": String,
  "category": String,
  "author": String,
  "publishDate": String,
  "source": String,
  "content": String(HTML),
}
```
---
### Events
These events that a cancer patient and their companion can join, either for entertainment events or form of networking (patient can connect to other people)

### Data Structure
```json
{
  "id": Number,
  "title": String,
  "dateStarted": String,
  "dateEnded": String,
  "organizer": String,
  "regLink": String,
  "description": String (HTML)
}
```
