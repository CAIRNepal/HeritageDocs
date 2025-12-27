

# Class: ArchivalRecord 


_Government or institutional administrative record_





URI: [heritageGraph:ArchivalRecord](https://cair-nepal.org/heritageGraph/ArchivalRecord)





```mermaid
 classDiagram
    class ArchivalRecord
    click ArchivalRecord href "../ArchivalRecord/"
      DataSource <|-- ArchivalRecord
        click DataSource href "../DataSource/"
      
      ArchivalRecord : english_description
        
      ArchivalRecord : name
        
      ArchivalRecord : publication_timespan
        
          
    
        
        
        ArchivalRecord --> "0..1" TimeSpan : publication_timespan
        click TimeSpan href "../TimeSpan/"
    

        
      ArchivalRecord : source_citation
        
      ArchivalRecord : source_language
        
      ArchivalRecord : source_type
        
      ArchivalRecord : source_url
        
      
```





## Inheritance
* [DataSource](DataSource.md)
    * **ArchivalRecord**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [name](name.md) | 0..1 <br/> [String](String.md) | Primary name or label | [DataSource](DataSource.md) |
| [source_type](source_type.md) | 0..1 <br/> [String](String.md) | Type of source (manuscript, inscription, survey, oral) | [DataSource](DataSource.md) |
| [source_citation](source_citation.md) | 0..1 <br/> [String](String.md) | Formal citation of source | [DataSource](DataSource.md) |
| [source_url](source_url.md) | 0..1 <br/> [String](String.md) | URL or digital identifier for source | [DataSource](DataSource.md) |
| [source_language](source_language.md) | 0..1 <br/> [String](String.md) | Language of the source material | [DataSource](DataSource.md) |
| [publication_timespan](publication_timespan.md) | 0..1 <br/> [TimeSpan](TimeSpan.md) | When source was published | [DataSource](DataSource.md) |
| [english_description](english_description.md) | 0..1 <br/> [String](String.md) | Descriptive text in English | [DataSource](DataSource.md) |










## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | heritageGraph:ArchivalRecord |
| native | heritageGraph:ArchivalRecord |
| exact | rico:Record |
| broad | crm:E31_Document |






## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: ArchivalRecord
description: Government or institutional administrative record
from_schema: CulturalHeritageOntology
exact_mappings:
- rico:Record
broad_mappings:
- crm:E31_Document
is_a: DataSource
class_uri: heritageGraph:ArchivalRecord

```
</details>

### Induced

<details>
```yaml
name: ArchivalRecord
description: Government or institutional administrative record
from_schema: CulturalHeritageOntology
exact_mappings:
- rico:Record
broad_mappings:
- crm:E31_Document
is_a: DataSource
attributes:
  name:
    name: name
    description: Primary name or label
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P1_is_identified_by
    alias: name
    owner: ArchivalRecord
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
  source_type:
    name: source_type
    description: Type of source (manuscript, inscription, survey, oral)
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P2_has_type
    alias: source_type
    owner: ArchivalRecord
    domain_of:
    - DataSource
    range: string
  source_citation:
    name: source_citation
    description: Formal citation of source
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P3_has_note
    alias: source_citation
    owner: ArchivalRecord
    domain_of:
    - DataSource
    range: string
  source_url:
    name: source_url
    description: URL or digital identifier for source
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: heritageGraph:source_url
    alias: source_url
    owner: ArchivalRecord
    domain_of:
    - DataSource
    range: string
  source_language:
    name: source_language
    description: Language of the source material
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P72_has_language
    alias: source_language
    owner: ArchivalRecord
    domain_of:
    - DataSource
    range: string
  publication_timespan:
    name: publication_timespan
    description: When source was published
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P4_has_time-span
    alias: publication_timespan
    owner: ArchivalRecord
    domain_of:
    - DataSource
    range: TimeSpan
  english_description:
    name: english_description
    description: Descriptive text in English
    from_schema: CulturalHeritageOntology
    rank: 1000
    slot_uri: crm:P3_has_note
    alias: english_description
    owner: ArchivalRecord
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
class_uri: heritageGraph:ArchivalRecord

```
</details>