

# Slot: transferred_to_actor 


_New custodian (person)_





URI: [crm:P29_custody_received_by](http://www.cidoc-crm.org/cidoc-crm/P29_custody_received_by)
Alias: transferred_to_actor

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [TransferOfCustody](TransferOfCustody.md) | Event of transferring responsibility for temple maintenance, ritual performan... |  no  |






## Properties

* Range: [Actor](Actor.md)




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P29_custody_received_by |
| native | heritageGraph:transferred_to_actor |




## LinkML Source

<details>
```yaml
name: transferred_to_actor
description: New custodian (person)
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P29_custody_received_by
alias: transferred_to_actor
domain_of:
- TransferOfCustody
range: Actor

```
</details>