

# Slot: documented_entity 


_Heritage entity documented by this activity_





URI: [prov:generated](https://www.w3.org/ns/prov/generated)
Alias: documented_entity

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [DocumentationActivity](DocumentationActivity.md) | The intellectual or technical process of recording information about a herita... |  no  |
| [Verification](Verification.md) | Process of cross-checking heritage claims against multiple sources |  no  |
| [OralHistoryInterview](OralHistoryInterview.md) | The interaction event between a researcher and a knowledge holder |  no  |
| [FieldSurveyActivity](FieldSurveyActivity.md) | The activity of measuring, photographing, or assessing a site in person |  no  |






## Properties

* Range: [ArchitecturalStructure](ArchitecturalStructure.md)

* Multivalued: True




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | prov:generated |
| native | heritageGraph:documented_entity |




## LinkML Source

<details>
```yaml
name: documented_entity
description: Heritage entity documented by this activity
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: prov:generated
alias: documented_entity
domain_of:
- DocumentationActivity
range: ArchitecturalStructure
multivalued: true

```
</details>