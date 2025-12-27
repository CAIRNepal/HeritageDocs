

# Slot: performs_ritual 


_Rituals performed by this Guthi_





URI: [crm:P14i_performed](http://www.cidoc-crm.org/cidoc-crm/P14i_performed)
Alias: performs_ritual

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SiGuthi](SiGuthi.md) | Funeral trust responsible for death rituals and cremation ceremonies |  no  |
| [Guthi](Guthi.md) | Endowed trust organization unique to Nepal, managing temples, rituals, and la... |  no  |
| [SanGuthi](SanGuthi.md) | Life-cycle ritual trust managing rites of passage |  no  |
| [RajGuthi](RajGuthi.md) | Royal Guthi established by Malla or Shah monarchy (pre-1964) |  no  |
| [PujaGuthi](PujaGuthi.md) | Worship trust responsible for daily puja rituals |  no  |
| [JatraGuthi](JatraGuthi.md) | Festival trust responsible for organizing and funding annual Jatra events |  no  |
| [NashaGuthi](NashaGuthi.md) | Music and dance trust (nāsaḥdyaḥ) preserving ritual performance traditions |  no  |
| [SanaGuthi](SanaGuthi.md) | Agricultural cooperative managing communal farmland |  no  |
| [TempleGuthi](TempleGuthi.md) | Trust managing temple maintenance, daily puja, and priest salaries |  no  |






## Properties

* Range: [RitualEvent](RitualEvent.md)

* Multivalued: True




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P14i_performed |
| native | heritageGraph:performs_ritual |




## LinkML Source

<details>
```yaml
name: performs_ritual
description: Rituals performed by this Guthi
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P14i_performed
alias: performs_ritual
domain_of:
- Guthi
range: RitualEvent
multivalued: true

```
</details>