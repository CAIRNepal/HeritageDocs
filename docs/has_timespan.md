

# Slot: has_timespan 


_Links event to its temporal extent_





URI: [crm:P4_has_time-span](http://www.cidoc-crm.org/cidoc-crm/P4_has_time-span)
Alias: has_timespan

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Consecration](Consecration.md) | Ritual event that transforms an object into a sacred vessel (e |  no  |
| [TransferOfCustody](TransferOfCustody.md) | Event of transferring responsibility for temple maintenance, ritual performan... |  no  |
| [NityaPuja](NityaPuja.md) | Daily worship ritual performed continuously |  no  |
| [RitualEvent](RitualEvent.md) | Intentional ritual activity that activates sacred space, invokes deities, and... |  no  |
| [Puja](Puja.md) | Worship ceremony directed toward a deity or sacred object |  no  |
| [NaimittikaPuja](NaimittikaPuja.md) | Occasional worship ritual tied to festivals or life events |  no  |
| [OralHistoryInterview](OralHistoryInterview.md) | The interaction event between a researcher and a knowledge holder |  no  |
| [MaskedDance](MaskedDance.md) | Festival featuring masked dancers embodying deities (e |  no  |
| [ChariotFestival](ChariotFestival.md) | Festival involving ceremonial chariot procession (e |  no  |
| [DocumentationActivity](DocumentationActivity.md) | The intellectual or technical process of recording information about a herita... |  no  |
| [Production](Production.md) | Event of creating an architectural structure, murti, or paubha |  no  |
| [FieldSurveyActivity](FieldSurveyActivity.md) | The activity of measuring, photographing, or assessing a site in person |  no  |
| [Enshrinement](Enshrinement.md) | Event of installing a deity's murti or symbol within a temple sanctum |  no  |
| [Festival](Festival.md) | Large-scale community ritual event (Jatra) involving processions, music, and ... |  no  |
| [Verification](Verification.md) | Process of cross-checking heritage claims against multiple sources |  no  |
| [ConditionAssessment](ConditionAssessment.md) | Event of evaluating the physical state of a heritage object or structure |  no  |






## Properties

* Range: [TimeSpan](TimeSpan.md)




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P4_has_time-span |
| native | heritageGraph:has_timespan |




## LinkML Source

<details>
```yaml
name: has_timespan
description: Links event to its temporal extent
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P4_has_time-span
alias: has_timespan
domain_of:
- Production
- RitualEvent
- Consecration
- Enshrinement
- TransferOfCustody
- ConditionAssessment
- DocumentationActivity
range: TimeSpan

```
</details>