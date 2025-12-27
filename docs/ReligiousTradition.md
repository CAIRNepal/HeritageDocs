

# Class: ReligiousTradition 


_Religious or spiritual tradition within which a deity or sacred figure is venerated_





URI: [crm:E55_Type](http://www.cidoc-crm.org/cidoc-crm/E55_Type)





```mermaid
 classDiagram
    class ReligiousTradition
    click ReligiousTradition href "../ReligiousTradition/"
      ReligiousTradition : english_description
        
      ReligiousTradition : name
        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [name](name.md) | 0..1 <br/> [String](String.md) | Primary name or label | direct |
| [english_description](english_description.md) | 0..1 <br/> [String](String.md) | Descriptive text in English | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Deity](Deity.md) | [has_religious_tradition](has_religious_tradition.md) | range | [ReligiousTradition](ReligiousTradition.md) |
| [Container](Container.md) | [religious_traditions](religious_traditions.md) | range | [ReligiousTradition](ReligiousTradition.md) |







## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:E55_Type |
| native | heritageGraph:ReligiousTradition |






## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: ReligiousTradition
description: Religious or spiritual tradition within which a deity or sacred figure
  is venerated
from_schema: CulturalHeritageOntology
slots:
- name
- english_description
class_uri: crm:E55_Type

```
</details>

### Induced

<details>
```yaml
name: ReligiousTradition
description: Religious or spiritual tradition within which a deity or sacred figure
  is venerated
from_schema: CulturalHeritageOntology
attributes:
  name:
    name: name
    description: Primary name or label
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P1_is_identified_by
    alias: name
    owner: ReligiousTradition
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
  english_description:
    name: english_description
    description: Descriptive text in English
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P3_has_note
    alias: english_description
    owner: ReligiousTradition
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
class_uri: crm:E55_Type

```
</details>