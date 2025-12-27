

# Slot: occupation 


_Person's occupation or role_





URI: [crm:P2_has_type](http://www.cidoc-crm.org/cidoc-crm/P2_has_type)
Alias: occupation

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Person](Person.md) | Individual person who performs, commissions, documents, or verifies heritage ... |  no  |






## Properties

* Range: [String](String.md)

* Multivalued: True




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P2_has_type |
| native | heritageGraph:occupation |




## LinkML Source

<details>
```yaml
name: occupation
description: Person's occupation or role
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P2_has_type
alias: occupation
domain_of:
- Person
range: string
multivalued: true

```
</details>