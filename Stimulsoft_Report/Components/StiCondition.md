---
title: "StiCondition Class"
---

## StiCondition Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: [StiBaseCondition](StiBaseCondition.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCondition**() | Creates a new object of the type StiCondition. |
| **StiCondition**(string expression, Color textColor, Color backColor, [Font](../../Stimulsoft_Drawing/root/Font.md) font, bool enabled) | Creates a new object of the type StiCondition. |

**StiCondition**()

Creates a new object of the type StiCondition.

---

**StiCondition**(**expression**: string, **textColor**: Color, **backColor**: Color, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **enabled**: bool)

Creates a new object of the type StiCondition.

**Parameters**

- **expression** (string)  
- **textColor** (Color)  
- **backColor** (Color)  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  
- **enabled** (bool)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AssignExpression** | string |  |
| **BackColor** | Color |  |
| **BreakIfTrue** | bool |  |
| **CanAssignExpression** | bool |  |
| **Enabled** | bool |  |
| **Font** | [Font](../../Stimulsoft_Drawing/root/Font.md) |  |
| **Icon** | byte[] |  |
| **IconSize** | Size? |  |
| **Permissions** | [StiConditionPermissions](StiConditionPermissions.md) |  |
| **Style** | string |  |
| **TextColor** | Color |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Equals** | bool |  |
| **GetFonts** | List<[StiFont](../../Stimulsoft_Base/root/StiFont.md)> |  |
| **GetHashCode** | int |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Clone

**Clone**(): object

Creates a new object that is a copy of the current instance.

**Returns** object — A new object that is a copy of this instance.


---

#### Equals

**Equals**(**obj**: object): bool

**Parameters**

- **obj** (object)  

**Returns** bool


---

#### GetFonts

**GetFonts**(): List<[StiFont](../../Stimulsoft_Base/root/StiFont.md)>

**Returns** List<[StiFont](../../Stimulsoft_Base/root/StiFont.md)>


---

#### GetHashCode

**GetHashCode**(): int

**Returns** int


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **IconAlignment** | ContentAlignment |  |
