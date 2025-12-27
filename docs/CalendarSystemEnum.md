# Enum: CalendarSystemEnum 



URI: [heritageGraph:CalendarSystemEnum](https://cair-nepal.org/heritageGraph/CalendarSystemEnum)

## Permissible Values

| Value | Meaning | Description |
| --- | --- | --- |
| Gregorian | heritageGraph:GregorianCalendar | ISO 8601 Gregorian calendar |
| BikramSambat | heritageGraph:BikramSambatCalendar | Official Nepali calendar (BS), epoch 57 BCE |
| NepalSambat | heritageGraph:NepalSambatCalendar | Newar cultural calendar (NS), epoch 879 CE |
| LunarTithi | heritageGraph:LunarCalendar | Hindu lunar calendar by tithi (lunar day) |




## Slots

| Name | Description |
| ---  | --- |
| [calendar_system](calendar_system.md) | Calendar system used for date representation |
| [calendar_system](calendar_system.md) |  |
| [calendar_system](calendar_system.md) |  |





## Identifier and Mapping Information






### Schema Source


* from schema: CulturalHeritageOntology






## LinkML Source

<details>
```yaml
name: CalendarSystemEnum
from_schema: CulturalHeritageOntology
rank: 1000
permissible_values:
  Gregorian:
    text: Gregorian
    description: ISO 8601 Gregorian calendar
    meaning: heritageGraph:GregorianCalendar
  BikramSambat:
    text: BikramSambat
    description: Official Nepali calendar (BS), epoch 57 BCE
    meaning: heritageGraph:BikramSambatCalendar
  NepalSambat:
    text: NepalSambat
    description: Newar cultural calendar (NS), epoch 879 CE
    meaning: heritageGraph:NepalSambatCalendar
  LunarTithi:
    text: LunarTithi
    description: Hindu lunar calendar by tithi (lunar day)
    meaning: heritageGraph:LunarCalendar

```
</details>