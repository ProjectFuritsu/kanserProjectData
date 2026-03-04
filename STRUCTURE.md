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
