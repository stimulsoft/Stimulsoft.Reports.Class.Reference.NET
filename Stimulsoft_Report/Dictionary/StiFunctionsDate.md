---
title: "StiFunctionsDate Class"
---

## StiFunctionsDate Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DateDiff** `static` *(+3 overloads)* | TimeSpan |  |
| **DateSerial** `static` *(+1 overloads)* | DateTime |  |
| **Day** `static` *(+3 overloads)* | long |  |
| **DayOfWeek** `static` *(+15 overloads)* | string |  |
| **DayOfYear** `static` *(+3 overloads)* | long |  |
| **DaysInMonth** `static` *(+4 overloads)* | long |  |
| **DaysInYear** `static` *(+4 overloads)* | long |  |
| **FromOADate** `static` | DateTime |  |
| **Hour** `static` *(+3 overloads)* | long |  |
| **Minute** `static` *(+3 overloads)* | long |  |
| **Month** `static` *(+3 overloads)* | long |  |
| **MonthIdent** `static` | object |  |
| **MonthName** `static` *(+7 overloads)* | string |  |
| **Second** `static` *(+3 overloads)* | long |  |
| **TimeSerial** `static` | TimeSpan |  |
| **ToOADate** `static` | double |  |
| **WeekOfMonth** `static` *(+5 overloads)* | long |  |
| **WeekOfYear** `static` *(+5 overloads)* | long |  |
| **Year** `static` *(+3 overloads)* | long |  |

---

### Method Details

#### DateDiff `static`

**DateDiff**(**date1**: DateTime, **date2**: DateTime): TimeSpan

**Parameters**

- **date1** (DateTime)  
- **date2** (DateTime)  

**Returns** TimeSpan

---

**DateDiff**(**date1**: DateTimeOffset, **date2**: DateTimeOffset): TimeSpan

**Parameters**

- **date1** (DateTimeOffset)  
- **date2** (DateTimeOffset)  

**Returns** TimeSpan

---

**DateDiff**(**date1**: DateTime?, **date2**: DateTime?): TimeSpan?

**Parameters**

- **date1** (DateTime?)  
- **date2** (DateTime?)  

**Returns** TimeSpan?

---

**DateDiff**(**date1**: DateTimeOffset?, **date2**: DateTimeOffset?): TimeSpan?

**Parameters**

- **date1** (DateTimeOffset?)  
- **date2** (DateTimeOffset?)  

**Returns** TimeSpan?


---

#### DateSerial `static`

**DateSerial**(**year**: long, **month**: long, **day**: long): DateTime

**Parameters**

- **year** (long)  
- **month** (long)  
- **day** (long)  

**Returns** DateTime

---

**DateSerial**(**ticks**: long): DateTime

**Parameters**

- **ticks** (long)  

**Returns** DateTime


---

#### Day `static`

**Day**(**date**: DateTime): long

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**Day**(**date**: DateTimeOffset): long

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**Day**(**date**: DateTime?): long

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**Day**(**date**: DateTimeOffset?): long

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long


---

#### DayOfWeek `static`

**DayOfWeek**(**date**: DateTime): string

**Parameters**

- **date** (DateTime)  

**Returns** string

---

**DayOfWeek**(**date**: DateTimeOffset): string

**Parameters**

- **date** (DateTimeOffset)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime?): string

**Parameters**

- **date** (DateTime?)  

**Returns** string

---

**DayOfWeek**(**date**: DateTimeOffset?): string

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime, **localized**: bool): string

**Parameters**

- **date** (DateTime)  
- **localized** (bool)  

**Returns** string

---

**DayOfWeek**(**date**: DateTimeOffset, **localized**: bool): string

**Parameters**

- **date** (DateTimeOffset)  
- **localized** (bool)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime?, **localized**: bool): string

**Parameters**

- **date** (DateTime?)  
- **localized** (bool)  

**Returns** string

---

**DayOfWeek**(**date**: DateTimeOffset?, **localized**: bool): string

**Parameters**

- **date** (DateTimeOffset?)  
- **localized** (bool)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime, **culture**: string): string

**Parameters**

- **date** (DateTime)  
- **culture** (string)  

**Returns** string

---

**DayOfWeek**(**date**: DateTimeOffset, **culture**: string): string

**Parameters**

- **date** (DateTimeOffset)  
- **culture** (string)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime?, **culture**: string): string

**Parameters**

- **date** (DateTime?)  
- **culture** (string)  

**Returns** string

---

**DayOfWeek**(**date**: DateTimeOffset?, **culture**: string): string

**Parameters**

- **date** (DateTimeOffset?)  
- **culture** (string)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime, **culture**: string, **upperCase**: bool): string

**Parameters**

- **date** (DateTime)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string

---

**DayOfWeek**(**date**: DateTimeOffset, **culture**: string, **upperCase**: bool): string

**Parameters**

- **date** (DateTimeOffset)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime?, **culture**: string, **upperCase**: bool): string

**Parameters**

- **date** (DateTime?)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string

---

**DayOfWeek**(**date**: DateTimeOffset?, **culture**: string, **upperCase**: bool): string

**Parameters**

- **date** (DateTimeOffset?)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string


---

#### DayOfYear `static`

**DayOfYear**(**date**: DateTime): long

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**DayOfYear**(**date**: DateTimeOffset): long

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**DayOfYear**(**date**: DateTime?): long

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**DayOfYear**(**date**: DateTimeOffset?): long

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long


---

#### DaysInMonth `static`

**DaysInMonth**(**year**: long, **month**: long): long

**Parameters**

- **year** (long)  
- **month** (long)  

**Returns** long

---

**DaysInMonth**(**date**: DateTime): long

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**DaysInMonth**(**date**: DateTimeOffset): long

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**DaysInMonth**(**date**: DateTime?): long

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**DaysInMonth**(**date**: DateTimeOffset?): long

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long


---

#### DaysInYear `static`

**DaysInYear**(**year**: long): long

**Parameters**

- **year** (long)  

**Returns** long

---

**DaysInYear**(**date**: DateTime): long

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**DaysInYear**(**date**: DateTimeOffset): long

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**DaysInYear**(**date**: DateTime?): long

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**DaysInYear**(**date**: DateTimeOffset?): long

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long


---

#### FromOADate `static`

**FromOADate**(**value**: double): DateTime

**Parameters**

- **value** (double)  

**Returns** DateTime


---

#### Hour `static`

**Hour**(**date**: DateTime): long

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**Hour**(**date**: DateTimeOffset): long

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**Hour**(**date**: DateTime?): long

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**Hour**(**date**: DateTimeOffset?): long

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long


---

#### Minute `static`

**Minute**(**date**: DateTime): long

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**Minute**(**date**: DateTimeOffset): long

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**Minute**(**date**: DateTime?): long

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**Minute**(**date**: DateTimeOffset?): long

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long


---

#### Month `static`

**Month**(**date**: DateTime): long

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**Month**(**date**: DateTimeOffset): long

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**Month**(**date**: DateTime?): long

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**Month**(**date**: DateTimeOffset?): long

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long


---

#### MonthIdent `static`

**MonthIdent**(**value**: object): object

**Parameters**

- **value** (object)  

**Returns** object


---

#### MonthName `static`

**MonthName**(**date**: DateTime): string

**Parameters**

- **date** (DateTime)  

**Returns** string

---

**MonthName**(**date**: DateTime?): string

**Parameters**

- **date** (DateTime?)  

**Returns** string

---

**MonthName**(**date**: DateTime, **localized**: bool): string

**Parameters**

- **date** (DateTime)  
- **localized** (bool)  

**Returns** string

---

**MonthName**(**date**: DateTime?, **localized**: bool): string

**Parameters**

- **date** (DateTime?)  
- **localized** (bool)  

**Returns** string

---

**MonthName**(**date**: DateTime, **culture**: string): string

**Parameters**

- **date** (DateTime)  
- **culture** (string)  

**Returns** string

---

**MonthName**(**date**: DateTime?, **culture**: string): string

**Parameters**

- **date** (DateTime?)  
- **culture** (string)  

**Returns** string

---

**MonthName**(**date**: DateTime, **culture**: string, **upperCase**: bool): string

**Parameters**

- **date** (DateTime)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string

---

**MonthName**(**date**: DateTime?, **culture**: string, **upperCase**: bool): string

**Parameters**

- **date** (DateTime?)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string


---

#### Second `static`

**Second**(**date**: DateTime): long

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**Second**(**date**: DateTimeOffset): long

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**Second**(**date**: DateTime?): long

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**Second**(**date**: DateTimeOffset?): long

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long


---

#### TimeSerial `static`

**TimeSerial**(**hours**: long, **minutes**: long, **seconds**: long): TimeSpan

**Parameters**

- **hours** (long)  
- **minutes** (long)  
- **seconds** (long)  

**Returns** TimeSpan


---

#### ToOADate `static`

**ToOADate**(**value**: DateTime): double

**Parameters**

- **value** (DateTime)  

**Returns** double


---

#### WeekOfMonth `static`

**WeekOfMonth**(**date**: DateTime): long

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**WeekOfMonth**(**date**: DateTime?): long

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**WeekOfMonth**(**date**: DateTime, **firstDayOfWeek**: DayOfWeek): long

**Parameters**

- **date** (DateTime)  
- **firstDayOfWeek** (DayOfWeek)  

**Returns** long

---

**WeekOfMonth**(**date**: DateTime?, **firstDayOfWeek**: DayOfWeek): long

**Parameters**

- **date** (DateTime?)  
- **firstDayOfWeek** (DayOfWeek)  

**Returns** long

---

**WeekOfMonth**(**date**: DateTime, **firstDayOfWeek**: DayOfWeek, **calendarWeekRule**: CalendarWeekRule): long

**Parameters**

- **date** (DateTime)  
- **firstDayOfWeek** (DayOfWeek)  
- **calendarWeekRule** (CalendarWeekRule)  

**Returns** long

---

**WeekOfMonth**(**date**: DateTime?, **firstDayOfWeek**: DayOfWeek, **calendarWeekRule**: CalendarWeekRule): long

**Parameters**

- **date** (DateTime?)  
- **firstDayOfWeek** (DayOfWeek)  
- **calendarWeekRule** (CalendarWeekRule)  

**Returns** long


---

#### WeekOfYear `static`

**WeekOfYear**(**date**: DateTime): long

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**WeekOfYear**(**date**: DateTime?): long

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**WeekOfYear**(**date**: DateTime, **firstDayOfWeek**: DayOfWeek): long

**Parameters**

- **date** (DateTime)  
- **firstDayOfWeek** (DayOfWeek)  

**Returns** long

---

**WeekOfYear**(**date**: DateTime?, **firstDayOfWeek**: DayOfWeek): long

**Parameters**

- **date** (DateTime?)  
- **firstDayOfWeek** (DayOfWeek)  

**Returns** long

---

**WeekOfYear**(**date**: DateTime, **firstDayOfWeek**: DayOfWeek, **calendarWeekRule**: CalendarWeekRule): long

**Parameters**

- **date** (DateTime)  
- **firstDayOfWeek** (DayOfWeek)  
- **calendarWeekRule** (CalendarWeekRule)  

**Returns** long

---

**WeekOfYear**(**date**: DateTime?, **firstDayOfWeek**: DayOfWeek, **calendarWeekRule**: CalendarWeekRule): long

**Parameters**

- **date** (DateTime?)  
- **firstDayOfWeek** (DayOfWeek)  
- **calendarWeekRule** (CalendarWeekRule)  

**Returns** long


---

#### Year `static`

**Year**(**date**: DateTime): long

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**Year**(**date**: DateTimeOffset): long

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**Year**(**date**: DateTime?): long

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**Year**(**date**: DateTimeOffset?): long

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long

