

# Slot: assessed_condition_state 


_Identified condition state (good, damaged, ruined)_





URI: [crm:P35_has_identified](http://www.cidoc-crm.org/cidoc-crm/P35_has_identified)
Alias: assessed_condition_state

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ConditionAssessment](ConditionAssessment.md) | Event of evaluating the physical state of a heritage object or structure |  no  |






## Properties

* Range: [String](String.md)




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P35_has_identified |
| native | heritageGraph:assessed_condition_state |




## LinkML Source

<details>
```yaml
name: assessed_condition_state
description: Identified condition state (good, damaged, ruined)
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P35_has_identified
alias: assessed_condition_state
domain_of:
- ConditionAssessment
range: string

```
</details>