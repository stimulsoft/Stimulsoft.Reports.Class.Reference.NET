---
title: "StiTestConnectionResult Class"
---

## StiTestConnectionResult Class

**Namespace:** `Stimulsoft.Base`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Notice** | string | A message which describes the result of connection testing. |
| **Success** | bool | A value which indicates the result of connection testing. True if connection tested successfully. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **MakeFine** `static` | [StiTestConnectionResult](StiTestConnectionResult.md) |  |
| **MakeWrong** `static` *(+2 overloads)* | [StiTestConnectionResult](StiTestConnectionResult.md) |  |

---

### Method Details

#### MakeFine `static`

**MakeFine**(): [StiTestConnectionResult](StiTestConnectionResult.md)

**Returns** [StiTestConnectionResult](StiTestConnectionResult.md)


---

#### MakeWrong `static`

**MakeWrong**(**notice**: string): [StiTestConnectionResult](StiTestConnectionResult.md)

**Parameters**

- **notice** (string)  

**Returns** [StiTestConnectionResult](StiTestConnectionResult.md)

---

**MakeWrong**(**exception**: Exception): [StiTestConnectionResult](StiTestConnectionResult.md)

**Parameters**

- **exception** (Exception)  

**Returns** [StiTestConnectionResult](StiTestConnectionResult.md)

---

**MakeWrong**(): [StiTestConnectionResult](StiTestConnectionResult.md)

**Returns** [StiTestConnectionResult](StiTestConnectionResult.md)

