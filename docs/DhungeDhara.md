

# Class: DhungeDhara 


_Stone spout (hiti) with carved imagery, used for ritual bathing and daily water supply_





URI: [heritageGraph:DhungeDhara](https://cair-nepal.org/heritageGraph/DhungeDhara)





```mermaid
 classDiagram
    class DhungeDhara
    click DhungeDhara href "../DhungeDhara/"
      WaterStructure <|-- DhungeDhara
        click WaterStructure href "../WaterStructure/"
      
      DhungeDhara : english_description
        
      DhungeDhara : has_component
        
          
    
        
        
        DhungeDhara --> "*" ArchitecturalElement : has_component
        click ArchitecturalElement href "../ArchitecturalElement/"
    

        
      DhungeDhara : has_condition_assessment
        
          
    
        
        
        DhungeDhara --> "*" ConditionAssessment : has_condition_assessment
        click ConditionAssessment href "../ConditionAssessment/"
    

        
      DhungeDhara : has_current_location
        
          
    
        
        
        DhungeDhara --> "1" Place : has_current_location
        click Place href "../Place/"
    

        
      DhungeDhara : has_custody_event
        
          
    
        
        
        DhungeDhara --> "*" TransferOfCustody : has_custody_event
        click TransferOfCustody href "../TransferOfCustody/"
    

        
      DhungeDhara : name
        
      DhungeDhara : participates_in_ritual
        
          
    
        
        
        DhungeDhara --> "*" RitualEvent : participates_in_ritual
        click RitualEvent href "../RitualEvent/"
    

        
      DhungeDhara : was_documented_by
        
          
    
        
        
        DhungeDhara --> "*" DocumentationActivity : was_documented_by
        click DocumentationActivity href "../DocumentationActivity/"
    

        
      DhungeDhara : was_produced_by_event
        
          
    
        
        
        DhungeDhara --> "0..1" Production : was_produced_by_event
        click Production href "../Production/"
    

        
      
```





## Inheritance
* [ArchitecturalStructure](ArchitecturalStructure.md)
    * [WaterStructure](WaterStructure.md)
        * **DhungeDhara**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [name](name.md) | 1 <br/> [String](String.md) | Primary name or label | [ArchitecturalStructure](ArchitecturalStructure.md) |
| [english_description](english_description.md) | 0..1 <br/> [String](String.md) | Descriptive text in English | [ArchitecturalStructure](ArchitecturalStructure.md) |
| [was_produced_by_event](was_produced_by_event.md) | 0..1 <br/> [Production](Production.md) | Event that created this object or structure | [ArchitecturalStructure](ArchitecturalStructure.md) |
| [has_current_location](has_current_location.md) | 1 <br/> [Place](Place.md) | Current location of object or structure | [ArchitecturalStructure](ArchitecturalStructure.md) |
| [participates_in_ritual](participates_in_ritual.md) | * <br/> [RitualEvent](RitualEvent.md) | Rituals in which this structure participates | [ArchitecturalStructure](ArchitecturalStructure.md) |
| [has_custody_event](has_custody_event.md) | * <br/> [TransferOfCustody](TransferOfCustody.md) | Custody transfer events for this structure | [ArchitecturalStructure](ArchitecturalStructure.md) |
| [was_documented_by](was_documented_by.md) | * <br/> [DocumentationActivity](DocumentationActivity.md) | Documentation event that recorded this entity or event | [ArchitecturalStructure](ArchitecturalStructure.md) |
| [has_condition_assessment](has_condition_assessment.md) | * <br/> [ConditionAssessment](ConditionAssessment.md) | Condition assessment events for this structure | [ArchitecturalStructure](ArchitecturalStructure.md) |
| [has_component](has_component.md) | * <br/> [ArchitecturalElement](ArchitecturalElement.md) | Architectural elements composing structure | [ArchitecturalStructure](ArchitecturalStructure.md) |










## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | heritageGraph:DhungeDhara |
| native | heritageGraph:DhungeDhara |






## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: DhungeDhara
description: Stone spout (hiti) with carved imagery, used for ritual bathing and daily
  water supply
from_schema: CulturalHeritageOntology
is_a: WaterStructure
class_uri: heritageGraph:DhungeDhara

```
</details>

### Induced

<details>
```yaml
name: DhungeDhara
description: Stone spout (hiti) with carved imagery, used for ritual bathing and daily
  water supply
from_schema: CulturalHeritageOntology
is_a: WaterStructure
attributes:
  name:
    name: name
    description: Primary name or label
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P1_is_identified_by
    alias: name
    owner: DhungeDhara
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
    required: true
  english_description:
    name: english_description
    description: Descriptive text in English
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P3_has_note
    alias: english_description
    owner: DhungeDhara
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
  was_produced_by_event:
    name: was_produced_by_event
    description: Event that created this object or structure
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P108i_was_produced_by
    alias: was_produced_by_event
    owner: DhungeDhara
    domain_of:
    - ArchitecturalStructure
    - IconographicObject
    range: Production
  has_current_location:
    name: has_current_location
    description: Current location of object or structure
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P55_has_current_location
    alias: has_current_location
    owner: DhungeDhara
    domain_of:
    - ArchitecturalStructure
    range: Place
    required: true
    minimum_cardinality: 1
    maximum_cardinality: 1
  participates_in_ritual:
    name: participates_in_ritual
    description: Rituals in which this structure participates
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P12i_was_present_at
    alias: participates_in_ritual
    owner: DhungeDhara
    domain_of:
    - ArchitecturalStructure
    - IconographicObject
    range: RitualEvent
    multivalued: true
  has_custody_event:
    name: has_custody_event
    description: Custody transfer events for this structure
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:E10_Transfer_of_Custody
    alias: has_custody_event
    owner: DhungeDhara
    domain_of:
    - ArchitecturalStructure
    range: TransferOfCustody
    multivalued: true
  was_documented_by:
    name: was_documented_by
    description: Documentation event that recorded this entity or event
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: prov:wasGeneratedBy
    alias: was_documented_by
    owner: DhungeDhara
    domain_of:
    - ArchitecturalStructure
    - Production
    - RitualEvent
    range: DocumentationActivity
    multivalued: true
  has_condition_assessment:
    name: has_condition_assessment
    description: Condition assessment events for this structure
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P44_has_condition
    alias: has_condition_assessment
    owner: DhungeDhara
    domain_of:
    - ArchitecturalStructure
    range: ConditionAssessment
    multivalued: true
  has_component:
    name: has_component
    description: Architectural elements composing structure
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P46_is_composed_of
    alias: has_component
    owner: DhungeDhara
    domain_of:
    - ArchitecturalStructure
    range: ArchitecturalElement
    multivalued: true
class_uri: heritageGraph:DhungeDhara

```
</details>