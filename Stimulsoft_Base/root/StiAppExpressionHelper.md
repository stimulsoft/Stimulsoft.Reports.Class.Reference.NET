---
title: "StiAppExpressionHelper Class"
---

## StiAppExpressionHelper Class

**Namespace:** `Stimulsoft.Base`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetExpression** `static` | StiAppExpression |  |
| **GetExpressionFromInstance** `static` *(+1 overloads)* | string | Returns an expression if specified from the context object. Returns null if the expression is not specified. |
| **GetExpressionValue** `static` | string |  |
| **IsExpressionSpecified** `static` | bool |  |
| **RemoveExpression** `static` | void |  |
| **SetExpression** `static` | void |  |

---

### Method Details

#### GetExpression `static`

**GetExpression**(**component**: object, **propName**: string): StiAppExpression

**Parameters**

- **component** (object)  
- **propName** (string)  

**Returns** StiAppExpression


---

#### GetExpressionFromInstance `static`

**GetExpressionFromInstance**(**context**: ITypeDescriptorContext): string

Returns an expression if specified from the context object. Returns null if the expression is not specified.

**Parameters**

- **context** (ITypeDescriptorContext)  

**Returns** string

---

**GetExpressionFromInstance**(**instance**: object, **propertyName**: string): string

Returns and expression if specified from the specified instance and the property name. Returns null if the expression is not specified.

**Parameters**

- **instance** (object)  
- **propertyName** (string)  

**Returns** string


---

#### GetExpressionValue `static`

**GetExpressionValue**(**component**: object, **propName**: string): string

**Parameters**

- **component** (object)  
- **propName** (string)  

**Returns** string


---

#### IsExpressionSpecified `static`

**IsExpressionSpecified**(**component**: object, **propName**: string): bool

**Parameters**

- **component** (object)  
- **propName** (string)  

**Returns** bool


---

#### RemoveExpression `static`

**RemoveExpression**(**component**: object, **propName**: string): void

**Parameters**

- **component** (object)  
- **propName** (string)  


---

#### SetExpression `static`

**SetExpression**(**component**: object, **propName**: string, **expression**: string): void

**Parameters**

- **component** (object)  
- **propName** (string)  
- **expression** (string)  

