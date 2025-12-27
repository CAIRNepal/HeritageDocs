

# Slot: performed_by_agent 


_Agent who performed documentation_





URI: [prov:wasAssociatedWith](https://www.w3.org/ns/prov/wasAssociatedWith)
Alias: performed_by_agent

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [DocumentationActivity](DocumentationActivity.md) | The intellectual or technical process of recording information about a herita... |  no  |
| [Verification](Verification.md) | Process of cross-checking heritage claims against multiple sources |  no  |
| [OralHistoryInterview](OralHistoryInterview.md) | The interaction event between a researcher and a knowledge holder |  no  |
| [FieldSurveyActivity](FieldSurveyActivity.md) | The activity of measuring, photographing, or assessing a site in person |  no  |






## Properties

* Range: [Person](Person.md)

* Multivalued: True




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | prov:wasAssociatedWith |
| native | heritageGraph:performed_by_agent |




## LinkML Source

<details>
```yaml
name: performed_by_agent
description: Agent who performed documentation
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: prov:wasAssociatedWith
alias: performed_by_agent
domain_of:
- DocumentationActivity
range: Person
multivalued: true

```
</details>