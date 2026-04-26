---
title: "StiExportUtils Class"
---

## StiExportUtils Class

**Namespace:** `Stimulsoft.Report.Export`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ByteArrayToHex** `static` | string |  |
| **ConvertDigitsToArabic** `static` *(+1 overloads)* | string |  |
| **CorrectEncoding** `static` | string |  |
| **CorrectRichTextForRiched20** `static` *(+1 overloads)* | void |  |
| **DisableFontSmoothing** `static` | void |  |
| **EnableFontSmoothing** `static` | void |  |
| **EnableFontSmoothingInternal** `static` | void |  |
| **GetNegativePattern** `static` | string |  |
| **GetPositivePattern** `static` | string |  |
| **GetReportVersion** `static` | string |  |
| **MakePdfDeflateStream** `static` | MemoryStream |  |
| **SaveComponentToString** `static` *(+1 overloads)* | string |  |
| **SplitString** `static` *(+1 overloads)* | List<string> |  |
| **StringToUrl** `static` | string |  |
| **TrimEndWhiteSpace** `static` *(+1 overloads)* | string |  |

---

### Method Details

#### ByteArrayToHex `static`

**ByteArrayToHex**(****: bytebytes): string

**Parameters**

- **** (bytebytes)  

**Returns** string


---

#### ConvertDigitsToArabic `static`

**ConvertDigitsToArabic**(**outputString**: string, **digitsType**: [StiArabicDigitsType](../root/StiArabicDigitsType.md)): string

**Parameters**

- **outputString** (string)  
- **digitsType** ([StiArabicDigitsType](../root/StiArabicDigitsType.md))  

**Returns** string

---

**ConvertDigitsToArabic**(**outputString**: StringBuilder, **digitsType**: [StiArabicDigitsType](../root/StiArabicDigitsType.md)): StringBuilder

**Parameters**

- **outputString** (StringBuilder)  
- **digitsType** ([StiArabicDigitsType](../root/StiArabicDigitsType.md))  

**Returns** StringBuilder


---

#### CorrectEncoding `static`

**CorrectEncoding**(**st**: string): string

**Parameters**

- **st** (string)  

**Returns** string


---

#### CorrectRichTextForRiched20 `static`

**CorrectRichTextForRiched20**(**rich**: StiRichText): void

**Parameters**

- **rich** (StiRichText)  

---

**CorrectRichTextForRiched20**(**baseText**: string): string

**Parameters**

- **baseText** (string)  

**Returns** string


---

#### DisableFontSmoothing `static`

**DisableFontSmoothing**(**report**: [StiReport](../root/StiReport.md)): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  


---

#### EnableFontSmoothing `static`

**EnableFontSmoothing**(**report**: [StiReport](../root/StiReport.md)): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  


---

#### EnableFontSmoothingInternal `static`

**EnableFontSmoothingInternal**(): void


---

#### GetNegativePattern `static`

**GetNegativePattern**(**patternIndex**: int): string

**Parameters**

- **patternIndex** (int)  

**Returns** string


---

#### GetPositivePattern `static`

**GetPositivePattern**(**patternIndex**: int): string

**Parameters**

- **patternIndex** (int)  

**Returns** string


---

#### GetReportVersion `static`

**GetReportVersion**(**report**: [StiReport](../root/StiReport.md)): string

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

**Returns** string


---

#### MakePdfDeflateStream `static`

**MakePdfDeflateStream**(****: bytedata): MemoryStream

**Parameters**

- **** (bytedata)  

**Returns** MemoryStream


---

#### SaveComponentToString `static`

**SaveComponentToString**(**component**: StiComponent): string

**Parameters**

- **component** (StiComponent)  

**Returns** string

---

**SaveComponentToString**(**component**: StiComponent, **imageFormat**: [ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md), **imageQuality**: float, **imageResolution**: float): string

**Parameters**

- **component** (StiComponent)  
- **imageFormat** ([ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md))  
- **imageQuality** (float)  
- **imageResolution** (float)  

**Returns** string


---

#### SplitString `static`

**SplitString**(**inputString**: string, **removeControl**: bool): List<string>

**Parameters**

- **inputString** (string)  
- **removeControl** (bool)  

**Returns** List<string>

---

**SplitString**(**inputString**: string, **delimiter**: char): string[]

**Parameters**

- **inputString** (string)  
- **delimiter** (char)  

**Returns** string[]


---

#### StringToUrl `static`

**StringToUrl**(**input**: string): string

**Parameters**

- **input** (string)  

**Returns** string


---

#### TrimEndWhiteSpace `static`

**TrimEndWhiteSpace**(**inputString**: string): string

**Parameters**

- **inputString** (string)  

**Returns** string

---

**TrimEndWhiteSpace**(**inputString**: string, **removeControl**: bool): string

**Parameters**

- **inputString** (string)  
- **removeControl** (bool)  

**Returns** string

