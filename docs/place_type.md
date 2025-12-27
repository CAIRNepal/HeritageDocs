

# Slot: place_type 


_Type of place (city, village, region)_





URI: [crm:P2_has_type](http://www.cidoc-crm.org/cidoc-crm/P2_has_type)
Alias: place_type

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Place](Place.md) | Defined geographic location where events occur and structures exist |  no  |






## Properties

* Range: [String](String.md)




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P2_has_type |
| native | heritageGraph:place_type |




## LinkML Source

<details>
```yaml
name: place_type
description: Type of place (city, village, region)
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P2_has_type
alias: place_type
domain_of:
- Place
range: string

```
</details>