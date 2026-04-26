---
title: "StiUpcSup2BarCodeType Class"
---

## StiUpcSup2BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: [StiEAN13BarCodeType](StiEAN13BarCodeType.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiUpcSup2BarCodeType**() |  |
| **StiUpcSup2BarCodeType**(float module, float height, [StiEanSupplementType](StiEanSupplementType.md) supplementType, string supplementCodeValue, bool showQuietZoneIndicator) |  |

**StiUpcSup2BarCodeType**()

---

**StiUpcSup2BarCodeType**(**module**: float, **height**: float, **supplementType**: [StiEanSupplementType](StiEanSupplementType.md), **supplementCodeValue**: string, **showQuietZoneIndicator**: bool)

**Parameters**

- **module** (float)  
- **height** (float)  
- **supplementType** ([StiEanSupplementType](StiEanSupplementType.md))  
- **supplementCodeValue** (string)  
- **showQuietZoneIndicator** (bool)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws the bar code with the specified parameters. |

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

