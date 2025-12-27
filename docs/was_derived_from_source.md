

# Slot: was_derived_from_source 


_Source(s) from which this assertion was derived_





URI: [prov:wasDerivedFrom](https://www.w3.org/ns/prov/wasDerivedFrom)
Alias: was_derived_from_source

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ProvenanceAssertion](ProvenanceAssertion.md) | A single factual claim about a heritage entity, with explicit source, author,... |  no  |






## Properties

* Range: [DataSource](DataSource.md)

* Multivalued: True




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | prov:wasDerivedFrom |
| native | heritageGraph:was_derived_from_source |




## LinkML Source

<details>
```yaml
name: was_derived_from_source
description: Source(s) from which this assertion was derived
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: prov:wasDerivedFrom
alias: was_derived_from_source
domain_of:
- ProvenanceAssertion
range: DataSource
multivalued: true

```
</details>