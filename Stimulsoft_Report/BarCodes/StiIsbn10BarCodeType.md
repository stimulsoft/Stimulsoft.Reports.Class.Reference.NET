---
title: "StiIsbn10BarCodeType Class"
---

## StiIsbn10BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: [StiIsbn13BarCodeType](StiIsbn13BarCodeType.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiIsbn10BarCodeType**() |  |
| **StiIsbn10BarCodeType**(float module, float height, [StiEanSupplementType](StiEanSupplementType.md) supplementType, string supplementCodeValue, bool showQuietZoneIndicator) |  |

**StiIsbn10BarCodeType**()

---

**StiIsbn10BarCodeType**(**module**: float, **height**: float, **supplementType**: [StiEanSupplementType](StiEanSupplementType.md), **supplementCodeValue**: string, **showQuietZoneIndicator**: bool)

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

