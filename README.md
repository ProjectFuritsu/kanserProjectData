
# Cancer YAML Data Repository

This repository stores structured report data using YAML/JSON. It is designed to be simple, human-readable, version-controlled, and easy to consume by frontend or backend applications.

The core idea is boring on purpose: predictable structure, clear fields, and minimal magic. That’s a feature, not a limitation.


### Authors

- [@ProjectFuritsu ](https://github.com/ProjectFuritsu)
- [@KDevDesigns](https://github.com/KDevDesigns)


## Features

- Human-readable and structured YAML format
- Categorization and severity tagging
- Location fields with optional precision
- Attachment references without embedded binaries
- Validation-friendly structure for linting and CI checks
- Git-friendly version control and change history
- Easy integration with frontend and serverless backends
- Moderation-ready without hard deletion of records
- Migration-friendly to database systems when scaling is required



### Used By

This project is used by the following application:

- CancerLine Companion App


#### Supported Languages (YAML Read Support)

| Language           | Popular YAML Package(s)                |
|------------------|--------------------------------------|
| JavaScript / TypeScript | js-yaml, yaml                     |
| Python            | PyYAML, ruamel.yaml                   |
| Go                | gopkg.in/yaml.v3                       |
| Java              | SnakeYAML                              |
| C#                | YamlDotNet                             |
| PHP               | symfony/yaml, spyc                     |
| Ruby              | yaml (built-in, Psych)                 |
| Rust              | serde_yaml                              |
| Kotlin            | kotlinx-serialization-yaml, SnakeYAML |
| Swift             | Yams                                   |
| Dart              | yaml                                   |
| R                 | yaml                                   |
| Julia             | YAML.jl                                 |
| Perl              | YAML, YAML::XS                          |
| Scala             | SnakeYAML (via JVM)                     |
| Haskell           | yaml                                    |
| Elixir            | yamerl                                  |
| Bash / CLI        | yq                                      |
