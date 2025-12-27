

# Slot: source_citation 


_Formal citation of source_





URI: [crm:P3_has_note](http://www.cidoc-crm.org/cidoc-crm/P3_has_note)
Alias: source_citation

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
| self | crm:P3_has_note |
| native | heritageGraph:source_citation |




## LinkML Source

<details>
```yaml
name: source_citation
description: Formal citation of source
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P3_has_note
alias: source_citation
domain_of:
- DataSource
range: string

```
</details>