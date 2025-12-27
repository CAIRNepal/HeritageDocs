

# Slot: publication_timespan 


_When source was published_





URI: [crm:P4_has_time-span](http://www.cidoc-crm.org/cidoc-crm/P4_has_time-span)
Alias: publication_timespan

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [FieldSurveyDataset](FieldSurveyDataset.md) | The structured data or report resulting from a field survey |  no  |
| [DataSource](DataSource.md) | Original source from which heritage information was derived |  no  |
| [ArchivalRecord](ArchivalRecord.md) | Government or institutional administrative record |  no  |
| [OralHistoryRecording](OralHistoryRecording.md) | The recording or transcript of an oral history interview |  no  |






## Properties

* Range: [TimeSpan](TimeSpan.md)




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P4_has_time-span |
| native | heritageGraph:publication_timespan |




## LinkML Source

<details>
```yaml
name: publication_timespan
description: When source was published
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P4_has_time-span
alias: publication_timespan
domain_of:
- DataSource
range: TimeSpan

```
</details>