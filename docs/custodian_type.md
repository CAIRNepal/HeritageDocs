

# Slot: custodian_type 


_Type of custodian (government, academic, community)_





URI: [crm:P2_has_type](http://www.cidoc-crm.org/cidoc-crm/P2_has_type)
Alias: custodian_type

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [DataCustodian](DataCustodian.md) | Institution or person currently stewarding heritage data |  no  |






## Properties

* Range: [String](String.md)




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P2_has_type |
| native | heritageGraph:custodian_type |




## LinkML Source

<details>
```yaml
name: custodian_type
description: Type of custodian (government, academic, community)
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P2_has_type
alias: custodian_type
domain_of:
- DataCustodian
range: string

```
</details>