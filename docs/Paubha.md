

# Class: Paubha 


_Traditional Newari scroll painting (thangka) with mandala and deity iconography_





URI: [heritageGraph:Paubha](https://cair-nepal.org/heritageGraph/Paubha)





```mermaid
 classDiagram
    class Paubha
    click Paubha href "../Paubha/"
      IconographicObject <|-- Paubha
        click IconographicObject href "../IconographicObject/"
      
      Paubha : depicts_deity
        
          
    
        
        
        Paubha --> "*" Deity : depicts_deity
        click Deity href "../Deity/"
    

        
      Paubha : english_description
        
      Paubha : name
        
      Paubha : participates_in_ritual
        
          
    
        
        
        Paubha --> "*" RitualEvent : participates_in_ritual
        click RitualEvent href "../RitualEvent/"
    

        
      Paubha : was_produced_by_event
        
          
    
        
        
        Paubha --> "0..1" Production : was_produced_by_event
        click Production href "../Production/"
    

        
      
```





## Inheritance
* [IconographicObject](IconographicObject.md)
    * **Paubha**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [name](name.md) | 0..1 <br/> [String](String.md) | Primary name or label | [IconographicObject](IconographicObject.md) |
| [english_description](english_description.md) | 0..1 <br/> [String](String.md) | Descriptive text in English | [IconographicObject](IconographicObject.md) |
| [depicts_deity](depicts_deity.md) | * <br/> [Deity](Deity.md) | Deity depicted iconographically (not cultic presence) | [IconographicObject](IconographicObject.md) |
| [was_produced_by_event](was_produced_by_event.md) | 0..1 <br/> [Production](Production.md) | Event that created this object or structure | [IconographicObject](IconographicObject.md) |
| [participates_in_ritual](participates_in_ritual.md) | * <br/> [RitualEvent](RitualEvent.md) | Rituals in which this structure participates | [IconographicObject](IconographicObject.md) |










## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | heritageGraph:Paubha |
| native | heritageGraph:Paubha |






## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: Paubha
description: Traditional Newari scroll painting (thangka) with mandala and deity iconography
from_schema: CulturalHeritageOntology
is_a: IconographicObject
class_uri: heritageGraph:Paubha

```
</details>

### Induced

<details>
```yaml
name: Paubha
description: Traditional Newari scroll painting (thangka) with mandala and deity iconography
from_schema: CulturalHeritageOntology
is_a: IconographicObject
attributes:
  name:
    name: name
    description: Primary name or label
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P1_is_identified_by
    alias: name
    owner: Paubha
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
    owner: Paubha
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
  depicts_deity:
    name: depicts_deity
    description: Deity depicted iconographically (not cultic presence)
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P62_depicts
    alias: depicts_deity
    owner: Paubha
    domain_of:
    - IconographicObject
    range: Deity
    multivalued: true
  was_produced_by_event:
    name: was_produced_by_event
    description: Event that created this object or structure
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P108i_was_produced_by
    alias: was_produced_by_event
    owner: Paubha
    domain_of:
    - ArchitecturalStructure
    - IconographicObject
    range: Production
  participates_in_ritual:
    name: participates_in_ritual
    description: Rituals in which this structure participates
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P12i_was_present_at
    alias: participates_in_ritual
    owner: Paubha
    domain_of:
    - ArchitecturalStructure
    - IconographicObject
    range: RitualEvent
    multivalued: true
class_uri: heritageGraph:Paubha

```
</details>