---
title: "StiUsedDataHelper Class"
---

## StiUsedDataHelper Class

**Namespace:** `Stimulsoft.Data.Helpers`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetMany** `static` *(+1 overloads)* | List<string> |  |
| **GetSingle** `static` *(+1 overloads)* | List<string> |  |

---

### Method Details

#### GetMany `static`

**GetMany**(****: IStiMetermeters): List<string>

**Parameters**

- **** (IStiMetermeters)  

**Returns** List<string>

---

**GetMany**(**meters**: IEnumerable<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)>): List<string>

**Parameters**

- **meters** (IEnumerable<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)>)  

**Returns** List<string>


---

#### GetSingle `static`

**GetSingle**(**meter**: [IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)): List<string>

**Parameters**

- **meter** ([IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md))  

**Returns** List<string>

---

**GetSingle**(**expression**: string): List<string>

**Parameters**

- **expression** (string)  

**Returns** List<string>

