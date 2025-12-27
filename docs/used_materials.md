

# Slot: used_materials 


_Ephemeral materials consumed during the ritual (e.g., oil, rice)._





URI: [crm:P125_used_object_of_type](http://www.cidoc-crm.org/cidoc-crm/P125_used_object_of_type)
Alias: used_materials

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [NityaPuja](NityaPuja.md) | Daily worship ritual performed continuously |  no  |
| [RitualEvent](RitualEvent.md) | Intentional ritual activity that activates sacred space, invokes deities, and... |  no  |
| [Puja](Puja.md) | Worship ceremony directed toward a deity or sacred object |  no  |
| [NaimittikaPuja](NaimittikaPuja.md) | Occasional worship ritual tied to festivals or life events |  no  |
| [MaskedDance](MaskedDance.md) | Festival featuring masked dancers embodying deities (e |  no  |
| [ChariotFestival](ChariotFestival.md) | Festival involving ceremonial chariot procession (e |  no  |
| [Festival](Festival.md) | Large-scale community ritual event (Jatra) involving processions, music, and ... |  no  |






## Properties

* Range: [Material](Material.md)

* Multivalued: True




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P125_used_object_of_type |
| native | heritageGraph:used_materials |




## LinkML Source

<details>
```yaml
name: used_materials
description: Ephemeral materials consumed during the ritual (e.g., oil, rice).
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P125_used_object_of_type
alias: used_materials
domain_of:
- RitualEvent
range: Material
multivalued: true

```
</details>