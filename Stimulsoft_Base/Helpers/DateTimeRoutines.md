---
title: "DateTimeRoutines Class"
---

## DateTimeRoutines Class

**Namespace:** `Stimulsoft.Base.Helpers`

Miscellaneous and parsing methods for DateTime

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

---

### Method Details

#### TryParseDate `static`

**TryParseDate**(**str**: string, **defaultFormat**: DateTimeFormat, **date**: DateTime): bool

Tries to find date within the passed string and return it as DateTime structure. It recognizes only date while ignoring time, so time in the returned DateTime is always 0:0:0. If year of the date was not found then it accepts the current year.

**Parameters**

- **str** (string) — string that contains date  
- **defaultFormat** (DateTimeFormat) — format to be used preferably in ambivalent instances  
- **date** (DateTime) — parsed date output  

**Returns** bool — true if date was found, else false

---

**TryParseDate**(**str**: string, **defaultFormat**: DateTimeFormat, **parsedDate**: ParsedDateTime): bool

Tries to find date within the passed string and return it as ParsedDateTime object. It recognizes only date while ignoring time, so time in the returned ParsedDateTime is always 0:0:0. If year of the date was not found then it accepts the current year.

**Parameters**

- **str** (string) — string that contains date  
- **defaultFormat** (DateTimeFormat) — format to be used preferably in ambivalent instances  
- **parsedDate** (ParsedDateTime) — parsed date output  

**Returns** bool — true if date was found, else false


---

#### TryParseDateOrTime `static`

**TryParseDateOrTime**(**str**: string, **defaultFormat**: DateTimeFormat, **dateTime**: DateTime): bool

Tries to find date and/or time within the passed string and return it as DateTime structure. If only date was found, time in the returned DateTime is always 0:0:0. If only time was found, date in the returned DateTime is DefaultDate.

**Parameters**

- **str** (string) — string that contains date and(or) time  
- **defaultFormat** (DateTimeFormat) — format to be used preferably in ambivalent instances  
- **dateTime** (DateTime) — parsed date-time output  

**Returns** bool — true if date and/or time was found, else false

---

**TryParseDateOrTime**(**str**: string, **defaultFormat**: DateTimeFormat, **parsedDateTime**: ParsedDateTime): bool

Tries to find date and/or time within the passed string and return it as ParsedDateTime object. If only date was found, time in the returned ParsedDateTime is always 0:0:0. If only time was found, date in the returned ParsedDateTime is DefaultDate.

**Parameters**

- **str** (string) — string that contains date-time  
- **defaultFormat** (DateTimeFormat) — format to be used preferably in ambivalent instances  
- **parsedDateTime** (ParsedDateTime) — parsed date-time output  

**Returns** bool — true if date or time was found, else false


---

#### TryParseDateTime `static`

**TryParseDateTime**(**str**: string, **defaultFormat**: DateTimeFormat, **dateTime**: DateTime): bool

Tries to find date and time within the passed string and return it as DateTime structure.

**Parameters**

- **str** (string) — string that contains date and/or time  
- **defaultFormat** (DateTimeFormat) — format to be used preferably in ambivalent instances  
- **dateTime** (DateTime) — parsed date-time output  

**Returns** bool — true if both date and time were found, else false

---

**TryParseDateTime**(**str**: string, **defaultFormat**: DateTimeFormat, **parsedDateTime**: ParsedDateTime): bool

Tries to find date and time within the passed string and return it as ParsedDateTime object.

**Parameters**

- **str** (string) — string that contains date-time  
- **defaultFormat** (DateTimeFormat) — format to be used preferably in ambivalent instances  
- **parsedDateTime** (ParsedDateTime) — parsed date-time output  

**Returns** bool — true if both date and time were found, else false


---

#### TryParseTime `static`

**TryParseTime**(**str**: string, **defaultFormat**: DateTimeFormat, **time**: DateTime): bool

Tries to find time within the passed string and return it as DateTime structure. It recognizes only time while ignoring date, so date in the returned DateTime is always 1/1/1.

**Parameters**

- **str** (string) — string that contains time  
- **defaultFormat** (DateTimeFormat) — format to be used preferably in ambivalent instances  
- **time** (DateTime) — parsed time output  

**Returns** bool — true if time was found, else false

---

**TryParseTime**(**str**: string, **defaultFormat**: DateTimeFormat, **parsedTime**: ParsedDateTime): bool

Tries to find time within the passed string and return it as ParsedDateTime object. It recognizes only time while ignoring date, so date in the returned ParsedDateTime is always 1/1/1

**Parameters**

- **str** (string) — string that contains date-time  
- **defaultFormat** (DateTimeFormat) — format to be used preferably in ambivalent instances  
- **parsedTime** (ParsedDateTime) — parsed date-time output  

**Returns** bool — true if time was found, else false

---

**TryParseTime**(**str**: string, **defaultFormat**: DateTimeFormat, **parsedTime**: ParsedDateTime, **parsedDate**: ParsedDateTime): bool

Tries to find time within the passed string (relatively to the passed parsedDate if any) and return it as ParsedDateTime object. It recognizes only time while ignoring date, so date in the returned ParsedDateTime is always 1/1/1

**Parameters**

- **str** (string) — string that contains date  
- **defaultFormat** (DateTimeFormat) — format to be used preferably in ambivalent instances  
- **parsedTime** (ParsedDateTime) — parsed date-time output  
- **parsedDate** (ParsedDateTime) — ParsedDateTime object if the date was found within this string, else NULL  

**Returns** bool — true if time was found, else false

