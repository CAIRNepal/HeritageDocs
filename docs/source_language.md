

# Slot: source_language 


_Language of the source material_





URI: [crm:P72_has_language](http://www.cidoc-crm.org/cidoc-crm/P72_has_language)
Alias: source_language

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
| self | crm:P72_has_language |
| native | heritageGraph:source_language |




## LinkML Source

<details>
```yaml
name: source_language
description: Language of the source material
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P72_has_language
alias: source_language
domain_of:
- DataSource
range: string

```
</details>