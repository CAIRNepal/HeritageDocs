

# Slot: was_attributed_to_agent 


_Person who made this assertion_





URI: [prov:wasAttributedTo](https://www.w3.org/ns/prov/wasAttributedTo)
Alias: was_attributed_to_agent

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ProvenanceAssertion](ProvenanceAssertion.md) | A single factual claim about a heritage entity, with explicit source, author,... |  no  |






## Properties

* Range: [Person](Person.md)

* Multivalued: True




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | prov:wasAttributedTo |
| native | heritageGraph:was_attributed_to_agent |




## LinkML Source

<details>
```yaml
name: was_attributed_to_agent
description: Person who made this assertion
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: prov:wasAttributedTo
alias: was_attributed_to_agent
domain_of:
- ProvenanceAssertion
range: Person
multivalued: true

```
</details>