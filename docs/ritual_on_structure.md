

# Slot: ritual_on_structure 


_Ritual occurs at specific temple or monument_





URI: [crm:P8_took_place_on_or_within](http://www.cidoc-crm.org/cidoc-crm/P8_took_place_on_or_within)
Alias: ritual_on_structure

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

* Range: [ArchitecturalStructure](ArchitecturalStructure.md)




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P8_took_place_on_or_within |
| native | heritageGraph:ritual_on_structure |




## LinkML Source

<details>
```yaml
name: ritual_on_structure
description: Ritual occurs at specific temple or monument
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P8_took_place_on_or_within
alias: ritual_on_structure
domain_of:
- RitualEvent
range: ArchitecturalStructure

```
</details>