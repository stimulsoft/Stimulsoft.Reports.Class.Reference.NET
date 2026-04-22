---
title: "Funcs Class"
---

## Funcs Class

**Namespace:** `Stimulsoft.Data.Functions`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class Funcs
```

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Abs** `static` | decimal |  |
| **AbsObject** `static` | object |  |
| **Acos** `static` | double |  |
| **AcosObject** `static` | object |  |
| **AddMonthsObject** `static` | object |  |
| **AddYears** `static` | DateTime |  |
| **AddYearsObject** `static` | object |  |
| **All** `static` | object |  |
| **Asin** `static` | double |  |
| **AsinObject** `static` | object |  |
| **Atan** `static` | double |  |
| **AtanObject** `static` | object |  |
| **Avg** `static` | decimal |  |
| **AvgD** `static` | double |  |
| **AvgDate** `static` | DateTime? |  |
| **AvgI** `static` | long |  |
| **AvgNulls** `static` | decimal? |  |
| **AvgTime** `static` | TimeSpan? |  |
| **AvgWeighted** `static` | decimal |  |
| **Calculate** `static` | object |  |
| **Ceiling** `static` | decimal |  |
| **CeilingObject** `static` | object |  |
| **Clamp** `static` | decimal |  |
| **ClampObject** `static` | object |  |
| **Cos** `static` | double |  |
| **CosObject** `static` | object |  |
| **Count** `static` | long |  |
| **CountIf** `static` | long |  |
| **DateDiff** `static` | TimeSpan? |  |
| **DateDiffObject** `static` | object |  |
| **DateTime** `static` | object |  |
| **Day** `static` | int |  |
| **DayObject** `static` | object |  |
| **DayOfWeek** `static` *(+3 overloads)* | string |  |
| **DayOfWeekIdent** `static` | DayOfWeek? |  |
| **DayOfWeekIdentObject** `static` | object |  |
| **DayOfWeekIndex** `static` | int |  |
| **DayOfWeekIndexObject** `static` | object |  |
| **DayOfWeekObject** `static` *(+3 overloads)* | object |  |
| **DayOfYear** `static` | int |  |
| **DayOfYearObject** `static` | object |  |
| **DaysInMonth** `static` *(+1 overloads)* | long |  |
| **DaysInMonthObject** `static` *(+1 overloads)* | object |  |
| **DaysInYear** `static` *(+1 overloads)* | int |  |
| **DaysInYearObject** `static` | object |  |
| **Distinct** `static` | object |  |
| **DistinctCount** `static` | long |  |
| **DistinctCountIf** `static` | long |  |
| **Div** `static` | decimal? |  |
| **DivObject** `static` | object |  |
| **ExistsCustomFunction** `static` | bool |  |
| **Exp** `static` | double |  |
| **ExpObject** `static` | object |  |
| **FinancialQuarter** `static` | StiQuarter? |  |
| **FinancialQuarterIndex** `static` | int |  |
| **FinancialQuarterIndexObject** `static` | object |  |
| **FinancialQuarterObject** `static` | object |  |
| **First** `static` | object |  |
| **FiscalMonthIdent** `static` | [StiFiscalMonth](../Types/StiFiscalMonth.md) | Returns StiFiscalMonth object which based on DateTime value and from an index or an english name of first month in the year (start from 1). |
| **FiscalMonthIdentObject** `static` | object |  |
| **Floor** `static` | decimal |  |
| **FloorObject** `static` | object |  |
| **Format** `static` | object |  |
| **Frac** `static` | decimal |  |
| **FracObject** `static` | object |  |
| **FromOADate** `static` | DateTime |  |
| **FromOADateObject** `static` | object |  |
| **GetAggregateMeasureFunctions** `static` | IEnumerable<string> |  |
| **GetCommonMeasureFunctions** `static` | IEnumerable<string> |  |
| **GetCustomFunction** `static` | [IStiAppFunction](../../Stimulsoft_Base/IStiAppFunction.md) |  |
| **GetCustomFunctions** `static` | IEnumerable<[IStiAppFunction](../../Stimulsoft_Base/IStiAppFunction.md)> |  |
| **GetDateAggregateMeasureFunctions** `static` | IEnumerable<string> |  |
| **GetDateDimensionFunctions** `static` | IEnumerable<string> |  |
| **GetIso2ConvertedValues** `static` | List<string> |  |
| **GetMapIdents** `static` | List<string> |  |
| **GetMeasureFunctions** `static` | IEnumerable<string> |  |
| **GetSystemVariable** `static` | object |  |
| **GetTimeAggregateMeasureFunctions** `static` | IEnumerable<string> |  |
| **Hour** `static` | int |  |
| **HourObject** `static` | object |  |
| **Image** `static` | object |  |
| **IndexOf** `static` | int |  |
| **Insert** `static` | string |  |
| **InsertObject** `static` | object |  |
| **InvokeCustomFunction** `static` | object |  |
| **IsAggregationFunction** `static` | bool |  |
| **IsDataEqual** `static` | bool |  |
| **IsMeasureFunction** `static` | bool |  |
| **IsValidUrl** `static` | bool |  |
| **Iso2** `static` | string |  |
| **Iso2Object** `static` | object |  |
| **Iso2ToName** `static` | string |  |
| **Iso2ToNameObject** `static` | object |  |
| **Iso3** `static` | string |  |
| **Iso3Object** `static` | object |  |
| **Iso3ToName** `static` | string |  |
| **Iso3ToNameObject** `static` | object |  |
| **Last** `static` | object |  |
| **Left** `static` | string |  |
| **LeftObject** `static` | object |  |
| **Length** `static` | int |  |
| **LengthObject** `static` | object |  |
| **Localize** `static` | string |  |
| **Log** `static` | double |  |
| **LogObject** `static` | object |  |
| **MakeDate** `static` | DateTime |  |
| **MakeDateObject** `static` | object |  |
| **MakeDateTime** `static` | DateTime |  |
| **MakeDateTimeObject** `static` | object |  |
| **MakeTime** `static` | DateTime |  |
| **MakeTimeObject** `static` | object |  |
| **Max** `static` | decimal |  |
| **MaxD** `static` | double |  |
| **MaxDate** `static` | DateTime? |  |
| **MaxI** `static` | long |  |
| **MaxNulls** `static` | decimal? |  |
| **MaxStr** `static` | string |  |
| **MaxTime** `static` | TimeSpan? |  |
| **Median** `static` | decimal |  |
| **MedianD** `static` | double |  |
| **MedianI** `static` | long |  |
| **Min** `static` | decimal |  |
| **MinD** `static` | double |  |
| **MinDate** `static` | DateTime? |  |
| **MinI** `static` | long |  |
| **MinMaxDateString** `static` | string |  |
| **MinNulls** `static` | decimal? |  |
| **MinStr** `static` | string |  |
| **MinTime** `static` | TimeSpan? |  |
| **Minute** `static` | int |  |
| **MinuteObject** `static` | object |  |
| **Mode** `static` | decimal |  |
| **ModeD** `static` | double |  |
| **ModeI** `static` | long |  |
| **Month** `static` | int |  |
| **MonthIdent** `static` | StiMonth? |  |
| **MonthIdentObject** `static` | object |  |
| **MonthName** `static` *(+3 overloads)* | string |  |
| **MonthNameObject** `static` *(+3 overloads)* | object |  |
| **MonthObject** `static` | object |  |
| **NormalizeName** `static` | string |  |
| **NormalizeNameObject** `static` | object |  |
| **Now** `static` | DateTime |  |
| **OptionalSkipNulls** `static` | IEnumerable<object> |  |
| **Quarter** `static` | StiQuarter? |  |
| **QuarterIndex** `static` | int |  |
| **QuarterIndexObject** `static` | object |  |
| **QuarterName** `static` | string |  |
| **QuarterNameObject** `static` | object |  |
| **QuarterObject** `static` | object |  |
| **Remove** `static` | string |  |
| **RemoveObject** `static` | object |  |
| **Replace** `static` | string |  |
| **ReplaceObject** `static` | object |  |
| **Right** `static` | string |  |
| **RightObject** `static` | object |  |
| **Round** `static` | decimal |  |
| **RoundObject** `static` | object |  |
| **RunningTotal** `static` | IEnumerable<object> |  |
| **Second** `static` | int |  |
| **SecondObject** `static` | object |  |
| **Sign** `static` | int |  |
| **SignObject** `static` | object |  |
| **Sin** `static` | double |  |
| **SinObject** `static` | object |  |
| **SkipNulls** `static` | IEnumerable<object> |  |
| **Sqrt** `static` | double |  |
| **SqrtObject** `static` | object |  |
| **StDev** `static` | double |  |
| **StDevP** `static` | double |  |
| **Substring** `static` | string |  |
| **SubstringObject** `static` | object |  |
| **Sum** `static` | decimal |  |
| **SumD** `static` | double |  |
| **SumDIf** `static` | double |  |
| **SumDistinct** `static` | decimal |  |
| **SumDistinctIf** `static` | decimal |  |
| **SumI** `static` | long |  |
| **SumIIf** `static` | long |  |
| **SumIf** `static` | decimal |  |
| **SumNulls** `static` | decimal? |  |
| **SumTime** `static` | TimeSpan |  |
| **SumTimeIf** `static` | TimeSpan |  |
| **Tan** `static` | double |  |
| **TanObject** `static` | object |  |
| **Time** `static` | object |  |
| **ToABC** `static` | string | Converts the number to A B C D representation for numbering of the list. |
| **ToABCNumeric** `static` | string | Converts the number to A B C D representation for numbering of the list. |
| **ToABCRu** `static` | string | Converts the number to А Б В representation for numbering of the list in russian. |
| **ToArabic** `static` *(+1 overloads)* | string | Converts the number to the arabic representation. |
| **ToDataName** `static` | string |  |
| **ToDataNameWithoutRelation** `static` | string |  |
| **ToExpression** `static` *(+1 overloads)* | string |  |
| **ToLowerCase** `static` | string |  |
| **ToLowerCaseObject** `static` | object |  |
| **ToOADate** `static` | double |  |
| **ToOADateObject** `static` | object |  |
| **ToProperCase** `static` | string |  |
| **ToProperCaseObject** `static` | object |  |
| **ToRoman** `static` | string | Converts Arabic numerals to Roman. |
| **ToString** `static` | string |  |
| **ToStringObject** `static` | object |  |
| **ToTitleCase** `static` | string |  |
| **ToTitleCaseObject** `static` | object |  |
| **ToUpperCase** `static` | string |  |
| **ToUpperCaseObject** `static` | object |  |
| **Trim** `static` | string |  |
| **TrimEnd** `static` | string |  |
| **TrimEndObject** `static` | object |  |
| **TrimObject** `static` | object |  |
| **TrimStart** `static` | string |  |
| **TrimStartObject** `static` | object |  |
| **Truncate** `static` | decimal |  |
| **TruncateObject** `static` | object |  |
| **Year** `static` | int |  |
| **YearMonth** `static` | string |  |
| **YearMonthObject** `static` | object |  |
| **YearObject** `static` | object |  |
