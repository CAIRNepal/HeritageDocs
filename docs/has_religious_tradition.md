

# Slot: has_religious_tradition 


_Religious tradition(s) within which this deity is venerated_





URI: [crm:P2_has_type](http://www.cidoc-crm.org/cidoc-crm/P2_has_type)
Alias: has_religious_tradition

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Deity](Deity.md) | Divine conceptual entity in Hindu, Buddhist, or syncretic traditions |  no  |






## Properties

* Range: [ReligiousTradition](ReligiousTradition.md)

* Multivalued: True




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P2_has_type |
| native | heritageGraph:has_religious_tradition |




## LinkML Source

<details>
```yaml
name: has_religious_tradition
description: Religious tradition(s) within which this deity is venerated
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P2_has_type
alias: has_religious_tradition
domain_of:
- Deity
range: ReligiousTradition
multivalued: true

```
</details>