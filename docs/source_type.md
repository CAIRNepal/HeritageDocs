

# Slot: source_type 


_Type of source (manuscript, inscription, survey, oral)_





URI: [crm:P2_has_type](http://www.cidoc-crm.org/cidoc-crm/P2_has_type)
Alias: source_type

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [FieldSurveyDataset](FieldSurveyDataset.md) | The structured data or report resulting from a field survey |  no  |
| [DataSource](DataSource.md) | Original source from which heritage information was derived |  no  |
| [ArchivalRecord](ArchivalRecord.md) | Government or institutional administrative record |  no  |
| [OralHistoryRecording](OralHistoryRecording.md) | The recording or transcript of an oral history interview |  no  |






## Properties

* Range: [String](String.md)




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P2_has_type |
| native | heritageGraph:source_type |




## LinkML Source

<details>
```yaml
name: source_type
description: Type of source (manuscript, inscription, survey, oral)
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P2_has_type
alias: source_type
domain_of:
- DataSource
range: string

```
</details>