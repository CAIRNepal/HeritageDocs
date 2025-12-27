

# Class: Material 


_Physical substance used in construction or crafting_





URI: [crm:E57_Material](http://www.cidoc-crm.org/cidoc-crm/E57_Material)





```mermaid
 classDiagram
    class Material
    click Material href "../Material/"
      Material : english_description
        
      Material : name
        
      
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
| [RitualEvent](RitualEvent.md) | [used_materials](used_materials.md) | range | [Material](Material.md) |
| [Puja](Puja.md) | [used_materials](used_materials.md) | range | [Material](Material.md) |
| [NityaPuja](NityaPuja.md) | [used_materials](used_materials.md) | range | [Material](Material.md) |
| [NaimittikaPuja](NaimittikaPuja.md) | [used_materials](used_materials.md) | range | [Material](Material.md) |
| [Festival](Festival.md) | [used_materials](used_materials.md) | range | [Material](Material.md) |
| [ChariotFestival](ChariotFestival.md) | [used_materials](used_materials.md) | range | [Material](Material.md) |
| [MaskedDance](MaskedDance.md) | [used_materials](used_materials.md) | range | [Material](Material.md) |
| [Container](Container.md) | [materials](materials.md) | range | [Material](Material.md) |







## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:E57_Material |
| native | heritageGraph:Material |






## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: Material
description: Physical substance used in construction or crafting
from_schema: CulturalHeritageOntology
slots:
- name
- english_description
class_uri: crm:E57_Material

```
</details>

### Induced

<details>
```yaml
name: Material
description: Physical substance used in construction or crafting
from_schema: CulturalHeritageOntology
attributes:
  name:
    name: name
    description: Primary name or label
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P1_is_identified_by
    alias: name
    owner: Material
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
    owner: Material
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
class_uri: crm:E57_Material

```
</details>