---
title: "StiToken Class"
---

## StiToken Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

Class describes Token.

```csharp
public class StiToken
```

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiToken([StiTokenType](StiTokenType.md) type)` | Create a new instance StiToken. |
| `StiToken([StiTokenType](StiTokenType.md) type, int index, int length)` | Creates a new object of the type StiToken. |
| `StiToken([StiTokenType](StiTokenType.md) type, int index, int length, char charValue)` | Creates a new object of the type StiToken. |
| `StiToken([StiTokenType](StiTokenType.md) type, int index, int length, string stringValue)` | Creates an object of the type StiToken that contains the value of the string. |
| `StiToken([StiTokenType](StiTokenType.md) type, int index, int length, object obj)` | Creates an object of the type StiToken that contains an object. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Data** | object | Gets or sets Value of the identifier. |
| **Index** | int | Gets or sets value indicates the beginning of token in text. |
| **Length** | int | Gets or sets value indicates the length of token. |
| **Type** | [StiTokenType](StiTokenType.md) | Gets or sets value indicates the type of token. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **IsAssign** | bool |  |
| **IsDot** | bool |  |
| **IsIdent** | bool |  |
| **IsIdentOrKeyword** | bool |  |
| **IsKeyword** | bool |  |
| **IsLBrace** | bool |  |
| **IsLBracket** | bool |  |
| **IsLPar** | bool |  |
| **IsRBrace** | bool |  |
| **IsRBracket** | bool |  |
| **IsRPar** | bool |  |
| **ToString** | string |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DataAsString** | string |  |
| **EOF** | [StiToken](StiToken.md) |  |
