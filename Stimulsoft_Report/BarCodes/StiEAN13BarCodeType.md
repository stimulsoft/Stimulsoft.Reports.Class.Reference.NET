---
title: "StiEAN13BarCodeType Class"
---

## StiEAN13BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiEAN13BarCodeType**() |  |

**StiEAN13BarCodeType**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **EanLineHeightForCut** | float |  |
| **EanLineHeightLong** | float |  |
| **EanLineHeightShort** | float |  |
| **EanMainHeight** | float |  |
| **EanSpaceBeforeAdd** | float |  |
| **EanSpaceBottom** | float |  |
| **EanSpaceLeft** | float |  |
| **EanSpaceRight** | float |  |
| **EanSpaceTextTop** | float |  |
| **EanSpaceTop** | float |  |
| **EanTextHeight** | float |  |
| **EanTextPositionBottom** | float |  |
| **EanTextPositionTop** | float |  |
| **EanWideToNarrowRatio** | float |  |
| **ShowQuietZoneIndicator** | bool |  |
| **SupplementCode** | string |  |
| **SupplementType** | [StiEanSupplementType](StiEanSupplementType.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws the bar code with the specified parameters. |
| **DrawEanBars** | void |  |
| **GetSymbolWidth** | float | Returns width of one symbol in module. |
| **IsSymbolSpace** | bool | Returns true is char is space. |
| **LoadFromJsonObject** | void |  |
| **MakeEan13Bars** | List<EanBarInfo> |  |
| **MakeEanAdd2Bars** | List<EanBarInfo> |  |
| **MakeEanAdd5Bars** | List<EanBarInfo> |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **makeLonger** | string |  |

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

#### DrawEanBars

**DrawEanBars**(**context**: object, **barsArray**: List<EanBarInfo>, **barCode**: StiBarCode): void

**Parameters**

- **context** (object)  
- **barsArray** (List<EanBarInfo>)  
- **barCode** (StiBarCode)  


---

#### GetSymbolWidth

**GetSymbolWidth**(**symbol**: char): float

Returns width of one symbol in module.

**Parameters**

- **symbol** (char)  

**Returns** float


---

#### IsSymbolSpace

**IsSymbolSpace**(**symbol**: char): bool

Returns true is char is space.

**Parameters**

- **symbol** (char)  

**Returns** bool


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### MakeEan13Bars

**MakeEan13Bars**(**code**: string, **isLast**: bool): List<EanBarInfo>

**Parameters**

- **code** (string)  
- **isLast** (bool)  

**Returns** List<EanBarInfo>


---

#### MakeEanAdd2Bars

**MakeEanAdd2Bars**(**code**: string, **baseArray**: List<EanBarInfo>, **isLast**: bool): List<EanBarInfo>

**Parameters**

- **code** (string)  
- **baseArray** (List<EanBarInfo>)  
- **isLast** (bool)  

**Returns** List<EanBarInfo>


---

#### MakeEanAdd5Bars

**MakeEanAdd5Bars**(**code**: string, **baseArray**: List<EanBarInfo>, **isLast**: bool): List<EanBarInfo>

**Parameters**

- **code** (string)  
- **baseArray** (List<EanBarInfo>)  
- **isLast** (bool)  

**Returns** List<EanBarInfo>


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


---

#### makeLonger

**makeLonger**(**symString**: string): string

**Parameters**

- **symString** (string)  

**Returns** string

