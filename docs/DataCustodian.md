

# Class: DataCustodian 


_Institution or person currently stewarding heritage data_





URI: [prov:Agent](https://www.w3.org/ns/prov/Agent)





```mermaid
 classDiagram
    class DataCustodian
    click DataCustodian href "../DataCustodian/"
      DataCustodian : custodian_type
        
      DataCustodian : english_description
        
      DataCustodian : name
        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [name](name.md) | 0..1 <br/> [String](String.md) | Primary name or label | direct |
| [custodian_type](custodian_type.md) | 0..1 <br/> [String](String.md) | Type of custodian (government, academic, community) | direct |
| [english_description](english_description.md) | 0..1 <br/> [String](String.md) | Descriptive text in English | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Container](Container.md) | [data_custodians](data_custodians.md) | range | [DataCustodian](DataCustodian.md) |







## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | prov:Agent |
| native | heritageGraph:DataCustodian |






## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: DataCustodian
description: Institution or person currently stewarding heritage data
from_schema: CulturalHeritageOntology
slots:
- name
- custodian_type
- english_description
class_uri: prov:Agent

```
</details>

### Induced

<details>
```yaml
name: DataCustodian
description: Institution or person currently stewarding heritage data
from_schema: CulturalHeritageOntology
attributes:
  name:
    name: name
    description: Primary name or label
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P1_is_identified_by
    alias: name
    owner: DataCustodian
    domain_of:
    - ArchitecturalStructure
    - IconographicObject
    - ArchitecturalElement
    - Deity
    - ReligiousTradition
    - TraditionOrPractice
    - ArchitecturalStyle
    - CalendarSystem
    - Production
    - RitualEvent
    - Consecration
    - Enshrinement
    - TransferOfCustody
    - ConditionAssessment
    - Guthi
    - CasteGroup
    - Person
    - Actor
    - Place
    - DataSource
    - DocumentationActivity
    - DataCustodian
    - Technique
    - Material
    range: string
  custodian_type:
    name: custodian_type
    description: Type of custodian (government, academic, community)
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P2_has_type
    alias: custodian_type
    owner: DataCustodian
    domain_of:
    - DataCustodian
    range: string
  english_description:
    name: english_description
    description: Descriptive text in English
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P3_has_note
    alias: english_description
    owner: DataCustodian
    domain_of:
    - ArchitecturalStructure
    - IconographicObject
    - ArchitecturalElement
    - Deity
    - ReligiousTradition
    - TraditionOrPractice
    - ArchitecturalStyle
    - RitualEvent
    - Guthi
    - CasteGroup
    - Person
    - Actor
    - DataSource
    - DataCustodian
    - Technique
    - Material
    range: string
class_uri: prov:Agent

```
</details>