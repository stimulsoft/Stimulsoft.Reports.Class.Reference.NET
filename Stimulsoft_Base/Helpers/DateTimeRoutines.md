---
title: "DateTimeRoutines Class"
---

## DateTimeRoutines Class

**Namespace:** `Stimulsoft.Base.Helpers`  
**Assembly:** `Stimulsoft.Base`

Miscellaneous and parsing methods for DateTime

```csharp
public static class DateTimeRoutines
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DefaultDateIsNow** `static` | bool | If true then DefaultDate property is ignored and DefaultDate is always DateTime.Now |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **TryParseDate** `static` *(+1 overloads)* | bool | Tries to find date within the passed string and return it as DateTime structure. It recognizes only date while ignoring time, so time in the returned DateTime is always 0:0:0. If year of the date was not found then it accepts the current year. |
| **TryParseDateOrTime** `static` *(+1 overloads)* | bool | Tries to find date and/or time within the passed string and return it as DateTime structure. If only date was found, time in the returned DateTime is always 0:0:0. If only time was found, date in the returned DateTime is DefaultDate. |
| **TryParseDateTime** `static` *(+1 overloads)* | bool | Tries to find date and time within the passed string and return it as DateTime structure. |
| **TryParseTime** `static` *(+2 overloads)* | bool | Tries to find time within the passed string and return it as DateTime structure. It recognizes only time while ignoring date, so date in the returned DateTime is always 1/1/1. |
