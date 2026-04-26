---
title: "StiFIMBarCodeType Class"
---

## StiFIMBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiFIMBarCodeType**() |  |
| **StiFIMBarCodeType**(float module, float height, bool addClearZone) |  |

**StiFIMBarCodeType**()

---

**StiFIMBarCodeType**(**module**: float, **height**: float, **addClearZone**: bool)

**Parameters**

- **module** (float)  
- **height** (float)  
- **addClearZone** (bool)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AddClearZone** | bool |  |
| **FIMSpaceLeft** | float |  |
| **FIMSpaceRight** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Draw

**Draw**(**context**: object, **barCode**: StiBarCode, **rect**: RectangleF, **zoom**: float): void

**Parameters**

- **context** (object)  
- **barCode** (StiBarCode)  
- **rect** (RectangleF)  
- **zoom** (float)  


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **FIMLineHeightForCut** | float |  |
| **FIMLineHeightLong** | float |  |
| **FIMLineHeightShort** | float |  |
| **FIMMainHeight** | float |  |
| **FIMSpaceBottom** | float |  |
| **FIMSpaceTop** | float |  |
| **FIMSymbols** | string |  |
| **FIMTextHeight** | float |  |
| **FIMTextPosition** | float |  |
| **defaultFIMModule** | float |  |
