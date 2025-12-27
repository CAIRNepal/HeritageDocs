# Enum: DatePrecisionEnum 



URI: [heritageGraph:DatePrecisionEnum](https://cair-nepal.org/heritageGraph/DatePrecisionEnum)

## Permissible Values

| Value | Meaning | Description |
| --- | --- | --- |
| Exact | None | Precise date known |
| Year | None | Year-level precision only |
| Decade | None | Within 10-year range |
| Century | None | Within century range |
| Circa | None | Approximate date |




## Slots

| Name | Description |
| ---  | --- |
| [date_precision](date_precision.md) | The level of precision for a recorded date |
| [date_precision](date_precision.md) |  |





## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology






## LinkML Source

<details>
```yaml
name: DatePrecisionEnum
from_schema: CulturalHeritageOntology
rank: 1000
permissible_values:
  Exact:
    text: Exact
    description: Precise date known
  Year:
    text: Year
    description: Year-level precision only
  Decade:
    text: Decade
    description: Within 10-year range
  Century:
    text: Century
    description: Within century range
  Circa:
    text: Circa
    description: Approximate date

```
</details>