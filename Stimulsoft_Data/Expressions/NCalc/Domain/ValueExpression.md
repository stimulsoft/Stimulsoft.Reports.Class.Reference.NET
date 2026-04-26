---
title: "ValueExpression Class"
---

## ValueExpression Class

**Namespace:** `Stimulsoft.Data.Expressions.NCalc.Domain`

### Inheritance

Inherits from: [LogicalExpression](LogicalExpression.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **ValueExpression**(object value) |  |
| **ValueExpression**(string value) |  |
| **ValueExpression**(int value) |  |
| **ValueExpression**(float value) |  |
| **ValueExpression**(DateTime value) |  |
| **ValueExpression**(bool value) |  |
| **ValueExpression**(object value, [ValueType](ValueType.md) type) |  |

**ValueExpression**(**value**: object)

**Parameters**

- **value** (object)  

---

**ValueExpression**(**value**: string)

**Parameters**

- **value** (string)  

---

**ValueExpression**(**value**: int)

**Parameters**

- **value** (int)  

---

**ValueExpression**(**value**: float)

**Parameters**

- **value** (float)  

---

**ValueExpression**(**value**: DateTime)

**Parameters**

- **value** (DateTime)  

---

**ValueExpression**(**value**: bool)

**Parameters**

- **value** (bool)  

---

**ValueExpression**(**value**: object, **type**: [ValueType](ValueType.md))

**Parameters**

- **value** (object)  
- **type** ([ValueType](ValueType.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Type** | [ValueType](ValueType.md) |  |
| **Value** | object |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Accept** | void |  |

---

### Method Details

#### Accept

**Accept**(**visitor**: [LogicalExpressionVisitor](LogicalExpressionVisitor.md)): void

**Parameters**

- **visitor** ([LogicalExpressionVisitor](LogicalExpressionVisitor.md))  

