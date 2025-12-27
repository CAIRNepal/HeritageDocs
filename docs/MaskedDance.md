

# Class: MaskedDance 


_Festival featuring masked dancers embodying deities (e.g., Kartik Naach)_





URI: [heritageGraph:MaskedDance](https://cair-nepal.org/heritageGraph/MaskedDance)





```mermaid
 classDiagram
    class MaskedDance
    click MaskedDance href "../MaskedDance/"
      Festival <|-- MaskedDance
        click Festival href "../Festival/"
      
      MaskedDance : english_description
        
      MaskedDance : follows_tradition
        
          
    
        
        
        MaskedDance --> "0..1" TraditionOrPractice : follows_tradition
        click TraditionOrPractice href "../TraditionOrPractice/"
    

        
      MaskedDance : has_provenance_assertion
        
          
    
        
        
        MaskedDance --> "*" ProvenanceAssertion : has_provenance_assertion
        click ProvenanceAssertion href "../ProvenanceAssertion/"
    

        
      MaskedDance : has_timespan
        
          
    
        
        
        MaskedDance --> "0..1" TimeSpan : has_timespan
        click TimeSpan href "../TimeSpan/"
    

        
      MaskedDance : includes_ritual_event
        
          
    
        
        
        MaskedDance --> "*" RitualEvent : includes_ritual_event
        click RitualEvent href "../RitualEvent/"
    

        
      MaskedDance : invokes_deity
        
          
    
        
        
        MaskedDance --> "*" Deity : invokes_deity
        click Deity href "../Deity/"
    

        
      MaskedDance : is_part_of_festival
        
          
    
        
        
        MaskedDance --> "0..1" Festival : is_part_of_festival
        click Festival href "../Festival/"
    

        
      MaskedDance : lunar_date_tithi
        
      MaskedDance : managed_by_guthi
        
          
    
        
        
        MaskedDance --> "*" Guthi : managed_by_guthi
        click Guthi href "../Guthi/"
    

        
      MaskedDance : name
        
      MaskedDance : occurs_after
        
          
    
        
        
        MaskedDance --> "0..1" RitualEvent : occurs_after
        click RitualEvent href "../RitualEvent/"
    

        
      MaskedDance : occurs_before
        
          
    
        
        
        MaskedDance --> "0..1" RitualEvent : occurs_before
        click RitualEvent href "../RitualEvent/"
    

        
      MaskedDance : performed_by_actor
        
          
    
        
        
        MaskedDance --> "*" Person : performed_by_actor
        click Person href "../Person/"
    

        
      MaskedDance : performed_by_group
        
          
    
        
        
        MaskedDance --> "*" Guthi : performed_by_group
        click Guthi href "../Guthi/"
    

        
      MaskedDance : recurrence_pattern
        
      MaskedDance : ritual_on_structure
        
          
    
        
        
        MaskedDance --> "0..1" ArchitecturalStructure : ritual_on_structure
        click ArchitecturalStructure href "../ArchitecturalStructure/"
    

        
      MaskedDance : ritual_type
        
          
    
        
        
        MaskedDance --> "0..1" RitualTypeEnum : ritual_type
        click RitualTypeEnum href "../RitualTypeEnum/"
    

        
      MaskedDance : used_materials
        
          
    
        
        
        MaskedDance --> "*" Material : used_materials
        click Material href "../Material/"
    

        
      MaskedDance : was_documented_by
        
          
    
        
        
        MaskedDance --> "*" DocumentationActivity : was_documented_by
        click DocumentationActivity href "../DocumentationActivity/"
    

        
      
```





## Inheritance
* [RitualEvent](RitualEvent.md)
    * [Festival](Festival.md)
        * **MaskedDance**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [includes_ritual_event](includes_ritual_event.md) | * <br/> [RitualEvent](RitualEvent.md) | Component rituals of festival | [Festival](Festival.md) |
| [name](name.md) | 0..1 <br/> [String](String.md) | Primary name or label | [RitualEvent](RitualEvent.md) |
| [english_description](english_description.md) | 0..1 <br/> [String](String.md) | Descriptive text in English | [RitualEvent](RitualEvent.md) |
| [ritual_type](ritual_type.md) | 0..1 <br/> [RitualTypeEnum](RitualTypeEnum.md) | Classification of ritual (puja, jatra, consecration) | [RitualEvent](RitualEvent.md) |
| [ritual_on_structure](ritual_on_structure.md) | 0..1 <br/> [ArchitecturalStructure](ArchitecturalStructure.md) | Ritual occurs at specific temple or monument | [RitualEvent](RitualEvent.md) |
| [has_timespan](has_timespan.md) | 0..1 <br/> [TimeSpan](TimeSpan.md) | Links event to its temporal extent | [RitualEvent](RitualEvent.md) |
| [lunar_date_tithi](lunar_date_tithi.md) | 0..1 <br/> [String](String.md) | Lunar day (Tithi) for ritual timing | [RitualEvent](RitualEvent.md) |
| [recurrence_pattern](recurrence_pattern.md) | 0..1 <br/> [String](String.md) | Frequency of recurring ritual (e | [RitualEvent](RitualEvent.md) |
| [invokes_deity](invokes_deity.md) | * <br/> [Deity](Deity.md) | Deity invoked or made present through ritual | [RitualEvent](RitualEvent.md) |
| [performed_by_actor](performed_by_actor.md) | * <br/> [Person](Person.md) | Individual who performed ritual | [RitualEvent](RitualEvent.md) |
| [performed_by_group](performed_by_group.md) | * <br/> [Guthi](Guthi.md) | Group (Guthi, caste) responsible for ritual | [RitualEvent](RitualEvent.md) |
| [is_part_of_festival](is_part_of_festival.md) | 0..1 <br/> [Festival](Festival.md) | Larger festival this ritual is part of | [RitualEvent](RitualEvent.md) |
| [managed_by_guthi](managed_by_guthi.md) | * <br/> [Guthi](Guthi.md) | Guthi organization managing this structure or ritual | [RitualEvent](RitualEvent.md) |
| [follows_tradition](follows_tradition.md) | 0..1 <br/> [TraditionOrPractice](TraditionOrPractice.md) | Transmitted ritual protocol followed | [RitualEvent](RitualEvent.md) |
| [was_documented_by](was_documented_by.md) | * <br/> [DocumentationActivity](DocumentationActivity.md) | Documentation event that recorded this entity or event | [RitualEvent](RitualEvent.md) |
| [has_provenance_assertion](has_provenance_assertion.md) | * <br/> [ProvenanceAssertion](ProvenanceAssertion.md) | Provenance assertions about this entity or event | [RitualEvent](RitualEvent.md) |
| [occurs_before](occurs_before.md) | 0..1 <br/> [RitualEvent](RitualEvent.md) | Points to the next ritual in the canonical sequence | [RitualEvent](RitualEvent.md) |
| [occurs_after](occurs_after.md) | 0..1 <br/> [RitualEvent](RitualEvent.md) | Points to the prerequisite ritual | [RitualEvent](RitualEvent.md) |
| [used_materials](used_materials.md) | * <br/> [Material](Material.md) | Ephemeral materials consumed during the ritual (e | [RitualEvent](RitualEvent.md) |










## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | heritageGraph:MaskedDance |
| native | heritageGraph:MaskedDance |






## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: MaskedDance
description: Festival featuring masked dancers embodying deities (e.g., Kartik Naach)
from_schema: CulturalHeritageOntology
is_a: Festival
class_uri: heritageGraph:MaskedDance

```
</details>

### Induced

<details>
```yaml
name: MaskedDance
description: Festival featuring masked dancers embodying deities (e.g., Kartik Naach)
from_schema: CulturalHeritageOntology
is_a: Festival
attributes:
  includes_ritual_event:
    name: includes_ritual_event
    description: Component rituals of festival
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P9i_forms_part_of
    alias: includes_ritual_event
    owner: MaskedDance
    domain_of:
    - Festival
    range: RitualEvent
    multivalued: true
  name:
    name: name
    description: Primary name or label
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P1_is_identified_by
    alias: name
    owner: MaskedDance
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
    owner: MaskedDance
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
    owner: MaskedDance
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
    owner: MaskedDance
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
    owner: MaskedDance
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
    owner: MaskedDance
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
    owner: MaskedDance
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
    owner: MaskedDance
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
    owner: MaskedDance
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
    owner: MaskedDance
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
    owner: MaskedDance
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
    owner: MaskedDance
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
    owner: MaskedDance
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
    owner: MaskedDance
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
    owner: MaskedDance
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
    owner: MaskedDance
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
    owner: MaskedDance
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
    owner: MaskedDance
    domain_of:
    - RitualEvent
    range: Material
    multivalued: true
class_uri: heritageGraph:MaskedDance

```
</details>