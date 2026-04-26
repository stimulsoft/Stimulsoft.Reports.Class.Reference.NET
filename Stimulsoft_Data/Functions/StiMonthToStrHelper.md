---
title: "StiMonthToStrHelper Class"
---

## StiMonthToStrHelper Class

**Namespace:** `Stimulsoft.Data.Functions`

MonthToStr helper.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddCulture** `static` | void |  |
| **Month** `static` *(+1 overloads)* | StiMonth? |  |
| **MonthName** `static` *(+4 overloads)* | string |  |

---

### Method Details

#### AddCulture `static`

**AddCulture**(****: stringmonthNames, ****: stringcultureNames, **defaultUpperCase**: bool): void

**Parameters**

- **** (stringmonthNames)  
- **** (stringcultureNames)  
- **defaultUpperCase** (bool)  


---

#### Month `static`

**Month**(**value**: int): StiMonth?

**Parameters**

- **value** (int)  

**Returns** StiMonth?

---

**Month**(**str**: string): StiMonth?

**Parameters**

- **str** (string)  

**Returns** StiMonth?


---

#### MonthName `static`

**MonthName**(**dateTime**: DateTime): string

**Parameters**

- **dateTime** (DateTime)  

**Returns** string

---

**MonthName**(**dateTime**: DateTime, **localized**: bool): string

**Parameters**

- **dateTime** (DateTime)  
- **localized** (bool)  

**Returns** string

---

**MonthName**(**dateTime**: DateTime, **culture**: string): string

**Parameters**

- **dateTime** (DateTime)  
- **culture** (string)  

**Returns** string

---

**MonthName**(**month**: int, **culture**: string): string

**Parameters**

- **month** (int)  
- **culture** (string)  

**Returns** string

---

**MonthName**(**dateTime**: DateTime, **culture**: string, **upperCase**: bool): string

**Parameters**

- **dateTime** (DateTime)  
- **culture** (string)  
- **upperCase** (bool)  

**Returns** string

