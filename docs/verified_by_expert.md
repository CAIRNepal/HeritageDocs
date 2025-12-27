

# Slot: verified_by_expert 


_Expert who performed verification_





URI: [crm:P14_carried_out_by](http://www.cidoc-crm.org/cidoc-crm/P14_carried_out_by)
Alias: verified_by_expert

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Verification](Verification.md) | Process of cross-checking heritage claims against multiple sources |  no  |






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
| native | heritageGraph:verified_by_expert |




## LinkML Source

<details>
```yaml
name: verified_by_expert
description: Expert who performed verification
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P14_carried_out_by
alias: verified_by_expert
domain_of:
- Verification
range: Person
multivalued: true

```
</details>