---
title: "Funcs Class"
---

## Funcs Class

**Namespace:** `Stimulsoft.Data.Functions`

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
| **GetCustomFunction** `static` | [IStiAppFunction](../../Stimulsoft_Base/root/IStiAppFunction.md) |  |
| **GetCustomFunctions** `static` | IEnumerable<[IStiAppFunction](../../Stimulsoft_Base/root/IStiAppFunction.md)> |  |
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

---

### Method Details

#### Abs `static`

**Abs**(**value**: decimal): decimal

**Parameters**

- **value** (decimal)  

**Returns** decimal


---

#### AbsObject `static`

**AbsObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Acos `static`

**Acos**(**value**: double): double

**Parameters**

- **value** (double)  

**Returns** double


---

#### AcosObject `static`

**AcosObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### AddMonthsObject `static`

**AddMonthsObject**(**date**: object, **months**: int): object

**Parameters**

- **date** (object)  
- **months** (int)  

**Returns** object


---

#### AddYears `static`

**AddYears**(**date**: DateTime, **years**: int): DateTime

**Parameters**

- **date** (DateTime)  
- **years** (int)  

**Returns** DateTime


---

#### AddYearsObject `static`

**AddYearsObject**(**date**: object, **years**: int): object

**Parameters**

- **date** (object)  
- **years** (int)  

**Returns** object


---

#### All `static`

**All**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Asin `static`

**Asin**(**value**: double): double

**Parameters**

- **value** (double)  

**Returns** double


---

#### AsinObject `static`

**AsinObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Atan `static`

**Atan**(**value**: double): double

**Parameters**

- **value** (double)  

**Returns** double


---

#### AtanObject `static`

**AtanObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Avg `static`

**Avg**(**value**: object): decimal

**Parameters**

- **value** (object)  

**Returns** decimal


---

#### AvgD `static`

**AvgD**(**value**: object): double

**Parameters**

- **value** (object)  

**Returns** double


---

#### AvgDate `static`

**AvgDate**(**value**: object): DateTime?

**Parameters**

- **value** (object)  

**Returns** DateTime?


---

#### AvgI `static`

**AvgI**(**value**: object): long

**Parameters**

- **value** (object)  

**Returns** long


---

#### AvgNulls `static`

**AvgNulls**(**value**: object): decimal?

**Parameters**

- **value** (object)  

**Returns** decimal?


---

#### AvgTime `static`

**AvgTime**(**value**: object): TimeSpan?

**Parameters**

- **value** (object)  

**Returns** TimeSpan?


---

#### AvgWeighted `static`

**AvgWeighted**(**value1**: object, **value2**: object): decimal

**Parameters**

- **value1** (object)  
- **value2** (object)  

**Returns** decimal


---

#### Calculate `static`

**Calculate**(**function**: string, **values**: IEnumerable<object>): object

**Parameters**

- **function** (string)  
- **values** (IEnumerable<object>)  

**Returns** object


---

#### Ceiling `static`

**Ceiling**(**value**: decimal): decimal

**Parameters**

- **value** (decimal)  

**Returns** decimal


---

#### CeilingObject `static`

**CeilingObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Clamp `static`

**Clamp**(**value**: decimal, **min**: decimal, **max**: decimal): decimal

**Parameters**

- **value** (decimal)  
- **min** (decimal)  
- **max** (decimal)  

**Returns** decimal


---

#### ClampObject `static`

**ClampObject**(**value**: object, **min**: object, **max**: object): object

**Parameters**

- **value** (object)  
- **min** (object)  
- **max** (object)  

**Returns** object


---

#### Cos `static`

**Cos**(**value**: double): double

**Parameters**

- **value** (double)  

**Returns** double


---

#### CosObject `static`

**CosObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Count `static`

**Count**(**value**: object): long

**Parameters**

- **value** (object)  

**Returns** long


---

#### CountIf `static`

**CountIf**(**value**: object, **condition**: object): long

**Parameters**

- **value** (object)  
- **condition** (object)  

**Returns** long


---

#### DateDiff `static`

**DateDiff**(**date1**: DateTime?, **date2**: DateTime?): TimeSpan?

**Parameters**

- **date1** (DateTime?)  
- **date2** (DateTime?)  

**Returns** TimeSpan?


---

#### DateDiffObject `static`

**DateDiffObject**(**value1**: object, **value2**: object): object

**Parameters**

- **value1** (object)  
- **value2** (object)  

**Returns** object


---

#### DateTime `static`

**DateTime**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Day `static`

**Day**(**dateTime**: DateTime?): int

**Parameters**

- **dateTime** (DateTime?)  

**Returns** int


---

#### DayObject `static`

**DayObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### DayOfWeek `static`

**DayOfWeek**(**date**: DateTime?): string

**Parameters**

- **date** (DateTime?)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime?, **localized**: bool): string

**Parameters**

- **date** (DateTime?)  
- **localized** (bool)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime?, **culture**: string): string

**Parameters**

- **date** (DateTime?)  
- **culture** (string)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime?, **culture**: string, **upperCase**: bool): string

**Parameters**

- **date** (DateTime?)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string


---

#### DayOfWeekIdent `static`

**DayOfWeekIdent**(**dateTime**: DateTime?): DayOfWeek?

**Parameters**

- **dateTime** (DateTime?)  

**Returns** DayOfWeek?


---

#### DayOfWeekIdentObject `static`

**DayOfWeekIdentObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### DayOfWeekIndex `static`

**DayOfWeekIndex**(**dateTime**: DateTime?): int

**Parameters**

- **dateTime** (DateTime?)  

**Returns** int


---

#### DayOfWeekIndexObject `static`

**DayOfWeekIndexObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### DayOfWeekObject `static`

**DayOfWeekObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object

---

**DayOfWeekObject**(**value**: object, **localized**: bool): object

**Parameters**

- **value** (object)  
- **localized** (bool)  

**Returns** object

---

**DayOfWeekObject**(**value**: object, **culture**: string): object

**Parameters**

- **value** (object)  
- **culture** (string)  

**Returns** object

---

**DayOfWeekObject**(**value**: object, **culture**: string, **upperCase**: bool): object

**Parameters**

- **value** (object)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** object


---

#### DayOfYear `static`

**DayOfYear**(**dateTime**: DateTime?): int

**Parameters**

- **dateTime** (DateTime?)  

**Returns** int


---

#### DayOfYearObject `static`

**DayOfYearObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### DaysInMonth `static`

**DaysInMonth**(**year**: long, **month**: long): long

**Parameters**

- **year** (long)  
- **month** (long)  

**Returns** long

---

**DaysInMonth**(**date**: DateTime?): long

**Parameters**

- **date** (DateTime?)  

**Returns** long


---

#### DaysInMonthObject `static`

**DaysInMonthObject**(**value1**: object, **value2**: object): object

**Parameters**

- **value1** (object)  
- **value2** (object)  

**Returns** object

---

**DaysInMonthObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### DaysInYear `static`

**DaysInYear**(**year**: long): int

**Parameters**

- **year** (long)  

**Returns** int

---

**DaysInYear**(**date**: DateTime?): int

**Parameters**

- **date** (DateTime?)  

**Returns** int


---

#### DaysInYearObject `static`

**DaysInYearObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Distinct `static`

**Distinct**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### DistinctCount `static`

**DistinctCount**(**value**: object): long

**Parameters**

- **value** (object)  

**Returns** long


---

#### DistinctCountIf `static`

**DistinctCountIf**(**value**: object, **condition**: object): long

**Parameters**

- **value** (object)  
- **condition** (object)  

**Returns** long


---

#### Div `static`

**Div**(**value1**: decimal, **value2**: decimal, **zeroResult**: decimal?): decimal?

**Parameters**

- **value1** (decimal)  
- **value2** (decimal)  
- **zeroResult** (decimal?)  

**Returns** decimal?


---

#### DivObject `static`

**DivObject**(**value1**: object, **value2**: object, **zeroResult**: object): object

**Parameters**

- **value1** (object)  
- **value2** (object)  
- **zeroResult** (object)  

**Returns** object


---

#### ExistsCustomFunction `static`

**ExistsCustomFunction**(**funcName**: string): bool

**Parameters**

- **funcName** (string)  

**Returns** bool


---

#### Exp `static`

**Exp**(**value**: double): double

**Parameters**

- **value** (double)  

**Returns** double


---

#### ExpObject `static`

**ExpObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### FinancialQuarter `static`

**FinancialQuarter**(**dateTime**: DateTime?): StiQuarter?

**Parameters**

- **dateTime** (DateTime?)  

**Returns** StiQuarter?


---

#### FinancialQuarterIndex `static`

**FinancialQuarterIndex**(**dateTime**: DateTime?): int

**Parameters**

- **dateTime** (DateTime?)  

**Returns** int


---

#### FinancialQuarterIndexObject `static`

**FinancialQuarterIndexObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### FinancialQuarterObject `static`

**FinancialQuarterObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### First `static`

**First**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### FiscalMonthIdent `static`

**FiscalMonthIdent**(**dateTime**: DateTime?, **startMonth**: object): [StiFiscalMonth](../Types/StiFiscalMonth.md)

Returns StiFiscalMonth object which based on DateTime value and from an index or an english name of first month in the year (start from 1).

**Parameters**

- **dateTime** (DateTime?) — A base DateTime value to get month.  
- **startMonth** (object) — An index or an english name of the first month in the year.  

**Returns** [StiFiscalMonth](../Types/StiFiscalMonth.md)


---

#### FiscalMonthIdentObject `static`

**FiscalMonthIdentObject**(**value**: object, **startMonth**: object): object

**Parameters**

- **value** (object)  
- **startMonth** (object)  

**Returns** object


---

#### Floor `static`

**Floor**(**value**: decimal): decimal

**Parameters**

- **value** (decimal)  

**Returns** decimal


---

#### FloorObject `static`

**FloorObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Format `static`

**Format**(**format**: string, **value**: object): object

**Parameters**

- **format** (string)  
- **value** (object)  

**Returns** object


---

#### Frac `static`

**Frac**(**value**: decimal): decimal

**Parameters**

- **value** (decimal)  

**Returns** decimal


---

#### FracObject `static`

**FracObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### FromOADate `static`

**FromOADate**(**value**: double): DateTime

**Parameters**

- **value** (double)  

**Returns** DateTime


---

#### FromOADateObject `static`

**FromOADateObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### GetAggregateMeasureFunctions `static`

**GetAggregateMeasureFunctions**(): IEnumerable<string>

**Returns** IEnumerable<string>


---

#### GetCommonMeasureFunctions `static`

**GetCommonMeasureFunctions**(): IEnumerable<string>

**Returns** IEnumerable<string>


---

#### GetCustomFunction `static`

**GetCustomFunction**(**funcName**: string, **argumentTypes**: IEnumerable<Type>): [IStiAppFunction](../../Stimulsoft_Base/root/IStiAppFunction.md)

**Parameters**

- **funcName** (string)  
- **argumentTypes** (IEnumerable<Type>)  

**Returns** [IStiAppFunction](../../Stimulsoft_Base/root/IStiAppFunction.md)


---

#### GetCustomFunctions `static`

**GetCustomFunctions**(**funcName**: string): IEnumerable<[IStiAppFunction](../../Stimulsoft_Base/root/IStiAppFunction.md)>

**Parameters**

- **funcName** (string)  

**Returns** IEnumerable<[IStiAppFunction](../../Stimulsoft_Base/root/IStiAppFunction.md)>


---

#### GetDateAggregateMeasureFunctions `static`

**GetDateAggregateMeasureFunctions**(): IEnumerable<string>

**Returns** IEnumerable<string>


---

#### GetDateDimensionFunctions `static`

**GetDateDimensionFunctions**(): IEnumerable<string>

**Returns** IEnumerable<string>


---

#### GetIso2ConvertedValues `static`

**GetIso2ConvertedValues**(**name**: string): List<string>

**Parameters**

- **name** (string)  

**Returns** List<string>


---

#### GetMapIdents `static`

**GetMapIdents**(**key**: string): List<string>

**Parameters**

- **key** (string)  

**Returns** List<string>


---

#### GetMeasureFunctions `static`

**GetMeasureFunctions**(): IEnumerable<string>

**Returns** IEnumerable<string>


---

#### GetSystemVariable `static`

**GetSystemVariable**(**variable**: [StiSystemVariableObject](StiSystemVariableObject.md), **line**: int): object

**Parameters**

- **variable** ([StiSystemVariableObject](StiSystemVariableObject.md))  
- **line** (int)  

**Returns** object


---

#### GetTimeAggregateMeasureFunctions `static`

**GetTimeAggregateMeasureFunctions**(): IEnumerable<string>

**Returns** IEnumerable<string>


---

#### Hour `static`

**Hour**(**dateTime**: DateTime?): int

**Parameters**

- **dateTime** (DateTime?)  

**Returns** int


---

#### HourObject `static`

**HourObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Image `static`

**Image**(**value**: object, **width**: int, **height**: int): object

**Parameters**

- **value** (object)  
- **width** (int)  
- **height** (int)  

**Returns** object


---

#### IndexOf `static`

**IndexOf**(**str**: string, **valueToFind**: string): int

**Parameters**

- **str** (string)  
- **valueToFind** (string)  

**Returns** int


---

#### Insert `static`

**Insert**(**str**: string, **startIndex**: int, **subStr**: string): string

**Parameters**

- **str** (string)  
- **startIndex** (int)  
- **subStr** (string)  

**Returns** string


---

#### InsertObject `static`

**InsertObject**(**value**: object, **startIndex**: int, **subStr**: string): object

**Parameters**

- **value** (object)  
- **startIndex** (int)  
- **subStr** (string)  

**Returns** object


---

#### InvokeCustomFunction `static`

**InvokeCustomFunction**(**funcName**: string, **arguments**: IEnumerable<object>): object

**Parameters**

- **funcName** (string)  
- **arguments** (IEnumerable<object>)  

**Returns** object


---

#### IsAggregationFunction `static`

**IsAggregationFunction**(**function**: string): bool

**Parameters**

- **function** (string)  

**Returns** bool


---

#### IsDataEqual `static`

**IsDataEqual**(**dataSource**: [IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md), **dataColumnName**: string, **searchColumnName**: string): bool

**Parameters**

- **dataSource** ([IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md))  
- **dataColumnName** (string)  
- **searchColumnName** (string)  

**Returns** bool


---

#### IsMeasureFunction `static`

**IsMeasureFunction**(**expression**: string): bool

**Parameters**

- **expression** (string)  

**Returns** bool


---

#### IsValidUrl `static`

**IsValidUrl**(**hyperlink**: string): bool

**Parameters**

- **hyperlink** (string)  

**Returns** bool


---

#### Iso2 `static`

**Iso2**(**name**: string, **mapId**: string, **lang**: string): string

**Parameters**

- **name** (string)  
- **mapId** (string)  
- **lang** (string)  

**Returns** string


---

#### Iso2Object `static`

**Iso2Object**(**value**: object, **mapId**: string, **lang**: string): object

**Parameters**

- **value** (object)  
- **mapId** (string)  
- **lang** (string)  

**Returns** object


---

#### Iso2ToName `static`

**Iso2ToName**(**alpha2**: string, **mapId**: string, **lang**: string): string

**Parameters**

- **alpha2** (string)  
- **mapId** (string)  
- **lang** (string)  

**Returns** string


---

#### Iso2ToNameObject `static`

**Iso2ToNameObject**(**value**: object, **mapId**: string, **lang**: string): object

**Parameters**

- **value** (object)  
- **mapId** (string)  
- **lang** (string)  

**Returns** object


---

#### Iso3 `static`

**Iso3**(**name**: string, **mapId**: string, **lang**: string): string

**Parameters**

- **name** (string)  
- **mapId** (string)  
- **lang** (string)  

**Returns** string


---

#### Iso3Object `static`

**Iso3Object**(**value**: object, **mapId**: string, **lang**: string): object

**Parameters**

- **value** (object)  
- **mapId** (string)  
- **lang** (string)  

**Returns** object


---

#### Iso3ToName `static`

**Iso3ToName**(**alpha3**: string, **mapId**: string, **lang**: string): string

**Parameters**

- **alpha3** (string)  
- **mapId** (string)  
- **lang** (string)  

**Returns** string


---

#### Iso3ToNameObject `static`

**Iso3ToNameObject**(**value**: object, **mapId**: string, **lang**: string): object

**Parameters**

- **value** (object)  
- **mapId** (string)  
- **lang** (string)  

**Returns** object


---

#### Last `static`

**Last**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Left `static`

**Left**(**str**: string, **length**: int): string

**Parameters**

- **str** (string)  
- **length** (int)  

**Returns** string


---

#### LeftObject `static`

**LeftObject**(**value**: object, **length**: int): object

**Parameters**

- **value** (object)  
- **length** (int)  

**Returns** object


---

#### Length `static`

**Length**(**str**: string): int

**Parameters**

- **str** (string)  

**Returns** int


---

#### LengthObject `static`

**LengthObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Localize `static`

**Localize**(**func**: string): string

**Parameters**

- **func** (string)  

**Returns** string


---

#### Log `static`

**Log**(**value**: double): double

**Parameters**

- **value** (double)  

**Returns** double


---

#### LogObject `static`

**LogObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### MakeDate `static`

**MakeDate**(**year**: int, **month**: int, **day**: int): DateTime

**Parameters**

- **year** (int)  
- **month** (int)  
- **day** (int)  

**Returns** DateTime


---

#### MakeDateObject `static`

**MakeDateObject**(**year**: object, **month**: object, **day**: object): object

**Parameters**

- **year** (object)  
- **month** (object)  
- **day** (object)  

**Returns** object


---

#### MakeDateTime `static`

**MakeDateTime**(**year**: int, **month**: int, **day**: int, **hour**: int, **minute**: int, **second**: int): DateTime

**Parameters**

- **year** (int)  
- **month** (int)  
- **day** (int)  
- **hour** (int)  
- **minute** (int)  
- **second** (int)  

**Returns** DateTime


---

#### MakeDateTimeObject `static`

**MakeDateTimeObject**(**year**: object, **month**: object, **day**: object, **hour**: object, **minute**: object, **second**: object): object

**Parameters**

- **year** (object)  
- **month** (object)  
- **day** (object)  
- **hour** (object)  
- **minute** (object)  
- **second** (object)  

**Returns** object


---

#### MakeTime `static`

**MakeTime**(**hour**: int, **minute**: int, **second**: int): DateTime

**Parameters**

- **hour** (int)  
- **minute** (int)  
- **second** (int)  

**Returns** DateTime


---

#### MakeTimeObject `static`

**MakeTimeObject**(**hour**: object, **minute**: object, **second**: object): object

**Parameters**

- **hour** (object)  
- **minute** (object)  
- **second** (object)  

**Returns** object


---

#### Max `static`

**Max**(**value**: object): decimal

**Parameters**

- **value** (object)  

**Returns** decimal


---

#### MaxD `static`

**MaxD**(**value**: object): double

**Parameters**

- **value** (object)  

**Returns** double


---

#### MaxDate `static`

**MaxDate**(**value**: object): DateTime?

**Parameters**

- **value** (object)  

**Returns** DateTime?


---

#### MaxI `static`

**MaxI**(**value**: object): long

**Parameters**

- **value** (object)  

**Returns** long


---

#### MaxNulls `static`

**MaxNulls**(**value**: object): decimal?

**Parameters**

- **value** (object)  

**Returns** decimal?


---

#### MaxStr `static`

**MaxStr**(**value**: object): string

**Parameters**

- **value** (object)  

**Returns** string


---

#### MaxTime `static`

**MaxTime**(**value**: object): TimeSpan?

**Parameters**

- **value** (object)  

**Returns** TimeSpan?


---

#### Median `static`

**Median**(**value**: object): decimal

**Parameters**

- **value** (object)  

**Returns** decimal


---

#### MedianD `static`

**MedianD**(**value**: object): double

**Parameters**

- **value** (object)  

**Returns** double


---

#### MedianI `static`

**MedianI**(**value**: object): long

**Parameters**

- **value** (object)  

**Returns** long


---

#### Min `static`

**Min**(**value**: object): decimal

**Parameters**

- **value** (object)  

**Returns** decimal


---

#### MinD `static`

**MinD**(**value**: object): double

**Parameters**

- **value** (object)  

**Returns** double


---

#### MinDate `static`

**MinDate**(**value**: object): DateTime?

**Parameters**

- **value** (object)  

**Returns** DateTime?


---

#### MinI `static`

**MinI**(**value**: object): long

**Parameters**

- **value** (object)  

**Returns** long


---

#### MinMaxDateString `static`

**MinMaxDateString**(**value**: object): string

**Parameters**

- **value** (object)  

**Returns** string


---

#### MinNulls `static`

**MinNulls**(**value**: object): decimal?

**Parameters**

- **value** (object)  

**Returns** decimal?


---

#### MinStr `static`

**MinStr**(**value**: object): string

**Parameters**

- **value** (object)  

**Returns** string


---

#### MinTime `static`

**MinTime**(**value**: object): TimeSpan?

**Parameters**

- **value** (object)  

**Returns** TimeSpan?


---

#### Minute `static`

**Minute**(**dateTime**: DateTime?): int

**Parameters**

- **dateTime** (DateTime?)  

**Returns** int


---

#### MinuteObject `static`

**MinuteObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Mode `static`

**Mode**(**value**: object): decimal

**Parameters**

- **value** (object)  

**Returns** decimal


---

#### ModeD `static`

**ModeD**(**value**: object): double

**Parameters**

- **value** (object)  

**Returns** double


---

#### ModeI `static`

**ModeI**(**value**: object): long

**Parameters**

- **value** (object)  

**Returns** long


---

#### Month `static`

**Month**(**dateTime**: DateTime?): int

**Parameters**

- **dateTime** (DateTime?)  

**Returns** int


---

#### MonthIdent `static`

**MonthIdent**(**dateTime**: DateTime?): StiMonth?

**Parameters**

- **dateTime** (DateTime?)  

**Returns** StiMonth?


---

#### MonthIdentObject `static`

**MonthIdentObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### MonthName `static`

**MonthName**(**date**: DateTime?): string

**Parameters**

- **date** (DateTime?)  

**Returns** string

---

**MonthName**(**date**: DateTime?, **localized**: bool): string

**Parameters**

- **date** (DateTime?)  
- **localized** (bool)  

**Returns** string

---

**MonthName**(**date**: DateTime?, **culture**: string): string

**Parameters**

- **date** (DateTime?)  
- **culture** (string)  

**Returns** string

---

**MonthName**(**date**: DateTime?, **culture**: string, **upperCase**: bool): string

**Parameters**

- **date** (DateTime?)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string


---

#### MonthNameObject `static`

**MonthNameObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object

---

**MonthNameObject**(**value**: object, **localized**: bool): object

**Parameters**

- **value** (object)  
- **localized** (bool)  

**Returns** object

---

**MonthNameObject**(**value**: object, **culture**: string): object

**Parameters**

- **value** (object)  
- **culture** (string)  

**Returns** object

---

**MonthNameObject**(**value**: object, **culture**: string, **upperCase**: bool): object

**Parameters**

- **value** (object)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** object


---

#### MonthObject `static`

**MonthObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### NormalizeName `static`

**NormalizeName**(**alpha3**: string, **mapId**: string, **lang**: string): string

**Parameters**

- **alpha3** (string)  
- **mapId** (string)  
- **lang** (string)  

**Returns** string


---

#### NormalizeNameObject `static`

**NormalizeNameObject**(**value**: object, **mapId**: string, **lang**: string): object

**Parameters**

- **value** (object)  
- **mapId** (string)  
- **lang** (string)  

**Returns** object


---

#### Now `static`

**Now**(): DateTime

**Returns** DateTime


---

#### OptionalSkipNulls `static`

**OptionalSkipNulls**(**values**: IEnumerable<object>): IEnumerable<object>

**Parameters**

- **values** (IEnumerable<object>)  

**Returns** IEnumerable<object>


---

#### Quarter `static`

**Quarter**(**dateTime**: DateTime?): StiQuarter?

**Parameters**

- **dateTime** (DateTime?)  

**Returns** StiQuarter?


---

#### QuarterIndex `static`

**QuarterIndex**(**dateTime**: DateTime?): int

**Parameters**

- **dateTime** (DateTime?)  

**Returns** int


---

#### QuarterIndexObject `static`

**QuarterIndexObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### QuarterName `static`

**QuarterName**(**dateTime**: DateTime?, **localized**: bool): string

**Parameters**

- **dateTime** (DateTime?)  
- **localized** (bool)  

**Returns** string


---

#### QuarterNameObject `static`

**QuarterNameObject**(**value**: object, **localized**: bool): object

**Parameters**

- **value** (object)  
- **localized** (bool)  

**Returns** object


---

#### QuarterObject `static`

**QuarterObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Remove `static`

**Remove**(**str**: string, **startIndex**: int, **count**: int): string

**Parameters**

- **str** (string)  
- **startIndex** (int)  
- **count** (int)  

**Returns** string


---

#### RemoveObject `static`

**RemoveObject**(**value**: object, **startIndex**: int, **count**: int): object

**Parameters**

- **value** (object)  
- **startIndex** (int)  
- **count** (int)  

**Returns** object


---

#### Replace `static`

**Replace**(**str**: string, **oldValue**: string, **newValue**: string): string

**Parameters**

- **str** (string)  
- **oldValue** (string)  
- **newValue** (string)  

**Returns** string


---

#### ReplaceObject `static`

**ReplaceObject**(**value**: object, **oldValue**: string, **newValue**: string): object

**Parameters**

- **value** (object)  
- **oldValue** (string)  
- **newValue** (string)  

**Returns** object


---

#### Right `static`

**Right**(**str**: string, **length**: int): string

**Parameters**

- **str** (string)  
- **length** (int)  

**Returns** string


---

#### RightObject `static`

**RightObject**(**value**: object, **length**: int): object

**Parameters**

- **value** (object)  
- **length** (int)  

**Returns** object


---

#### Round `static`

**Round**(**value**: decimal, **decimals**: int): decimal

**Parameters**

- **value** (decimal)  
- **decimals** (int)  

**Returns** decimal


---

#### RoundObject `static`

**RoundObject**(**value**: object, **decimals**: int): object

**Parameters**

- **value** (object)  
- **decimals** (int)  

**Returns** object


---

#### RunningTotal `static`

**RunningTotal**(**values**: IEnumerable<object>): IEnumerable<object>

**Parameters**

- **values** (IEnumerable<object>)  

**Returns** IEnumerable<object>


---

#### Second `static`

**Second**(**dateTime**: DateTime?): int

**Parameters**

- **dateTime** (DateTime?)  

**Returns** int


---

#### SecondObject `static`

**SecondObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Sign `static`

**Sign**(**value**: decimal): int

**Parameters**

- **value** (decimal)  

**Returns** int


---

#### SignObject `static`

**SignObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Sin `static`

**Sin**(**value**: double): double

**Parameters**

- **value** (double)  

**Returns** double


---

#### SinObject `static`

**SinObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### SkipNulls `static`

**SkipNulls**(**values**: IEnumerable<object>): IEnumerable<object>

**Parameters**

- **values** (IEnumerable<object>)  

**Returns** IEnumerable<object>


---

#### Sqrt `static`

**Sqrt**(**value**: double): double

**Parameters**

- **value** (double)  

**Returns** double


---

#### SqrtObject `static`

**SqrtObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### StDev `static`

**StDev**(**value**: object): double

**Parameters**

- **value** (object)  

**Returns** double


---

#### StDevP `static`

**StDevP**(**value**: object): double

**Parameters**

- **value** (object)  

**Returns** double


---

#### Substring `static`

**Substring**(**str**: string, **startIndex**: int, **length**: int): string

**Parameters**

- **str** (string)  
- **startIndex** (int)  
- **length** (int)  

**Returns** string


---

#### SubstringObject `static`

**SubstringObject**(**value**: object, **startIndex**: int, **length**: int): object

**Parameters**

- **value** (object)  
- **startIndex** (int)  
- **length** (int)  

**Returns** object


---

#### Sum `static`

**Sum**(**value**: object): decimal

**Parameters**

- **value** (object)  

**Returns** decimal


---

#### SumD `static`

**SumD**(**value**: object): double

**Parameters**

- **value** (object)  

**Returns** double


---

#### SumDIf `static`

**SumDIf**(**value**: object, **condition**: object): double

**Parameters**

- **value** (object)  
- **condition** (object)  

**Returns** double


---

#### SumDistinct `static`

**SumDistinct**(**value**: object): decimal

**Parameters**

- **value** (object)  

**Returns** decimal


---

#### SumDistinctIf `static`

**SumDistinctIf**(**value**: object, **condition**: object): decimal

**Parameters**

- **value** (object)  
- **condition** (object)  

**Returns** decimal


---

#### SumI `static`

**SumI**(**value**: object): long

**Parameters**

- **value** (object)  

**Returns** long


---

#### SumIIf `static`

**SumIIf**(**value**: object, **condition**: object): long

**Parameters**

- **value** (object)  
- **condition** (object)  

**Returns** long


---

#### SumIf `static`

**SumIf**(**value**: object, **condition**: object): decimal

**Parameters**

- **value** (object)  
- **condition** (object)  

**Returns** decimal


---

#### SumNulls `static`

**SumNulls**(**value**: object): decimal?

**Parameters**

- **value** (object)  

**Returns** decimal?


---

#### SumTime `static`

**SumTime**(**value**: object): TimeSpan

**Parameters**

- **value** (object)  

**Returns** TimeSpan


---

#### SumTimeIf `static`

**SumTimeIf**(**value**: object, **condition**: object): TimeSpan

**Parameters**

- **value** (object)  
- **condition** (object)  

**Returns** TimeSpan


---

#### Tan `static`

**Tan**(**value**: double): double

**Parameters**

- **value** (double)  

**Returns** double


---

#### TanObject `static`

**TanObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Time `static`

**Time**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### ToABC `static`

**ToABC**(**value**: int): string

Converts the number to A B C D representation for numbering of the list.

**Parameters**

- **value** (int) — A number for converting into the A B C representation.  

**Returns** string — String representation of the value in A B C D format.


---

#### ToABCNumeric `static`

**ToABCNumeric**(**value**: int): string

Converts the number to A B C D representation for numbering of the list.

**Parameters**

- **value** (int) — A number for converting into the A B C representation.  

**Returns** string — String representation of the value in A B C D format.


---

#### ToABCRu `static`

**ToABCRu**(**value**: int): string

Converts the number to А Б В representation for numbering of the list in russian.

**Parameters**

- **value** (int) — A number for converting into the А Б В representation.  

**Returns** string — String representation of the value in А Б В format.


---

#### ToArabic `static`

**ToArabic**(**value**: int, **useEasternDigits**: bool): string

Converts the number to the arabic representation.

**Parameters**

- **value** (int) — A number for converting into the arabic representation.  
- **useEasternDigits** (bool) — Use eastern or standard arabic digits.  

**Returns** string — String representation of the value with arabic digits.

---

**ToArabic**(**value**: string, **useEasternDigits**: bool): string

Converts all digits in the string to the arabic representation.

**Parameters**

- **value** (string) — A string for converting into the arabic representation.  
- **useEasternDigits** (bool) — Use eastern or standard arabic digits.  

**Returns** string — String with arabic digits.


---

#### ToDataName `static`

**ToDataName**(**name**: string): string

**Parameters**

- **name** (string)  

**Returns** string


---

#### ToDataNameWithoutRelation `static`

**ToDataNameWithoutRelation**(**name**: string, **dataSources**: IEnumerable<[IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md)>): string

**Parameters**

- **name** (string)  
- **dataSources** (IEnumerable<[IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md)>)  

**Returns** string


---

#### ToExpression `static`

**ToExpression**(**name**: string): string

**Parameters**

- **name** (string)  

**Returns** string

---

**ToExpression**(**sourceName**: string, **columnName**: string): string

**Parameters**

- **sourceName** (string)  
- **columnName** (string)  

**Returns** string


---

#### ToLowerCase `static`

**ToLowerCase**(**str**: string): string

**Parameters**

- **str** (string)  

**Returns** string


---

#### ToLowerCaseObject `static`

**ToLowerCaseObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### ToOADate `static`

**ToOADate**(**value**: DateTime): double

**Parameters**

- **value** (DateTime)  

**Returns** double


---

#### ToOADateObject `static`

**ToOADateObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### ToProperCase `static`

**ToProperCase**(**str**: string): string

**Parameters**

- **str** (string)  

**Returns** string


---

#### ToProperCaseObject `static`

**ToProperCaseObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### ToRoman `static`

**ToRoman**(**value**: int): string

Converts Arabic numerals to Roman.

**Parameters**

- **value** (int) — Arabic numerals for converting to the Roman format.  

**Returns** string — Returns Arabics numerals in Roman.


---

#### ToString `static`

**ToString**(**value**: object): string

**Parameters**

- **value** (object)  

**Returns** string


---

#### ToStringObject `static`

**ToStringObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### ToTitleCase `static`

**ToTitleCase**(**str**: string): string

**Parameters**

- **str** (string)  

**Returns** string


---

#### ToTitleCaseObject `static`

**ToTitleCaseObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### ToUpperCase `static`

**ToUpperCase**(**str**: string): string

**Parameters**

- **str** (string)  

**Returns** string


---

#### ToUpperCaseObject `static`

**ToUpperCaseObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Trim `static`

**Trim**(**str**: string): string

**Parameters**

- **str** (string)  

**Returns** string


---

#### TrimEnd `static`

**TrimEnd**(**str**: string): string

**Parameters**

- **str** (string)  

**Returns** string


---

#### TrimEndObject `static`

**TrimEndObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### TrimObject `static`

**TrimObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### TrimStart `static`

**TrimStart**(**str**: string): string

**Parameters**

- **str** (string)  

**Returns** string


---

#### TrimStartObject `static`

**TrimStartObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Truncate `static`

**Truncate**(**value**: decimal): decimal

**Parameters**

- **value** (decimal)  

**Returns** decimal


---

#### TruncateObject `static`

**TruncateObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### Year `static`

**Year**(**dateTime**: DateTime?): int

**Parameters**

- **dateTime** (DateTime?)  

**Returns** int


---

#### YearMonth `static`

**YearMonth**(**dateTime**: DateTime?): string

**Parameters**

- **dateTime** (DateTime?)  

**Returns** string


---

#### YearMonthObject `static`

**YearMonthObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### YearObject `static`

**YearObject**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object

