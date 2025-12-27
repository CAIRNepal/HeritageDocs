

# Slot: carried_out_by_actor 


_Actor(s) who performed this event_





URI: [crm:P14_carried_out_by](http://www.cidoc-crm.org/cidoc-crm/P14_carried_out_by)
Alias: carried_out_by_actor

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Production](Production.md) | Event of creating an architectural structure, murti, or paubha |  no  |
| [ConditionAssessment](ConditionAssessment.md) | Event of evaluating the physical state of a heritage object or structure |  no  |






## Properties

* Range: [Actor](Actor.md)

* Multivalued: True




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P14_carried_out_by |
| native | heritageGraph:carried_out_by_actor |




## LinkML Source

<details>
```yaml
name: carried_out_by_actor
description: Actor(s) who performed this event
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P14_carried_out_by
alias: carried_out_by_actor
domain_of:
- Production
- ConditionAssessment
range: Actor
multivalued: true

```
</details>