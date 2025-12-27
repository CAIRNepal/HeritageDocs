

# Slot: guthi_type 


_Type of Guthi (Si, Jatra, Temple)_





URI: [crm:P2_has_type](http://www.cidoc-crm.org/cidoc-crm/P2_has_type)
Alias: guthi_type

<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SiGuthi](SiGuthi.md) | Funeral trust responsible for death rituals and cremation ceremonies |  no  |
| [Guthi](Guthi.md) | Endowed trust organization unique to Nepal, managing temples, rituals, and la... |  yes  |
| [SanGuthi](SanGuthi.md) | Life-cycle ritual trust managing rites of passage |  no  |
| [RajGuthi](RajGuthi.md) | Royal Guthi established by Malla or Shah monarchy (pre-1964) |  no  |
| [PujaGuthi](PujaGuthi.md) | Worship trust responsible for daily puja rituals |  no  |
| [JatraGuthi](JatraGuthi.md) | Festival trust responsible for organizing and funding annual Jatra events |  no  |
| [NashaGuthi](NashaGuthi.md) | Music and dance trust (nāsaḥdyaḥ) preserving ritual performance traditions |  no  |
| [SanaGuthi](SanaGuthi.md) | Agricultural cooperative managing communal farmland |  no  |
| [TempleGuthi](TempleGuthi.md) | Trust managing temple maintenance, daily puja, and priest salaries |  no  |






## Properties

* Range: [GuthiTypeEnum](GuthiTypeEnum.md)




## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:P2_has_type |
| native | heritageGraph:guthi_type |




## LinkML Source

<details>
```yaml
name: guthi_type
description: Type of Guthi (Si, Jatra, Temple)
from_schema: CulturalHeritageOntology
rank: 1000
slot_uri: crm:P2_has_type
alias: guthi_type
domain_of:
- Guthi
range: GuthiTypeEnum

```
</details>