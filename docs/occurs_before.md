

# Slot: occurs_before 


_Points to the next ritual in the canonical sequence._





URI: [crm:P120_occurs_before](http://www.cidoc-crm.org/cidoc-crm/P120_occurs_before)
Alias: occurs_before

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

* Range: [RitualEvent](RitualEvent.md)




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P120_occurs_before |
| native | heritageGraph:occurs_before |




## LinkML Source

<details>
```yaml
name: occurs_before
description: Points to the next ritual in the canonical sequence.
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P120_occurs_before
alias: occurs_before
domain_of:
- RitualEvent
range: RitualEvent

```
</details>