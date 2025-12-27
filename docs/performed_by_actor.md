

# Slot: performed_by_actor 


_Individual who performed ritual_





URI: [crm:P14_carried_out_by](http://www.cidoc-crm.org/cidoc-crm/P14_carried_out_by)
Alias: performed_by_actor

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Consecration](Consecration.md) | Ritual event that transforms an object into a sacred vessel (e |  no  |
| [NityaPuja](NityaPuja.md) | Daily worship ritual performed continuously |  no  |
| [RitualEvent](RitualEvent.md) | Intentional ritual activity that activates sacred space, invokes deities, and... |  no  |
| [Puja](Puja.md) | Worship ceremony directed toward a deity or sacred object |  no  |
| [NaimittikaPuja](NaimittikaPuja.md) | Occasional worship ritual tied to festivals or life events |  no  |
| [MaskedDance](MaskedDance.md) | Festival featuring masked dancers embodying deities (e |  no  |
| [ChariotFestival](ChariotFestival.md) | Festival involving ceremonial chariot procession (e |  no  |
| [Enshrinement](Enshrinement.md) | Event of installing a deity's murti or symbol within a temple sanctum |  no  |
| [Festival](Festival.md) | Large-scale community ritual event (Jatra) involving processions, music, and ... |  no  |






## Properties

* Range: [Person](Person.md)

* Multivalued: True




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P14_carried_out_by |
| native | heritageGraph:performed_by_actor |




## LinkML Source

<details>
```yaml
name: performed_by_actor
description: Individual who performed ritual
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P14_carried_out_by
alias: performed_by_actor
domain_of:
- RitualEvent
- Consecration
- Enshrinement
range: Person
multivalued: true

```
</details>