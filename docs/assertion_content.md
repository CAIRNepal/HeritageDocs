

# Slot: assertion_content 


_The factual claim being asserted_





URI: [prov:value](https://www.w3.org/ns/prov/value)
Alias: assertion_content

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ProvenanceAssertion](ProvenanceAssertion.md) | A single factual claim about a heritage entity, with explicit source, author,... |  no  |






## Properties

* Range: [String](String.md)




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | prov:value |
| native | heritageGraph:assertion_content |




## LinkML Source

<details>
```yaml
name: assertion_content
description: The factual claim being asserted
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: prov:value
alias: assertion_content
domain_of:
- ProvenanceAssertion
range: string

```
</details>