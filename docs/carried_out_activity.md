

# Slot: carried_out_activity 


_Activities performed by this actor_





URI: [crm:P14i_performed](http://www.cidoc-crm.org/cidoc-crm/P14i_performed)
Alias: carried_out_activity

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Person](Person.md) | Individual person who performs, commissions, documents, or verifies heritage ... |  no  |






## Properties

* Range: [RitualEvent](RitualEvent.md)

* Multivalued: True




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P14i_performed |
| native | heritageGraph:carried_out_activity |




## LinkML Source

<details>
```yaml
name: carried_out_activity
description: Activities performed by this actor
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P14i_performed
alias: carried_out_activity
domain_of:
- Person
range: RitualEvent
multivalued: true

```
</details>