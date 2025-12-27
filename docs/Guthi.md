

# Class: Guthi 


_Endowed trust organization unique to Nepal, managing temples, rituals, and land through hereditary or voluntary membership_





URI: [crm:E74_Group](http://www.cidoc-crm.org/cidoc-crm/E74_Group)





```mermaid
 classDiagram
    class Guthi
    click Guthi href "../Guthi/"
      Guthi <|-- SiGuthi
        click SiGuthi href "../SiGuthi/"
      Guthi <|-- JatraGuthi
        click JatraGuthi href "../JatraGuthi/"
      Guthi <|-- PujaGuthi
        click PujaGuthi href "../PujaGuthi/"
      Guthi <|-- TempleGuthi
        click TempleGuthi href "../TempleGuthi/"
      Guthi <|-- NashaGuthi
        click NashaGuthi href "../NashaGuthi/"
      Guthi <|-- SanaGuthi
        click SanaGuthi href "../SanaGuthi/"
      Guthi <|-- SanGuthi
        click SanGuthi href "../SanGuthi/"
      Guthi <|-- RajGuthi
        click RajGuthi href "../RajGuthi/"
      
      Guthi : english_description
        
      Guthi : founded_by_event
        
          
    
        
        
        Guthi --> "0..1" Production : founded_by_event
        click Production href "../Production/"
    

        
      Guthi : guthi_type
        
          
    
        
        
        Guthi --> "0..1" GuthiTypeEnum : guthi_type
        click GuthiTypeEnum href "../GuthiTypeEnum/"
    

        
      Guthi : has_land_endowment
        
      Guthi : has_membership
        
          
    
        
        
        Guthi --> "*" Person : has_membership
        click Person href "../Person/"
    

        
      Guthi : holds_custody_of
        
          
    
        
        
        Guthi --> "*" ArchitecturalStructure : holds_custody_of
        click ArchitecturalStructure href "../ArchitecturalStructure/"
    

        
      Guthi : manages_structure
        
          
    
        
        
        Guthi --> "*" ArchitecturalStructure : manages_structure
        click ArchitecturalStructure href "../ArchitecturalStructure/"
    

        
      Guthi : name
        
      Guthi : performs_ritual
        
          
    
        
        
        Guthi --> "*" RitualEvent : performs_ritual
        click RitualEvent href "../RitualEvent/"
    

        
      
```





## Inheritance
* **Guthi**
    * [SiGuthi](SiGuthi.md)
    * [JatraGuthi](JatraGuthi.md)
    * [PujaGuthi](PujaGuthi.md)
    * [TempleGuthi](TempleGuthi.md)
    * [NashaGuthi](NashaGuthi.md)
    * [SanaGuthi](SanaGuthi.md)
    * [SanGuthi](SanGuthi.md)
    * [RajGuthi](RajGuthi.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [name](name.md) | 0..1 <br/> [String](String.md) | Primary name or label | direct |
| [english_description](english_description.md) | 0..1 <br/> [String](String.md) | Descriptive text in English | direct |
| [guthi_type](guthi_type.md) | 0..1 <br/> [GuthiTypeEnum](GuthiTypeEnum.md) | Type of Guthi (Si, Jatra, Temple) | direct |
| [manages_structure](manages_structure.md) | * <br/> [ArchitecturalStructure](ArchitecturalStructure.md) | Structures managed by this Guthi | direct |
| [performs_ritual](performs_ritual.md) | * <br/> [RitualEvent](RitualEvent.md) | Rituals performed by this Guthi | direct |
| [holds_custody_of](holds_custody_of.md) | * <br/> [ArchitecturalStructure](ArchitecturalStructure.md) | Structures under Guthi custodianship | direct |
| [has_membership](has_membership.md) | * <br/> [Person](Person.md) | Members of Guthi organization | direct |
| [founded_by_event](founded_by_event.md) | 0..1 <br/> [Production](Production.md) | Event that established the Guthi | direct |
| [has_land_endowment](has_land_endowment.md) | 0..1 <br/> [String](String.md) | Description of land holdings supporting Guthi | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [RitualEvent](RitualEvent.md) | [performed_by_group](performed_by_group.md) | range | [Guthi](Guthi.md) |
| [RitualEvent](RitualEvent.md) | [managed_by_guthi](managed_by_guthi.md) | range | [Guthi](Guthi.md) |
| [Puja](Puja.md) | [performed_by_group](performed_by_group.md) | range | [Guthi](Guthi.md) |
| [Puja](Puja.md) | [managed_by_guthi](managed_by_guthi.md) | range | [Guthi](Guthi.md) |
| [NityaPuja](NityaPuja.md) | [performed_by_group](performed_by_group.md) | range | [Guthi](Guthi.md) |
| [NityaPuja](NityaPuja.md) | [managed_by_guthi](managed_by_guthi.md) | range | [Guthi](Guthi.md) |
| [NaimittikaPuja](NaimittikaPuja.md) | [performed_by_group](performed_by_group.md) | range | [Guthi](Guthi.md) |
| [NaimittikaPuja](NaimittikaPuja.md) | [managed_by_guthi](managed_by_guthi.md) | range | [Guthi](Guthi.md) |
| [Festival](Festival.md) | [performed_by_group](performed_by_group.md) | range | [Guthi](Guthi.md) |
| [Festival](Festival.md) | [managed_by_guthi](managed_by_guthi.md) | range | [Guthi](Guthi.md) |
| [ChariotFestival](ChariotFestival.md) | [performed_by_group](performed_by_group.md) | range | [Guthi](Guthi.md) |
| [ChariotFestival](ChariotFestival.md) | [managed_by_guthi](managed_by_guthi.md) | range | [Guthi](Guthi.md) |
| [MaskedDance](MaskedDance.md) | [performed_by_group](performed_by_group.md) | range | [Guthi](Guthi.md) |
| [MaskedDance](MaskedDance.md) | [managed_by_guthi](managed_by_guthi.md) | range | [Guthi](Guthi.md) |
| [TransferOfCustody](TransferOfCustody.md) | [transferred_to_guthi](transferred_to_guthi.md) | range | [Guthi](Guthi.md) |
| [Person](Person.md) | [member_of_group](member_of_group.md) | range | [Guthi](Guthi.md) |
| [Container](Container.md) | [guthis](guthis.md) | range | [Guthi](Guthi.md) |







## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:E74_Group |
| native | heritageGraph:Guthi |






## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: Guthi
description: Endowed trust organization unique to Nepal, managing temples, rituals,
  and land through hereditary or voluntary membership
from_schema: CulturalHeritageOntology
slots:
- name
- english_description
- guthi_type
- manages_structure
- performs_ritual
- holds_custody_of
- has_membership
- founded_by_event
- has_land_endowment
slot_usage:
  guthi_type:
    name: guthi_type
    range: GuthiTypeEnum
class_uri: crm:E74_Group

```
</details>

### Induced

<details>
```yaml
name: Guthi
description: Endowed trust organization unique to Nepal, managing temples, rituals,
  and land through hereditary or voluntary membership
from_schema: CulturalHeritageOntology
slot_usage:
  guthi_type:
    name: guthi_type
    range: GuthiTypeEnum
attributes:
  name:
    name: name
    description: Primary name or label
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P1_is_identified_by
    alias: name
    owner: Guthi
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
    owner: Guthi
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
  guthi_type:
    name: guthi_type
    description: Type of Guthi (Si, Jatra, Temple)
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P2_has_type
    alias: guthi_type
    owner: Guthi
    domain_of:
    - Guthi
    range: GuthiTypeEnum
  manages_structure:
    name: manages_structure
    description: Structures managed by this Guthi
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: heritageGraph:manages_structure
    alias: manages_structure
    owner: Guthi
    domain_of:
    - Guthi
    range: ArchitecturalStructure
    multivalued: true
  performs_ritual:
    name: performs_ritual
    description: Rituals performed by this Guthi
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P14i_performed
    alias: performs_ritual
    owner: Guthi
    domain_of:
    - Guthi
    range: RitualEvent
    multivalued: true
  holds_custody_of:
    name: holds_custody_of
    description: Structures under Guthi custodianship
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P52_has_current_owner
    alias: holds_custody_of
    owner: Guthi
    domain_of:
    - Guthi
    range: ArchitecturalStructure
    multivalued: true
  has_membership:
    name: has_membership
    description: Members of Guthi organization
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P107_has_current_or_former_member
    alias: has_membership
    owner: Guthi
    domain_of:
    - Guthi
    range: Person
    multivalued: true
  founded_by_event:
    name: founded_by_event
    description: Event that established the Guthi
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P95i_was_formed_by
    alias: founded_by_event
    owner: Guthi
    domain_of:
    - Guthi
    range: Production
  has_land_endowment:
    name: has_land_endowment
    description: Description of land holdings supporting Guthi
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: heritageGraph:has_land_endowment
    alias: has_land_endowment
    owner: Guthi
    domain_of:
    - Guthi
    range: string
class_uri: crm:E74_Group

```
</details>