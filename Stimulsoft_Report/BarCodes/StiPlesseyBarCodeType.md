---
title: "StiPlesseyBarCodeType Class"
---

## StiPlesseyBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPlesseyBarCodeType**() |  |
| **StiPlesseyBarCodeType**(float module, float height, [StiPlesseyCheckSum](StiPlesseyCheckSum.md) checkSum1, [StiPlesseyCheckSum](StiPlesseyCheckSum.md) checkSum2) |  |

**StiPlesseyBarCodeType**()

---

**StiPlesseyBarCodeType**(**module**: float, **height**: float, **checkSum1**: [StiPlesseyCheckSum](StiPlesseyCheckSum.md), **checkSum2**: [StiPlesseyCheckSum](StiPlesseyCheckSum.md))

**Parameters**

- **module** (float)  
- **height** (float)  
- **checkSum1** ([StiPlesseyCheckSum](StiPlesseyCheckSum.md))  
- **checkSum2** ([StiPlesseyCheckSum](StiPlesseyCheckSum.md))  


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
| **PlesseyLineHeightForCut** | float |  |
| **PlesseyLineHeightLong** | float |  |
| **PlesseyLineHeightShort** | float |  |
| **PlesseyMainHeight** | float |  |
| **PlesseySpaceBottom** | float |  |
| **PlesseySpaceLeft** | float |  |
| **PlesseySpaceRight** | float |  |
| **PlesseySpaceTop** | float |  |
| **PlesseySymbols** | string |  |
| **PlesseyTextHeight** | float |  |
| **PlesseyTextPosition** | float |  |
