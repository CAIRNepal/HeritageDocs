

# Slot: ritual_type 


_Classification of ritual (puja, jatra, consecration)_





URI: [crm:P2_has_type](http://www.cidoc-crm.org/cidoc-crm/P2_has_type)
Alias: ritual_type

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

* Range: [RitualTypeEnum](RitualTypeEnum.md)




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P2_has_type |
| native | heritageGraph:ritual_type |




## LinkML Source

<details>
```yaml
name: ritual_type
description: Classification of ritual (puja, jatra, consecration)
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P2_has_type
alias: ritual_type
domain_of:
- RitualEvent
range: RitualTypeEnum

```
</details>