

# Slot: place_coordinates 


_Geographic coordinates (WGS84: lat,lon)_





URI: [crm:P168_place_is_defined_by](http://www.cidoc-crm.org/cidoc-crm/P168_place_is_defined_by)
Alias: place_coordinates

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
| self | crm:P168_place_is_defined_by |
| native | heritageGraph:place_coordinates |




## LinkML Source

<details>
```yaml
name: place_coordinates
description: 'Geographic coordinates (WGS84: lat,lon)'
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P168_place_is_defined_by
alias: place_coordinates
domain_of:
- Place
range: string

```
</details>