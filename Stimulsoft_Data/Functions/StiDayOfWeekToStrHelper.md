---
title: "StiDayOfWeekToStrHelper Class"
---

## StiDayOfWeekToStrHelper Class

**Namespace:** `Stimulsoft.Data.Functions`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddCulture** `static` | void |  |
| **DayOfWeek** `static` *(+9 overloads)* | string | Returns the day of the week. |

---

### Method Details

#### AddCulture `static`

**AddCulture**(****: stringmonthNames, ****: stringcultureNames, **defaultUpperCase**: bool): void

**Parameters**

- **** (stringmonthNames)  
- **** (stringcultureNames)  
- **defaultUpperCase** (bool)  


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

**DayOfWeek**(**dateTime**: DateTime, **culture**: string): string

**Parameters**

- **dateTime** (DateTime)  
- **culture** (string)  

**Returns** string

---

**DayOfWeek**(**dateTime**: DateTimeOffset, **culture**: string): string

**Parameters**

- **dateTime** (DateTimeOffset)  
- **culture** (string)  

**Returns** string

---

**DayOfWeek**(**dayOfWeek**: int, **culture**: string): string

**Parameters**

- **dayOfWeek** (int)  
- **culture** (string)  

**Returns** string

---

**DayOfWeek**(**dateTime**: DateTime, **culture**: string, **upperCase**: bool): string

**Parameters**

- **dateTime** (DateTime)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string

---

**DayOfWeek**(**dateTime**: DateTimeOffset, **culture**: string, **upperCase**: bool): string

**Parameters**

- **dateTime** (DateTimeOffset)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string

---

**DayOfWeek**(**str**: string): DayOfWeek?

**Parameters**

- **str** (string)  

**Returns** DayOfWeek?

