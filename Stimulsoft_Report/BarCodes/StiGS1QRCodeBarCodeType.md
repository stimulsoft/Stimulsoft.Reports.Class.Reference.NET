---
title: "StiGS1QRCodeBarCodeType Class"
---

## StiGS1QRCodeBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: [StiQRCodeBarCodeType](StiQRCodeBarCodeType.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGS1QRCodeBarCodeType**() |  |
| **StiGS1QRCodeBarCodeType**(float module, [StiQRCodeErrorCorrectionLevel](StiQRCodeErrorCorrectionLevel.md) errorCorrectionLevel, [StiQRCodeSize](StiQRCodeSize.md) matrixSize) |  |

**StiGS1QRCodeBarCodeType**()

---

**StiGS1QRCodeBarCodeType**(**module**: float, **errorCorrectionLevel**: [StiQRCodeErrorCorrectionLevel](StiQRCodeErrorCorrectionLevel.md), **matrixSize**: [StiQRCodeSize](StiQRCodeSize.md))

**Parameters**

- **module** (float)  
- **errorCorrectionLevel** ([StiQRCodeErrorCorrectionLevel](StiQRCodeErrorCorrectionLevel.md))  
- **matrixSize** ([StiQRCodeSize](StiQRCodeSize.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Image** | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **ImageMultipleFactor** | double |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void |  |
| **GetBarcodeImage** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |

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

#### GetBarcodeImage `static`

**GetBarcodeImage**(**code**: string, **zoom**: int): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **code** (string)  
- **zoom** (int)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)

