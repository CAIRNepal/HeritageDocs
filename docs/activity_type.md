

# Slot: activity_type 


_Type of documentation activity_





URI: [crm:P2_has_type](http://www.cidoc-crm.org/cidoc-crm/P2_has_type)
Alias: activity_type

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [DocumentationActivity](DocumentationActivity.md) | The intellectual or technical process of recording information about a herita... |  no  |
| [Verification](Verification.md) | Process of cross-checking heritage claims against multiple sources |  no  |
| [OralHistoryInterview](OralHistoryInterview.md) | The interaction event between a researcher and a knowledge holder |  no  |
| [FieldSurveyActivity](FieldSurveyActivity.md) | The activity of measuring, photographing, or assessing a site in person |  no  |






## Properties

* Range: [String](String.md)




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P2_has_type |
| native | heritageGraph:activity_type |




## LinkML Source

<details>
```yaml
name: activity_type
description: Type of documentation activity
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P2_has_type
alias: activity_type
domain_of:
- DocumentationActivity
range: string

```
</details>