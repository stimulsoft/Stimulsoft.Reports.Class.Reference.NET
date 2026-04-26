---
title: "StiFunctionsDateTime Class"
---

## StiFunctionsDateTime Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddDays** `static` | DateTime | Returns a new DateTime that adds the specified number of days to the value of this instance. |
| **AddHours** `static` | DateTime | Returns a new DateTime that adds the specified number of hours to the value of this instance. |
| **AddMilliseconds** `static` | DateTime | Returns a new DateTime that adds the specified number of milliseconds to the value of this instance. |
| **AddMinutes** `static` | DateTime | Returns a new DateTime that adds the specified number of minutes to the value of this instance. |
| **AddMonths** `static` | DateTime | Returns a new DateTime that adds the specified number of months to the value of this instance. |
| **AddSeconds** `static` | DateTime | Returns a new DateTime that adds the specified number of seconds to the value of this instance. |
| **AddYears** `static` | DateTime | Returns a new DateTime that adds the specified number of years to the value of this instance. |
| **DateDiff** `static` *(+3 overloads)* | TimeSpan | Returns a number of time intervals between two specified dates. |
| **DateSerial** `static` *(+1 overloads)* | DateTime | Returns the DateTime value for the specified year, month, and day. |
| **Day** `static` *(+3 overloads)* | long | Returns the day from a date and returns it as a integer value. |
| **DayOfWeek** `static` *(+15 overloads)* | string | Returns the day of the week. |
| **DayOfYear** `static` *(+3 overloads)* | long | Returns the day of the year. |
| **DaysInMonth** `static` *(+4 overloads)* | long | Returns the number of days in the specified month and year. |
| **DaysInYear** `static` *(+4 overloads)* | long | Returns the number of days in the specified year. |
| **FromOADate** `static` | DateTime | Returns a DateTime equivalent to the specified OLE Automation Date. |
| **Hour** `static` *(+3 overloads)* | long | Returns the hour portion from a date and returns it as a integer value. |
| **LocalTimeToUtc** `static` | DateTime | Converts a local DateTime to UTC. Unspecified kinds are treated as Local. |
| **Minute** `static` *(+3 overloads)* | long | Returns the minutes portion from a date and returns it as a integer value. |
| **Month** `static` *(+3 overloads)* | long | Returns the month from a date and returns it as an integer value. |
| **MonthIdent** `static` | object | Returns the month identificator from the specified date-time value. |
| **MonthName** `static` *(+7 overloads)* | string | Returns the name of the month. |
| **Second** `static` *(+3 overloads)* | long | Returns the seconds portion from a date and returns it as a integer value. |
| **TimeSerial** `static` | TimeSpan | Returns the TimeValue value for a specified number of hours, minutes, and seconds. |
| **ToJapaneseDateString** `static` *(+1 overloads)* | string |  |
| **ToOADate** `static` | double | Returns the equivalent OLE Automation date of specified datetime. |
| **UtcToLocalTime** `static` | DateTime | Converts a UTC DateTime to the system local time (DateTime.Kind -> Local). |
| **WeekOfMonth** `static` *(+5 overloads)* | long | Returns the week of the month that includes the date in the specified DateTime value. |
| **WeekOfYear** `static` *(+5 overloads)* | long | Returns the week of the year that includes the date in the specified DateTime value. |
| **Year** `static` *(+3 overloads)* | long | Returns the year from a date and returns it as a integer value. |

---

### Method Details

#### AddDays `static`

**AddDays**(**date**: DateTime, **days**: double): DateTime

Returns a new DateTime that adds the specified number of days to the value of this instance.

**Parameters**

- **date** (DateTime)  
- **days** (double)  

**Returns** DateTime


---

#### AddHours `static`

**AddHours**(**date**: DateTime, **hours**: double): DateTime

Returns a new DateTime that adds the specified number of hours to the value of this instance.

**Parameters**

- **date** (DateTime)  
- **hours** (double)  

**Returns** DateTime


---

#### AddMilliseconds `static`

**AddMilliseconds**(**date**: DateTime, **milliseconds**: double): DateTime

Returns a new DateTime that adds the specified number of milliseconds to the value of this instance.

**Parameters**

- **date** (DateTime)  
- **milliseconds** (double)  

**Returns** DateTime


---

#### AddMinutes `static`

**AddMinutes**(**date**: DateTime, **minutes**: double): DateTime

Returns a new DateTime that adds the specified number of minutes to the value of this instance.

**Parameters**

- **date** (DateTime)  
- **minutes** (double)  

**Returns** DateTime


---

#### AddMonths `static`

**AddMonths**(**date**: DateTime, **months**: int): DateTime

Returns a new DateTime that adds the specified number of months to the value of this instance.

**Parameters**

- **date** (DateTime)  
- **months** (int)  

**Returns** DateTime


---

#### AddSeconds `static`

**AddSeconds**(**date**: DateTime, **seconds**: double): DateTime

Returns a new DateTime that adds the specified number of seconds to the value of this instance.

**Parameters**

- **date** (DateTime)  
- **seconds** (double)  

**Returns** DateTime


---

#### AddYears `static`

**AddYears**(**date**: DateTime, **years**: int): DateTime

Returns a new DateTime that adds the specified number of years to the value of this instance.

**Parameters**

- **date** (DateTime)  
- **years** (int)  

**Returns** DateTime


---

#### DateDiff `static`

**DateDiff**(**date1**: DateTime, **date2**: DateTime): TimeSpan

Returns a number of time intervals between two specified dates.

**Parameters**

- **date1** (DateTime)  
- **date2** (DateTime)  

**Returns** TimeSpan

---

**DateDiff**(**date1**: DateTimeOffset, **date2**: DateTimeOffset): TimeSpan

Returns a number of time intervals between two specified dates.

**Parameters**

- **date1** (DateTimeOffset)  
- **date2** (DateTimeOffset)  

**Returns** TimeSpan

---

**DateDiff**(**date1**: DateTime?, **date2**: DateTime?): TimeSpan?

Returns a number of time intervals between two specified dates.

**Parameters**

- **date1** (DateTime?)  
- **date2** (DateTime?)  

**Returns** TimeSpan?

---

**DateDiff**(**date1**: DateTimeOffset?, **date2**: DateTimeOffset?): TimeSpan?

Returns a number of time intervals between two specified dates.

**Parameters**

- **date1** (DateTimeOffset?)  
- **date2** (DateTimeOffset?)  

**Returns** TimeSpan?


---

#### DateSerial `static`

**DateSerial**(**year**: long, **month**: long, **day**: long): DateTime

Returns the DateTime value for the specified year, month, and day.

**Parameters**

- **year** (long) — The year (1 through 9999).  
- **month** (long) — The month (1 through 12).  
- **day** (long) — The day (1 through the number of days in month).  

**Returns** DateTime — DateTime value.

---

**DateSerial**(**ticks**: long): DateTime

Returns the DateTime value for the specified number of ticks.

**Parameters**

- **ticks** (long) — A number of ticks that have elapsed since January 1, 0001.  

**Returns** DateTime — DateTime value.


---

#### Day `static`

**Day**(**date**: DateTime): long

Returns the day from a date and returns it as a integer value.

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**Day**(**date**: DateTimeOffset): long

Returns the day from a date and returns it as a integer value.

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**Day**(**date**: DateTime?): long

Returns the day from a date and returns it as a integer value.

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**Day**(**date**: DateTimeOffset?): long

Returns the day from a date and returns it as a integer value.

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long


---

#### DayOfWeek `static`

**DayOfWeek**(**date**: DateTime): string

Returns the day of the week.

**Parameters**

- **date** (DateTime)  

**Returns** string

---

**DayOfWeek**(**date**: DateTimeOffset): string

Returns the day of the week.

**Parameters**

- **date** (DateTimeOffset)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime?): string

Returns the day of the week.

**Parameters**

- **date** (DateTime?)  

**Returns** string

---

**DayOfWeek**(**date**: DateTimeOffset?): string

Returns the day of the week.

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime, **localized**: bool): string

Returns the day of the week.

**Parameters**

- **date** (DateTime)  
- **localized** (bool)  

**Returns** string

---

**DayOfWeek**(**date**: DateTimeOffset, **localized**: bool): string

Returns the day of the week.

**Parameters**

- **date** (DateTimeOffset)  
- **localized** (bool)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime?, **localized**: bool): string

Returns the day of the week.

**Parameters**

- **date** (DateTime?)  
- **localized** (bool)  

**Returns** string

---

**DayOfWeek**(**date**: DateTimeOffset?, **localized**: bool): string

Returns the day of the week.

**Parameters**

- **date** (DateTimeOffset?)  
- **localized** (bool)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime, **culture**: string): string

Returns the day of the week.

**Parameters**

- **date** (DateTime)  
- **culture** (string)  

**Returns** string

---

**DayOfWeek**(**date**: DateTimeOffset, **culture**: string): string

Returns the day of the week.

**Parameters**

- **date** (DateTimeOffset)  
- **culture** (string)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime?, **culture**: string): string

Returns the day of the week.

**Parameters**

- **date** (DateTime?)  
- **culture** (string)  

**Returns** string

---

**DayOfWeek**(**date**: DateTimeOffset?, **culture**: string): string

Returns the day of the week.

**Parameters**

- **date** (DateTimeOffset?)  
- **culture** (string)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime, **culture**: string, **upperCase**: bool): string

Returns the day of the week.

**Parameters**

- **date** (DateTime)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string

---

**DayOfWeek**(**date**: DateTimeOffset, **culture**: string, **upperCase**: bool): string

Returns the day of the week.

**Parameters**

- **date** (DateTimeOffset)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string

---

**DayOfWeek**(**date**: DateTime?, **culture**: string, **upperCase**: bool): string

Returns the day of the week.

**Parameters**

- **date** (DateTime?)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string

---

**DayOfWeek**(**date**: DateTimeOffset?, **culture**: string, **upperCase**: bool): string

Returns the day of the week.

**Parameters**

- **date** (DateTimeOffset?)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string


---

#### DayOfYear `static`

**DayOfYear**(**date**: DateTime): long

Returns the day of the year.

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**DayOfYear**(**date**: DateTimeOffset): long

Returns the day of the year.

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**DayOfYear**(**date**: DateTime?): long

Returns the day of the year.

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**DayOfYear**(**date**: DateTimeOffset?): long

Returns the day of the year.

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long


---

#### DaysInMonth `static`

**DaysInMonth**(**year**: long, **month**: long): long

Returns the number of days in the specified month and year.

**Parameters**

- **year** (long)  
- **month** (long)  

**Returns** long

---

**DaysInMonth**(**date**: DateTime): long

Returns the number of days in the specified month and year.

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**DaysInMonth**(**date**: DateTimeOffset): long

Returns the number of days in the specified month and year.

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**DaysInMonth**(**date**: DateTime?): long

Returns the number of days in the specified month and year.

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**DaysInMonth**(**date**: DateTimeOffset?): long

Returns the number of days in the specified month and year.

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long


---

#### DaysInYear `static`

**DaysInYear**(**year**: long): long

Returns the number of days in the specified year.

**Parameters**

- **year** (long)  

**Returns** long

---

**DaysInYear**(**date**: DateTime): long

Returns the number of days in the specified year.

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**DaysInYear**(**date**: DateTimeOffset): long

Returns the number of days in the specified year.

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**DaysInYear**(**date**: DateTime?): long

Returns the number of days in the specified year.

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**DaysInYear**(**date**: DateTimeOffset?): long

Returns the number of days in the specified year.

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long


---

#### FromOADate `static`

**FromOADate**(**value**: double): DateTime

Returns a DateTime equivalent to the specified OLE Automation Date.

**Parameters**

- **value** (double)  

**Returns** DateTime


---

#### Hour `static`

**Hour**(**date**: DateTime): long

Returns the hour portion from a date and returns it as a integer value.

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**Hour**(**date**: DateTimeOffset): long

Returns the hour portion from a date and returns it as a integer value.

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**Hour**(**date**: DateTime?): long

Returns the hour portion from a date and returns it as a integer value.

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**Hour**(**date**: DateTimeOffset?): long

Returns the hour portion from a date and returns it as a integer value.

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long


---

#### LocalTimeToUtc `static`

**LocalTimeToUtc**(**localDate**: DateTime): DateTime

Converts a local DateTime to UTC. Unspecified kinds are treated as Local.

**Parameters**

- **localDate** (DateTime)  

**Returns** DateTime


---

#### Minute `static`

**Minute**(**date**: DateTime): long

Returns the minutes portion from a date and returns it as a integer value.

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**Minute**(**date**: DateTimeOffset): long

Returns the minutes portion from a date and returns it as a integer value.

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**Minute**(**date**: DateTime?): long

Returns the minutes portion from a date and returns it as a integer value.

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**Minute**(**date**: DateTimeOffset?): long

Returns the minutes portion from a date and returns it as a integer value.

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long


---

#### Month `static`

**Month**(**date**: DateTime): long

Returns the month from a date and returns it as an integer value.

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**Month**(**date**: DateTimeOffset): long

Returns the month from a date and returns it as a integer value.

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**Month**(**date**: DateTime?): long

Returns the month from a date and returns it as a integer value.

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**Month**(**date**: DateTimeOffset?): long

Returns the month from a date and returns it as a integer value.

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long


---

#### MonthIdent `static`

**MonthIdent**(**value**: object): object

Returns the month identificator from the specified date-time value.

**Parameters**

- **value** (object)  

**Returns** object


---

#### MonthName `static`

**MonthName**(**date**: DateTime): string

Returns the name of the month.

**Parameters**

- **date** (DateTime)  

**Returns** string

---

**MonthName**(**date**: DateTime?): string

Returns the name of the month.

**Parameters**

- **date** (DateTime?)  

**Returns** string

---

**MonthName**(**date**: DateTime, **localized**: bool): string

Returns the name of the month.

**Parameters**

- **date** (DateTime)  
- **localized** (bool)  

**Returns** string

---

**MonthName**(**date**: DateTime?, **localized**: bool): string

Returns the name of the month.

**Parameters**

- **date** (DateTime?)  
- **localized** (bool)  

**Returns** string

---

**MonthName**(**date**: DateTime, **culture**: string): string

Returns the name of the month.

**Parameters**

- **date** (DateTime)  
- **culture** (string)  

**Returns** string

---

**MonthName**(**date**: DateTime?, **culture**: string): string

Returns the name of the month.

**Parameters**

- **date** (DateTime?)  
- **culture** (string)  

**Returns** string

---

**MonthName**(**date**: DateTime, **culture**: string, **upperCase**: bool): string

Returns the name of the month.

**Parameters**

- **date** (DateTime)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string

---

**MonthName**(**date**: DateTime?, **culture**: string, **upperCase**: bool): string

Returns the name of the month.

**Parameters**

- **date** (DateTime?)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string


---

#### Second `static`

**Second**(**date**: DateTime): long

Returns the seconds portion from a date and returns it as a integer value.

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**Second**(**date**: DateTimeOffset): long

Returns the seconds portion from a date and returns it as a integer value.

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**Second**(**date**: DateTime?): long

Returns the seconds portion from a date and returns it as a integer value.

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**Second**(**date**: DateTimeOffset?): long

Returns the seconds portion from a date and returns it as a integer value.

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long


---

#### TimeSerial `static`

**TimeSerial**(**hours**: long, **minutes**: long, **seconds**: long): TimeSpan

Returns the TimeValue value for a specified number of hours, minutes, and seconds.

**Parameters**

- **hours** (long)  
- **minutes** (long)  
- **seconds** (long)  

**Returns** TimeSpan


---

#### ToJapaneseDateString `static`

**ToJapaneseDateString**(**date**: DateTime): string

**Parameters**

- **date** (DateTime)  

**Returns** string

---

**ToJapaneseDateString**(**date**: DateTime, **format**: string): string

**Parameters**

- **date** (DateTime)  
- **format** (string)  

**Returns** string


---

#### ToOADate `static`

**ToOADate**(**value**: DateTime): double

Returns the equivalent OLE Automation date of specified datetime.

**Parameters**

- **value** (DateTime)  

**Returns** double


---

#### UtcToLocalTime `static`

**UtcToLocalTime**(**utcDate**: DateTime): DateTime

Converts a UTC DateTime to the system local time (DateTime.Kind -> Local).

**Parameters**

- **utcDate** (DateTime)  

**Returns** DateTime


---

#### WeekOfMonth `static`

**WeekOfMonth**(**date**: DateTime): long

Returns the week of the month that includes the date in the specified DateTime value.

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**WeekOfMonth**(**date**: DateTime?): long

Returns the week of the month that includes the date in the specified DateTime value.

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**WeekOfMonth**(**date**: DateTime, **firstDayOfWeek**: DayOfWeek): long

Returns the week of the month that includes the date in the specified DateTime value.

**Parameters**

- **date** (DateTime)  
- **firstDayOfWeek** (DayOfWeek)  

**Returns** long

---

**WeekOfMonth**(**date**: DateTime?, **firstDayOfWeek**: DayOfWeek): long

Returns the week of the month that includes the date in the specified DateTime value.

**Parameters**

- **date** (DateTime?)  
- **firstDayOfWeek** (DayOfWeek)  

**Returns** long

---

**WeekOfMonth**(**date**: DateTime, **firstDayOfWeek**: DayOfWeek, **calendarWeekRule**: CalendarWeekRule): long

Returns the week of the month that includes the date in the specified DateTime value.

**Parameters**

- **date** (DateTime)  
- **firstDayOfWeek** (DayOfWeek)  
- **calendarWeekRule** (CalendarWeekRule)  

**Returns** long

---

**WeekOfMonth**(**date**: DateTime?, **firstDayOfWeek**: DayOfWeek, **calendarWeekRule**: CalendarWeekRule): long

Returns the week of the month that includes the date in the specified DateTime value.

**Parameters**

- **date** (DateTime?)  
- **firstDayOfWeek** (DayOfWeek)  
- **calendarWeekRule** (CalendarWeekRule)  

**Returns** long


---

#### WeekOfYear `static`

**WeekOfYear**(**date**: DateTime): long

Returns the week of the year that includes the date in the specified DateTime value.

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**WeekOfYear**(**date**: DateTime?): long

Returns the week of the year that includes the date in the specified DateTime value.

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**WeekOfYear**(**date**: DateTime, **firstDayOfWeek**: DayOfWeek): long

Returns the week of the year that includes the date in the specified DateTime value.

**Parameters**

- **date** (DateTime)  
- **firstDayOfWeek** (DayOfWeek)  

**Returns** long

---

**WeekOfYear**(**date**: DateTime?, **firstDayOfWeek**: DayOfWeek): long

Returns the week of the year that includes the date in the specified DateTime value.

**Parameters**

- **date** (DateTime?)  
- **firstDayOfWeek** (DayOfWeek)  

**Returns** long

---

**WeekOfYear**(**date**: DateTime, **firstDayOfWeek**: DayOfWeek, **calendarWeekRule**: CalendarWeekRule): long

Returns the week of the year that includes the date in the specified DateTime value.

**Parameters**

- **date** (DateTime)  
- **firstDayOfWeek** (DayOfWeek)  
- **calendarWeekRule** (CalendarWeekRule)  

**Returns** long

---

**WeekOfYear**(**date**: DateTime?, **firstDayOfWeek**: DayOfWeek, **calendarWeekRule**: CalendarWeekRule): long

Returns the week of the year that includes the date in the specified DateTime value.

**Parameters**

- **date** (DateTime?)  
- **firstDayOfWeek** (DayOfWeek)  
- **calendarWeekRule** (CalendarWeekRule)  

**Returns** long


---

#### Year `static`

**Year**(**date**: DateTime): long

Returns the year from a date and returns it as a integer value.

**Parameters**

- **date** (DateTime)  

**Returns** long

---

**Year**(**date**: DateTimeOffset): long

Returns the year from a date and returns it as an integer value.

**Parameters**

- **date** (DateTimeOffset)  

**Returns** long

---

**Year**(**date**: DateTime?): long

Returns the year from a date and returns it as an integer value.

**Parameters**

- **date** (DateTime?)  

**Returns** long

---

**Year**(**date**: DateTimeOffset?): long

Returns the year from a date and returns it as an integer value.

**Parameters**

- **date** (DateTimeOffset?)  

**Returns** long

