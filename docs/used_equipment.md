

# Slot: used_equipment 


_Equipment used in documentation_





URI: [crm:P16_used_specific_object](http://www.cidoc-crm.org/cidoc-crm/P16_used_specific_object)
Alias: used_equipment

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

* Multivalued: True




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P16_used_specific_object |
| native | heritageGraph:used_equipment |




## LinkML Source

<details>
```yaml
name: used_equipment
description: Equipment used in documentation
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P16_used_specific_object
alias: used_equipment
domain_of:
- DocumentationActivity
range: string
multivalued: true

```
</details>