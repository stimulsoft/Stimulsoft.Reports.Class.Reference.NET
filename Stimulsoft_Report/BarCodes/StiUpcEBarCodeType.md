---
title: "StiUpcEBarCodeType Class"
---

## StiUpcEBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

The class describes the Barcode type - UPC-E.

### Inheritance

Inherits from: [StiEAN13BarCodeType](StiEAN13BarCodeType.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiUpcEBarCodeType**() |  |
| **StiUpcEBarCodeType**(float module, float height, [StiEanSupplementType](StiEanSupplementType.md) supplementType, string supplementCodeValue, bool showQuietZoneIndicator) |  |

**StiUpcEBarCodeType**()

---

**StiUpcEBarCodeType**(**module**: float, **height**: float, **supplementType**: [StiEanSupplementType](StiEanSupplementType.md), **supplementCodeValue**: string, **showQuietZoneIndicator**: bool)

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
| **MakeUpcEBars** | List<EanBarInfo> |  |

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

#### MakeUpcEBars

**MakeUpcEBars**(**code**: string, **isLast**: bool): List<EanBarInfo>

**Parameters**

- **code** (string)  
- **isLast** (bool)  

**Returns** List<EanBarInfo>

