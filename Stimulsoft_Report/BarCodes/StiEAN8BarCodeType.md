---
title: "StiEAN8BarCodeType Class"
---

## StiEAN8BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

The class describes the Barcode type - EAN-8.

### Inheritance

Inherits from: [StiEAN13BarCodeType](StiEAN13BarCodeType.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiEAN8BarCodeType**() |  |
| **StiEAN8BarCodeType**(float module, float height, [StiEanSupplementType](StiEanSupplementType.md) supplementType, string supplementCodeValue, bool showQuietZoneIndicator) |  |

**StiEAN8BarCodeType**()

---

**StiEAN8BarCodeType**(**module**: float, **height**: float, **supplementType**: [StiEanSupplementType](StiEanSupplementType.md), **supplementCodeValue**: string, **showQuietZoneIndicator**: bool)

**Parameters**

- **module** (float)  
- **height** (float)  
- **supplementType** ([StiEanSupplementType](StiEanSupplementType.md))  
- **supplementCodeValue** (string)  
- **showQuietZoneIndicator** (bool)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **EanLineHeightShort** | float |  |
| **EanMainHeight** | float |  |
| **EanSpaceLeft** | float |  |
| **EanSpaceRight** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws the bar code with the specified parameters. |
| **MakeEan8Bars** | List<EanBarInfo> |  |

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

#### MakeEan8Bars

**MakeEan8Bars**(**code**: string, **isLast**: bool): List<EanBarInfo>

**Parameters**

- **code** (string)  
- **isLast** (bool)  

**Returns** List<EanBarInfo>

