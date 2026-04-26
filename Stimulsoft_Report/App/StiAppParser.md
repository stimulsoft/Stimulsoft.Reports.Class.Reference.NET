---
title: "StiAppParser Class"
---

## StiAppParser Class

**Namespace:** `Stimulsoft.Report.App`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **UseScriptParser** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetExpressions** `static` | IEnumerable<StiAppExpression> |  |
| **IsDataPathExistInBindings** `static` | bool |  |
| **IsDataPathExistInExpression** `static` | bool |  |
| **IsVariablesExistInBindings** `static` | bool |  |
| **IsVariablesExistInExpression** `static` | bool |  |
| **ParseBoolExpression** `static` | bool |  |
| **ParseBoolExpressionOrDefault** `static` | bool |  |
| **ParseBrushExpression** `static` | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **ParseColorExpression** `static` | Color |  |
| **ParseColorExpressionOrDefault** `static` | Color |  |
| **ParseDecimalExpression** `static` | decimal |  |
| **ParseDecimalExpressionOrDefault** `static` | decimal |  |
| **ParseEnumExpression** `static` *(+1 overloads)* | T |  |
| **ParseEnumExpressionOrDefault** `static` | T |  |
| **ParseFloatExpression** `static` | float |  |
| **ParseFloatExpressionOrDefault** `static` | float |  |
| **ParseFontExpression** `static` | [Font](../../Stimulsoft_Drawing/root/Font.md) |  |
| **ParseFontExpressionOrDefault** `static` | [Font](../../Stimulsoft_Drawing/root/Font.md) |  |
| **ParseIntExpression** `static` | int |  |
| **ParseIntExpressionOrDefault** `static` | int |  |
| **ParseStringExpression** `static` | string |  |
| **ParseStringExpressionOrDefault** `static` | string |  |
| **ProcessExpressions** `static` | void |  |

---

### Method Details

#### GetExpressions `static`

**GetExpressions**(**component**: object): IEnumerable<StiAppExpression>

**Parameters**

- **component** (object)  

**Returns** IEnumerable<StiAppExpression>


---

#### IsDataPathExistInBindings `static`

**IsDataPathExistInBindings**(**element**: [IStiElementUI](IStiElementUI.md), ****: stringdataPaths): bool

**Parameters**

- **element** ([IStiElementUI](IStiElementUI.md))  
- **** (stringdataPaths)  

**Returns** bool


---

#### IsDataPathExistInExpression `static`

**IsDataPathExistInExpression**(**element**: [IStiElementUI](IStiElementUI.md), ****: stringdataPaths): bool

**Parameters**

- **element** ([IStiElementUI](IStiElementUI.md))  
- **** (stringdataPaths)  

**Returns** bool


---

#### IsVariablesExistInBindings `static`

**IsVariablesExistInBindings**(**element**: [IStiElementUI](IStiElementUI.md), ****: IStiAppVariablevariables): bool

**Parameters**

- **element** ([IStiElementUI](IStiElementUI.md))  
- **** (IStiAppVariablevariables)  

**Returns** bool


---

#### IsVariablesExistInExpression `static`

**IsVariablesExistInExpression**(**element**: [IStiElementUI](IStiElementUI.md), ****: IStiAppVariablevariables): bool

**Parameters**

- **element** ([IStiElementUI](IStiElementUI.md))  
- **** (IStiAppVariablevariables)  

**Returns** bool


---

#### ParseBoolExpression `static`

**ParseBoolExpression**(**component**: StiComponent, **propName**: string, **allowDataLoading**: bool): bool

**Parameters**

- **component** (StiComponent)  
- **propName** (string)  
- **allowDataLoading** (bool)  

**Returns** bool


---

#### ParseBoolExpressionOrDefault `static`

**ParseBoolExpressionOrDefault**(**comp**: StiComponent, **propName**: string, **defaultValue**: bool, **allowDataLoading**: bool): bool

**Parameters**

- **comp** (StiComponent)  
- **propName** (string)  
- **defaultValue** (bool)  
- **allowDataLoading** (bool)  

**Returns** bool


---

#### ParseBrushExpression `static`

**ParseBrushExpression**(**component**: StiComponent, **propName**: string, **allowDataLoading**: bool): [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)

**Parameters**

- **component** (StiComponent)  
- **propName** (string)  
- **allowDataLoading** (bool)  

**Returns** [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)


---

#### ParseColorExpression `static`

**ParseColorExpression**(**component**: StiComponent, **propName**: string, **allowDataLoading**: bool): Color

**Parameters**

- **component** (StiComponent)  
- **propName** (string)  
- **allowDataLoading** (bool)  

**Returns** Color


---

#### ParseColorExpressionOrDefault `static`

**ParseColorExpressionOrDefault**(**comp**: StiComponent, **propName**: string, **defaultValue**: Color, **allowDataLoading**: bool): Color

**Parameters**

- **comp** (StiComponent)  
- **propName** (string)  
- **defaultValue** (Color)  
- **allowDataLoading** (bool)  

**Returns** Color


---

#### ParseDecimalExpression `static`

**ParseDecimalExpression**(**component**: StiComponent, **propName**: string, **allowDataLoading**: bool): decimal

**Parameters**

- **component** (StiComponent)  
- **propName** (string)  
- **allowDataLoading** (bool)  

**Returns** decimal


---

#### ParseDecimalExpressionOrDefault `static`

**ParseDecimalExpressionOrDefault**(**comp**: StiComponent, **propName**: string, **defaultValue**: decimal, **allowDataLoading**: bool): decimal

**Parameters**

- **comp** (StiComponent)  
- **propName** (string)  
- **defaultValue** (decimal)  
- **allowDataLoading** (bool)  

**Returns** decimal


---

#### ParseEnumExpression `static`

**ParseEnumExpression**(**component**: StiComponent, **propName**: string, **allowDataLoading**: bool): T

**Parameters**

- **component** (StiComponent)  
- **propName** (string)  
- **allowDataLoading** (bool)  

**Returns** T

---

**ParseEnumExpression**(**component**: StiComponent, **propName**: string, **enumType**: Type, **allowDataLoading**: bool): object

**Parameters**

- **component** (StiComponent)  
- **propName** (string)  
- **enumType** (Type)  
- **allowDataLoading** (bool)  

**Returns** object


---

#### ParseEnumExpressionOrDefault `static`

**ParseEnumExpressionOrDefault**(**comp**: StiComponent, **propName**: string, **defaultValue**: T, **allowDataLoading**: bool): T

**Parameters**

- **comp** (StiComponent)  
- **propName** (string)  
- **defaultValue** (T)  
- **allowDataLoading** (bool)  

**Returns** T


---

#### ParseFloatExpression `static`

**ParseFloatExpression**(**component**: StiComponent, **propName**: string, **allowDataLoading**: bool): float

**Parameters**

- **component** (StiComponent)  
- **propName** (string)  
- **allowDataLoading** (bool)  

**Returns** float


---

#### ParseFloatExpressionOrDefault `static`

**ParseFloatExpressionOrDefault**(**comp**: StiComponent, **propName**: string, **defaultValue**: float, **allowDataLoading**: bool): float

**Parameters**

- **comp** (StiComponent)  
- **propName** (string)  
- **defaultValue** (float)  
- **allowDataLoading** (bool)  

**Returns** float


---

#### ParseFontExpression `static`

**ParseFontExpression**(**component**: StiComponent, **propName**: string, **allowDataLoading**: bool): [Font](../../Stimulsoft_Drawing/root/Font.md)

**Parameters**

- **component** (StiComponent)  
- **propName** (string)  
- **allowDataLoading** (bool)  

**Returns** [Font](../../Stimulsoft_Drawing/root/Font.md)


---

#### ParseFontExpressionOrDefault `static`

**ParseFontExpressionOrDefault**(**comp**: StiComponent, **propName**: string, **defaultValue**: [Font](../../Stimulsoft_Drawing/root/Font.md), **allowDataLoading**: bool): [Font](../../Stimulsoft_Drawing/root/Font.md)

**Parameters**

- **comp** (StiComponent)  
- **propName** (string)  
- **defaultValue** ([Font](../../Stimulsoft_Drawing/root/Font.md))  
- **allowDataLoading** (bool)  

**Returns** [Font](../../Stimulsoft_Drawing/root/Font.md)


---

#### ParseIntExpression `static`

**ParseIntExpression**(**component**: StiComponent, **propName**: string, **allowDataLoading**: bool): int

**Parameters**

- **component** (StiComponent)  
- **propName** (string)  
- **allowDataLoading** (bool)  

**Returns** int


---

#### ParseIntExpressionOrDefault `static`

**ParseIntExpressionOrDefault**(**comp**: StiComponent, **propName**: string, **defaultValue**: int, **allowDataLoading**: bool): int

**Parameters**

- **comp** (StiComponent)  
- **propName** (string)  
- **defaultValue** (int)  
- **allowDataLoading** (bool)  

**Returns** int


---

#### ParseStringExpression `static`

**ParseStringExpression**(**component**: StiComponent, **propName**: string, **allowDataLoading**: bool): string

**Parameters**

- **component** (StiComponent)  
- **propName** (string)  
- **allowDataLoading** (bool)  

**Returns** string


---

#### ParseStringExpressionOrDefault `static`

**ParseStringExpressionOrDefault**(**comp**: StiComponent, **propName**: string, **defaultValue**: string, **allowDataLoading**: bool): string

**Parameters**

- **comp** (StiComponent)  
- **propName** (string)  
- **defaultValue** (string)  
- **allowDataLoading** (bool)  

**Returns** string


---

#### ProcessExpressions `static`

**ProcessExpressions**(**obj**: object, **allowDataLoading**: bool, **eventType**: StiEventType?): void

**Parameters**

- **obj** (object)  
- **allowDataLoading** (bool)  
- **eventType** (StiEventType?)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **ErrorTime** | DateTime |  |
| **Expr** | string |  |
| **Value** | object |  |
