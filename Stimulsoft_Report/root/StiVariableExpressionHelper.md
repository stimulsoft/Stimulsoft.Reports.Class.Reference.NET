---
title: "StiVariableExpressionHelper Class"
---

## StiVariableExpressionHelper Class

**Namespace:** `Stimulsoft.Report`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ExtractVariableName** `static` | string |  |
| **GetSimpleName** `static` | string |  |
| **GetVariableSpecifiedAsExpression** `static` | [IStiAppVariable](../../Stimulsoft_Base/root/IStiAppVariable.md) |  |
| **IsVariableSpecifiedAsExpression** `static` | bool |  |

---

### Method Details

#### ExtractVariableName `static`

**ExtractVariableName**(**exp**: string): string

**Parameters**

- **exp** (string)  

**Returns** string


---

#### GetSimpleName `static`

**GetSimpleName**(**name**: string): string

**Parameters**

- **name** (string)  

**Returns** string


---

#### GetVariableSpecifiedAsExpression `static`

**GetVariableSpecifiedAsExpression**(**element**: IStiElement, **expression**: string): [IStiAppVariable](../../Stimulsoft_Base/root/IStiAppVariable.md)

**Parameters**

- **element** (IStiElement)  
- **expression** (string)  

**Returns** [IStiAppVariable](../../Stimulsoft_Base/root/IStiAppVariable.md)


---

#### IsVariableSpecifiedAsExpression `static`

**IsVariableSpecifiedAsExpression**(**element**: IStiElement, **expression**: string): bool

**Parameters**

- **element** (IStiElement)  
- **expression** (string)  

**Returns** bool


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **ParserCompId** | string |  |
