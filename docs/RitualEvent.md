

# Class: RitualEvent 


_Intentional ritual activity that activates sacred space, invokes deities, and binds social groups_





URI: [crm:E7_Activity](http://www.cidoc-crm.org/cidoc-crm/E7_Activity)





```mermaid
 classDiagram
    class RitualEvent
    click RitualEvent href "../RitualEvent/"
      RitualEvent <|-- Puja
        click Puja href "../Puja/"
      RitualEvent <|-- Festival
        click Festival href "../Festival/"
      
      RitualEvent : english_description
        
      RitualEvent : follows_tradition
        
          
    
        
        
        RitualEvent --> "0..1" TraditionOrPractice : follows_tradition
        click TraditionOrPractice href "../TraditionOrPractice/"
    

        
      RitualEvent : has_provenance_assertion
        
          
    
        
        
        RitualEvent --> "*" ProvenanceAssertion : has_provenance_assertion
        click ProvenanceAssertion href "../ProvenanceAssertion/"
    

        
      RitualEvent : has_timespan
        
          
    
        
        
        RitualEvent --> "0..1" TimeSpan : has_timespan
        click TimeSpan href "../TimeSpan/"
    

        
      RitualEvent : invokes_deity
        
          
    
        
        
        RitualEvent --> "*" Deity : invokes_deity
        click Deity href "../Deity/"
    

        
      RitualEvent : is_part_of_festival
        
          
    
        
        
        RitualEvent --> "0..1" Festival : is_part_of_festival
        click Festival href "../Festival/"
    

        
      RitualEvent : lunar_date_tithi
        
      RitualEvent : managed_by_guthi
        
          
    
        
        
        RitualEvent --> "*" Guthi : managed_by_guthi
        click Guthi href "../Guthi/"
    

        
      RitualEvent : name
        
      RitualEvent : occurs_after
        
          
    
        
        
        RitualEvent --> "0..1" RitualEvent : occurs_after
        click RitualEvent href "../RitualEvent/"
    

        
      RitualEvent : occurs_before
        
          
    
        
        
        RitualEvent --> "0..1" RitualEvent : occurs_before
        click RitualEvent href "../RitualEvent/"
    

        
      RitualEvent : performed_by_actor
        
          
    
        
        
        RitualEvent --> "*" Person : performed_by_actor
        click Person href "../Person/"
    

        
      RitualEvent : performed_by_group
        
          
    
        
        
        RitualEvent --> "*" Guthi : performed_by_group
        click Guthi href "../Guthi/"
    

        
      RitualEvent : recurrence_pattern
        
      RitualEvent : ritual_on_structure
        
          
    
        
        
        RitualEvent --> "0..1" ArchitecturalStructure : ritual_on_structure
        click ArchitecturalStructure href "../ArchitecturalStructure/"
    

        
      RitualEvent : ritual_type
        
          
    
        
        
        RitualEvent --> "0..1" RitualTypeEnum : ritual_type
        click RitualTypeEnum href "../RitualTypeEnum/"
    

        
      RitualEvent : used_materials
        
          
    
        
        
        RitualEvent --> "*" Material : used_materials
        click Material href "../Material/"
    

        
      RitualEvent : was_documented_by
        
          
    
        
        
        RitualEvent --> "*" DocumentationActivity : was_documented_by
        click DocumentationActivity href "../DocumentationActivity/"
    

        
      
```





## Inheritance
* **RitualEvent**
    * [Puja](Puja.md)
    * [Festival](Festival.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [name](name.md) | 0..1 <br/> [String](String.md) | Primary name or label | direct |
| [english_description](english_description.md) | 0..1 <br/> [String](String.md) | Descriptive text in English | direct |
| [ritual_type](ritual_type.md) | 0..1 <br/> [RitualTypeEnum](RitualTypeEnum.md) | Classification of ritual (puja, jatra, consecration) | direct |
| [ritual_on_structure](ritual_on_structure.md) | 0..1 <br/> [ArchitecturalStructure](ArchitecturalStructure.md) | Ritual occurs at specific temple or monument | direct |
| [has_timespan](has_timespan.md) | 0..1 <br/> [TimeSpan](TimeSpan.md) | Links event to its temporal extent | direct |
| [lunar_date_tithi](lunar_date_tithi.md) | 0..1 <br/> [String](String.md) | Lunar day (Tithi) for ritual timing | direct |
| [recurrence_pattern](recurrence_pattern.md) | 0..1 <br/> [String](String.md) | Frequency of recurring ritual (e | direct |
| [invokes_deity](invokes_deity.md) | * <br/> [Deity](Deity.md) | Deity invoked or made present through ritual | direct |
| [performed_by_actor](performed_by_actor.md) | * <br/> [Person](Person.md) | Individual who performed ritual | direct |
| [performed_by_group](performed_by_group.md) | * <br/> [Guthi](Guthi.md) | Group (Guthi, caste) responsible for ritual | direct |
| [is_part_of_festival](is_part_of_festival.md) | 0..1 <br/> [Festival](Festival.md) | Larger festival this ritual is part of | direct |
| [managed_by_guthi](managed_by_guthi.md) | * <br/> [Guthi](Guthi.md) | Guthi organization managing this structure or ritual | direct |
| [follows_tradition](follows_tradition.md) | 0..1 <br/> [TraditionOrPractice](TraditionOrPractice.md) | Transmitted ritual protocol followed | direct |
| [was_documented_by](was_documented_by.md) | * <br/> [DocumentationActivity](DocumentationActivity.md) | Documentation event that recorded this entity or event | direct |
| [has_provenance_assertion](has_provenance_assertion.md) | * <br/> [ProvenanceAssertion](ProvenanceAssertion.md) | Provenance assertions about this entity or event | direct |
| [occurs_before](occurs_before.md) | 0..1 <br/> [RitualEvent](RitualEvent.md) | Points to the next ritual in the canonical sequence | direct |
| [occurs_after](occurs_after.md) | 0..1 <br/> [RitualEvent](RitualEvent.md) | Points to the prerequisite ritual | direct |
| [used_materials](used_materials.md) | * <br/> [Material](Material.md) | Ephemeral materials consumed during the ritual (e | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [ArchitecturalStructure](ArchitecturalStructure.md) | [participates_in_ritual](participates_in_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [Temple](Temple.md) | [participates_in_ritual](participates_in_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [BuddhistMonument](BuddhistMonument.md) | [participates_in_ritual](participates_in_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [Stupa](Stupa.md) | [participates_in_ritual](participates_in_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [Chaitya](Chaitya.md) | [participates_in_ritual](participates_in_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [RestHouse](RestHouse.md) | [participates_in_ritual](participates_in_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [Pati](Pati.md) | [participates_in_ritual](participates_in_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [Sattal](Sattal.md) | [participates_in_ritual](participates_in_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [Dharmashala](Dharmashala.md) | [participates_in_ritual](participates_in_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [WaterStructure](WaterStructure.md) | [participates_in_ritual](participates_in_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [DhungeDhara](DhungeDhara.md) | [participates_in_ritual](participates_in_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [Pokhari](Pokhari.md) | [participates_in_ritual](participates_in_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [IconographicObject](IconographicObject.md) | [participates_in_ritual](participates_in_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [Paubha](Paubha.md) | [participates_in_ritual](participates_in_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [Murti](Murti.md) | [participates_in_ritual](participates_in_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [Deity](Deity.md) | [is_invoked_in_ritual](is_invoked_in_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [RitualEvent](RitualEvent.md) | [occurs_before](occurs_before.md) | range | [RitualEvent](RitualEvent.md) |
| [RitualEvent](RitualEvent.md) | [occurs_after](occurs_after.md) | range | [RitualEvent](RitualEvent.md) |
| [Puja](Puja.md) | [occurs_before](occurs_before.md) | range | [RitualEvent](RitualEvent.md) |
| [Puja](Puja.md) | [occurs_after](occurs_after.md) | range | [RitualEvent](RitualEvent.md) |
| [NityaPuja](NityaPuja.md) | [occurs_before](occurs_before.md) | range | [RitualEvent](RitualEvent.md) |
| [NityaPuja](NityaPuja.md) | [occurs_after](occurs_after.md) | range | [RitualEvent](RitualEvent.md) |
| [NaimittikaPuja](NaimittikaPuja.md) | [occurs_before](occurs_before.md) | range | [RitualEvent](RitualEvent.md) |
| [NaimittikaPuja](NaimittikaPuja.md) | [occurs_after](occurs_after.md) | range | [RitualEvent](RitualEvent.md) |
| [Festival](Festival.md) | [includes_ritual_event](includes_ritual_event.md) | range | [RitualEvent](RitualEvent.md) |
| [Festival](Festival.md) | [occurs_before](occurs_before.md) | range | [RitualEvent](RitualEvent.md) |
| [Festival](Festival.md) | [occurs_after](occurs_after.md) | range | [RitualEvent](RitualEvent.md) |
| [ChariotFestival](ChariotFestival.md) | [includes_ritual_event](includes_ritual_event.md) | range | [RitualEvent](RitualEvent.md) |
| [ChariotFestival](ChariotFestival.md) | [occurs_before](occurs_before.md) | range | [RitualEvent](RitualEvent.md) |
| [ChariotFestival](ChariotFestival.md) | [occurs_after](occurs_after.md) | range | [RitualEvent](RitualEvent.md) |
| [MaskedDance](MaskedDance.md) | [includes_ritual_event](includes_ritual_event.md) | range | [RitualEvent](RitualEvent.md) |
| [MaskedDance](MaskedDance.md) | [occurs_before](occurs_before.md) | range | [RitualEvent](RitualEvent.md) |
| [MaskedDance](MaskedDance.md) | [occurs_after](occurs_after.md) | range | [RitualEvent](RitualEvent.md) |
| [Guthi](Guthi.md) | [performs_ritual](performs_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [SiGuthi](SiGuthi.md) | [performs_ritual](performs_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [JatraGuthi](JatraGuthi.md) | [performs_ritual](performs_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [PujaGuthi](PujaGuthi.md) | [performs_ritual](performs_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [TempleGuthi](TempleGuthi.md) | [performs_ritual](performs_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [NashaGuthi](NashaGuthi.md) | [performs_ritual](performs_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [SanaGuthi](SanaGuthi.md) | [performs_ritual](performs_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [SanGuthi](SanGuthi.md) | [performs_ritual](performs_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [RajGuthi](RajGuthi.md) | [performs_ritual](performs_ritual.md) | range | [RitualEvent](RitualEvent.md) |
| [Person](Person.md) | [carried_out_activity](carried_out_activity.md) | range | [RitualEvent](RitualEvent.md) |
| [ProvenanceAssertion](ProvenanceAssertion.md) | [asserts_about_event](asserts_about_event.md) | range | [RitualEvent](RitualEvent.md) |
| [FieldSurveyActivity](FieldSurveyActivity.md) | [documented_event](documented_event.md) | range | [RitualEvent](RitualEvent.md) |
| [OralHistoryInterview](OralHistoryInterview.md) | [documented_event](documented_event.md) | range | [RitualEvent](RitualEvent.md) |
| [DocumentationActivity](DocumentationActivity.md) | [documented_event](documented_event.md) | range | [RitualEvent](RitualEvent.md) |
| [Verification](Verification.md) | [documented_event](documented_event.md) | range | [RitualEvent](RitualEvent.md) |
| [Container](Container.md) | [ritual_events](ritual_events.md) | range | [RitualEvent](RitualEvent.md) |







## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | crm:E7_Activity |
| native | heritageGraph:RitualEvent |






## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: RitualEvent
description: Intentional ritual activity that activates sacred space, invokes deities,
  and binds social groups
from_schema: CulturalHeritageOntology
slots:
- name
- english_description
- ritual_type
- ritual_on_structure
- has_timespan
- lunar_date_tithi
- recurrence_pattern
- invokes_deity
- performed_by_actor
- performed_by_group
- is_part_of_festival
- managed_by_guthi
- follows_tradition
- was_documented_by
- has_provenance_assertion
- occurs_before
- occurs_after
- used_materials
class_uri: crm:E7_Activity

```
</details>

### Induced

<details>
```yaml
name: RitualEvent
description: Intentional ritual activity that activates sacred space, invokes deities,
  and binds social groups
from_schema: CulturalHeritageOntology
attributes:
  name:
    name: name
    description: Primary name or label
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P1_is_identified_by
    alias: name
    owner: RitualEvent
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
    owner: RitualEvent
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
  ritual_type:
    name: ritual_type
    description: Classification of ritual (puja, jatra, consecration)
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P2_has_type
    alias: ritual_type
    owner: RitualEvent
    domain_of:
    - RitualEvent
    range: RitualTypeEnum
  ritual_on_structure:
    name: ritual_on_structure
    description: Ritual occurs at specific temple or monument
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P8_took_place_on_or_within
    alias: ritual_on_structure
    owner: RitualEvent
    domain_of:
    - RitualEvent
    range: ArchitecturalStructure
  has_timespan:
    name: has_timespan
    description: Links event to its temporal extent
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P4_has_time-span
    alias: has_timespan
    owner: RitualEvent
    domain_of:
    - Production
    - RitualEvent
    - Consecration
    - Enshrinement
    - TransferOfCustody
    - ConditionAssessment
    - DocumentationActivity
    range: TimeSpan
  lunar_date_tithi:
    name: lunar_date_tithi
    description: Lunar day (Tithi) for ritual timing
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: heritageGraph:lunar_date_tithi
    alias: lunar_date_tithi
    owner: RitualEvent
    domain_of:
    - RitualEvent
    range: string
  recurrence_pattern:
    name: recurrence_pattern
    description: Frequency of recurring ritual (e.g., annual, monthly)
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: heritageGraph:recurrence_pattern
    alias: recurrence_pattern
    owner: RitualEvent
    domain_of:
    - RitualEvent
    range: string
  invokes_deity:
    name: invokes_deity
    description: Deity invoked or made present through ritual
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P12_occurred_in_the_presence_of
    alias: invokes_deity
    owner: RitualEvent
    domain_of:
    - RitualEvent
    range: Deity
    multivalued: true
  performed_by_actor:
    name: performed_by_actor
    description: Individual who performed ritual
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P14_carried_out_by
    alias: performed_by_actor
    owner: RitualEvent
    domain_of:
    - RitualEvent
    - Consecration
    - Enshrinement
    range: Person
    multivalued: true
  performed_by_group:
    name: performed_by_group
    description: Group (Guthi, caste) responsible for ritual
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P14_carried_out_by
    alias: performed_by_group
    owner: RitualEvent
    domain_of:
    - RitualEvent
    range: Guthi
    multivalued: true
  is_part_of_festival:
    name: is_part_of_festival
    description: Larger festival this ritual is part of
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P9_consists_of
    alias: is_part_of_festival
    owner: RitualEvent
    domain_of:
    - RitualEvent
    range: Festival
  managed_by_guthi:
    name: managed_by_guthi
    description: Guthi organization managing this structure or ritual
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: heritageGraph:managed_by_guthi
    alias: managed_by_guthi
    owner: RitualEvent
    domain_of:
    - RitualEvent
    range: Guthi
    multivalued: true
  follows_tradition:
    name: follows_tradition
    description: Transmitted ritual protocol followed
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P33_used_specific_technique
    alias: follows_tradition
    owner: RitualEvent
    domain_of:
    - RitualEvent
    range: TraditionOrPractice
  was_documented_by:
    name: was_documented_by
    description: Documentation event that recorded this entity or event
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: prov:wasGeneratedBy
    alias: was_documented_by
    owner: RitualEvent
    domain_of:
    - ArchitecturalStructure
    - Production
    - RitualEvent
    range: DocumentationActivity
    multivalued: true
  has_provenance_assertion:
    name: has_provenance_assertion
    description: Provenance assertions about this entity or event
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: heritageGraph:has_provenance_assertion
    alias: has_provenance_assertion
    owner: RitualEvent
    domain_of:
    - Production
    - RitualEvent
    range: ProvenanceAssertion
    multivalued: true
  occurs_before:
    name: occurs_before
    description: Points to the next ritual in the canonical sequence.
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P120_occurs_before
    alias: occurs_before
    owner: RitualEvent
    domain_of:
    - RitualEvent
    range: RitualEvent
  occurs_after:
    name: occurs_after
    description: Points to the prerequisite ritual.
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P120i_is_occurred_before_by
    alias: occurs_after
    owner: RitualEvent
    domain_of:
    - RitualEvent
    range: RitualEvent
  used_materials:
    name: used_materials
    description: Ephemeral materials consumed during the ritual (e.g., oil, rice).
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P125_used_object_of_type
    alias: used_materials
    owner: RitualEvent
    domain_of:
    - RitualEvent
    range: Material
    multivalued: true
class_uri: crm:E7_Activity

```
</details>