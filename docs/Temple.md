

# Class: Temple 


_Sacred architectural structure legally classified as an 'Ancient Monument' under Nepal's preservation laws, characterized by deity enshrinement and ritual activation._





URI: [heritageGraph:Temple](https://cair-nepal.org/heritageGraph/Temple)





```mermaid
 classDiagram
    class Temple
    click Temple href "../Temple/"
      ArchitecturalStructure <|-- Temple
        click ArchitecturalStructure href "../ArchitecturalStructure/"
      
      Temple : english_description
        
      Temple : enshrines_deity_through_event
        
          
    
        
        
        Temple --> "*" Enshrinement : enshrines_deity_through_event
        click Enshrinement href "../Enshrinement/"
    

        
      Temple : has_architectural_style
        
          
    
        
        
        Temple --> "1" ArchitecturalStyleEnum : has_architectural_style
        click ArchitecturalStyleEnum href "../ArchitecturalStyleEnum/"
    

        
      Temple : has_component
        
          
    
        
        
        Temple --> "*" ArchitecturalElement : has_component
        click ArchitecturalElement href "../ArchitecturalElement/"
    

        
      Temple : has_condition_assessment
        
          
    
        
        
        Temple --> "*" ConditionAssessment : has_condition_assessment
        click ConditionAssessment href "../ConditionAssessment/"
    

        
      Temple : has_current_location
        
          
    
        
        
        Temple --> "1" Place : has_current_location
        click Place href "../Place/"
    

        
      Temple : has_custody_event
        
          
    
        
        
        Temple --> "*" TransferOfCustody : has_custody_event
        click TransferOfCustody href "../TransferOfCustody/"
    

        
      Temple : name
        
      Temple : participates_in_ritual
        
          
    
        
        
        Temple --> "*" RitualEvent : participates_in_ritual
        click RitualEvent href "../RitualEvent/"
    

        
      Temple : was_documented_by
        
          
    
        
        
        Temple --> "*" DocumentationActivity : was_documented_by
        click DocumentationActivity href "../DocumentationActivity/"
    

        
      Temple : was_produced_by_event
        
          
    
        
        
        Temple --> "0..1" Production : was_produced_by_event
        click Production href "../Production/"
    

        
      
```





## Inheritance
* [ArchitecturalStructure](ArchitecturalStructure.md)
    * **Temple**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [enshrines_deity_through_event](enshrines_deity_through_event.md) | * <br/> [Enshrinement](Enshrinement.md) | Enshrinement event that installed deity in temple | direct |
| [has_architectural_style](has_architectural_style.md) | 1 <br/> [ArchitecturalStyleEnum](ArchitecturalStyleEnum.md) | Architectural style classification | direct |
| [name](name.md) | 1 <br/> [String](String.md) | Primary name or label | [ArchitecturalStructure](ArchitecturalStructure.md) |
| [english_description](english_description.md) | 0..1 <br/> [String](String.md) | Descriptive text in English | [ArchitecturalStructure](ArchitecturalStructure.md) |
| [was_produced_by_event](was_produced_by_event.md) | 0..1 <br/> [Production](Production.md) | Event that created this object or structure | [ArchitecturalStructure](ArchitecturalStructure.md) |
| [has_current_location](has_current_location.md) | 1 <br/> [Place](Place.md) | Current location of object or structure | [ArchitecturalStructure](ArchitecturalStructure.md) |
| [participates_in_ritual](participates_in_ritual.md) | * <br/> [RitualEvent](RitualEvent.md) | Rituals in which this structure participates | [ArchitecturalStructure](ArchitecturalStructure.md) |
| [has_custody_event](has_custody_event.md) | * <br/> [TransferOfCustody](TransferOfCustody.md) | Custody transfer events for this structure | [ArchitecturalStructure](ArchitecturalStructure.md) |
| [was_documented_by](was_documented_by.md) | * <br/> [DocumentationActivity](DocumentationActivity.md) | Documentation event that recorded this entity or event | [ArchitecturalStructure](ArchitecturalStructure.md) |
| [has_condition_assessment](has_condition_assessment.md) | * <br/> [ConditionAssessment](ConditionAssessment.md) | Condition assessment events for this structure | [ArchitecturalStructure](ArchitecturalStructure.md) |
| [has_component](has_component.md) | * <br/> [ArchitecturalElement](ArchitecturalElement.md) | Architectural elements composing structure | [ArchitecturalStructure](ArchitecturalStructure.md) |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Enshrinement](Enshrinement.md) | [enshrined_in_structure](enshrined_in_structure.md) | range | [Temple](Temple.md) |







## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | heritageGraph:Temple |
| native | heritageGraph:Temple |
| exact | schema:HinduTemple, aat:300007595, wd:Q44539 |
| broad | dbo:ReligiousBuilding |






## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: Temple
description: Sacred architectural structure legally classified as an 'Ancient Monument'
  under Nepal's preservation laws, characterized by deity enshrinement and ritual
  activation.
from_schema: CulturalHeritageOntology
exact_mappings:
- schema:HinduTemple
- aat:300007595
- wd:Q44539
broad_mappings:
- dbo:ReligiousBuilding
is_a: ArchitecturalStructure
slots:
- enshrines_deity_through_event
- has_architectural_style
slot_usage:
  has_architectural_style:
    name: has_architectural_style
    range: ArchitecturalStyleEnum
    required: true
class_uri: heritageGraph:Temple

```
</details>

### Induced

<details>
```yaml
name: Temple
description: Sacred architectural structure legally classified as an 'Ancient Monument'
  under Nepal's preservation laws, characterized by deity enshrinement and ritual
  activation.
from_schema: CulturalHeritageOntology
exact_mappings:
- schema:HinduTemple
- aat:300007595
- wd:Q44539
broad_mappings:
- dbo:ReligiousBuilding
is_a: ArchitecturalStructure
slot_usage:
  has_architectural_style:
    name: has_architectural_style
    range: ArchitecturalStyleEnum
    required: true
attributes:
  enshrines_deity_through_event:
    name: enshrines_deity_through_event
    description: Enshrinement event that installed deity in temple
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: heritageGraph:enshrines_deity_through_event
    alias: enshrines_deity_through_event
    owner: Temple
    domain_of:
    - Temple
    range: Enshrinement
    multivalued: true
  has_architectural_style:
    name: has_architectural_style
    description: Architectural style classification
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P2_has_type
    alias: has_architectural_style
    owner: Temple
    domain_of:
    - Temple
    range: ArchitecturalStyleEnum
    required: true
  name:
    name: name
    description: Primary name or label
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P1_is_identified_by
    alias: name
    owner: Temple
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
    owner: Temple
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
    owner: Temple
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
    owner: Temple
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
    owner: Temple
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
    owner: Temple
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
    owner: Temple
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
    owner: Temple
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
    owner: Temple
    domain_of:
    - ArchitecturalStructure
    range: ArchitecturalElement
    multivalued: true
class_uri: heritageGraph:Temple

```
</details>