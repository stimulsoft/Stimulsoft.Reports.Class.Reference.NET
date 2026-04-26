---
title: "StiMsiBarCodeType Class"
---

## StiMsiBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

The class describes the Barcode type - Msi.

### Inheritance

Inherits from: [StiPlesseyBarCodeType](StiPlesseyBarCodeType.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMsiBarCodeType**() |  |
| **StiMsiBarCodeType**(float module, float height, [StiPlesseyCheckSum](StiPlesseyCheckSum.md) checkSum1, [StiPlesseyCheckSum](StiPlesseyCheckSum.md) checkSum2) |  |

**StiMsiBarCodeType**()

---

**StiMsiBarCodeType**(**module**: float, **height**: float, **checkSum1**: [StiPlesseyCheckSum](StiPlesseyCheckSum.md), **checkSum2**: [StiPlesseyCheckSum](StiPlesseyCheckSum.md))

**Parameters**

- **module** (float)  
- **height** (float)  
- **checkSum1** ([StiPlesseyCheckSum](StiPlesseyCheckSum.md))  
- **checkSum2** ([StiPlesseyCheckSum](StiPlesseyCheckSum.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CodeToBarMsi** | string |  |
| **Draw** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### CodeToBarMsi

**CodeToBarMsi**(**inputCode**: string): string

**Parameters**

- **inputCode** (string)  

**Returns** string


---

#### Draw

**Draw**(**context**: object, **barCode**: StiBarCode, **rect**: RectangleF, **zoom**: float): void

**Parameters**

- **context** (object)  
- **barCode** (StiBarCode)  
- **rect** (RectangleF)  
- **zoom** (float)  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

