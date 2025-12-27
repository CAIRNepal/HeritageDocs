

# Class: Actor 


_General actor (person or group) responsible for events_





URI: [crm:E39_Actor](http://www.cidoc-crm.org/cidoc-crm/E39_Actor)





```mermaid
 classDiagram
    class Actor
    click Actor href "../Actor/"
      Actor : english_description
        
      Actor : name
        
      
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
| [Production](Production.md) | [carried_out_by_actor](carried_out_by_actor.md) | range | [Actor](Actor.md) |
| [Production](Production.md) | [commissioned_by](commissioned_by.md) | range | [Actor](Actor.md) |
| [TransferOfCustody](TransferOfCustody.md) | [transferred_from_actor](transferred_from_actor.md) | range | [Actor](Actor.md) |
| [TransferOfCustody](TransferOfCustody.md) | [transferred_to_actor](transferred_to_actor.md) | range | [Actor](Actor.md) |
| [ConditionAssessment](ConditionAssessment.md) | [carried_out_by_actor](carried_out_by_actor.md) | range | [Actor](Actor.md) |







## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:E39_Actor |
| native | heritageGraph:Actor |






## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: Actor
description: General actor (person or group) responsible for events
from_schema: CulturalHeritageOntology
slots:
- name
- english_description
class_uri: crm:E39_Actor

```
</details>

### Induced

<details>
```yaml
name: Actor
description: General actor (person or group) responsible for events
from_schema: CulturalHeritageOntology
attributes:
  name:
    name: name
    description: Primary name or label
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P1_is_identified_by
    alias: name
    owner: Actor
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
    owner: Actor
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
class_uri: crm:E39_Actor

```
</details>