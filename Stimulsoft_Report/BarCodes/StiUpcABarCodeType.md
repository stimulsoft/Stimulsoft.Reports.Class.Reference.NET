---
title: "StiUpcABarCodeType Class"
---

## StiUpcABarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: [StiEAN13BarCodeType](StiEAN13BarCodeType.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiUpcABarCodeType**() |  |
| **StiUpcABarCodeType**(float module, float height, [StiEanSupplementType](StiEanSupplementType.md) supplementType, string supplementCodeValue, bool showQuietZoneIndicator) |  |

**StiUpcABarCodeType**()

---

**StiUpcABarCodeType**(**module**: float, **height**: float, **supplementType**: [StiEanSupplementType](StiEanSupplementType.md), **supplementCodeValue**: string, **showQuietZoneIndicator**: bool)

**Parameters**

- **module** (float)  
- **height** (float)  
- **supplementType** ([StiEanSupplementType](StiEanSupplementType.md))  
- **supplementCodeValue** (string)  
- **showQuietZoneIndicator** (bool)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **EanSpaceLeft** | float |  |
| **EanSpaceRight** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws the bar code with the specified parameters. |
| **MakeUpcABars** | List<EanBarInfo> |  |

---

### Method Details

#### Draw

**Draw**(**context**: object, **barCode**: StiBarCode, **rect**: RectangleF, **zoom**: float): void

Draws the bar code with the specified parameters.

**Parameters**

- **context** (object) — Context for drawing.  
- **barCode** (StiBarCode) — Component that invokes drawing.  
- **rect** (RectangleF) — The rectangle that shows coordinates for drawing.  
- **zoom** (float) — Zoom of drawing.  


---

#### MakeUpcABars

**MakeUpcABars**(**code**: string, **isLast**: bool): List<EanBarInfo>

**Parameters**

- **code** (string)  
- **isLast** (bool)  

**Returns** List<EanBarInfo>

