---
title: "UnwantedTokenException Class"
---

## UnwantedTokenException Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Inherits from: [MismatchedTokenException](MismatchedTokenException.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **UnwantedTokenException**() |  |
| **UnwantedTokenException**(string message) |  |
| **UnwantedTokenException**(string message, Exception innerException) |  |
| **UnwantedTokenException**(int expecting, [IIntStream](IIntStream.md) input) |  |
| **UnwantedTokenException**(SerializationInfo info, StreamingContext context) |  |
| **UnwantedTokenException**(int expecting, [IIntStream](IIntStream.md) input, IList<string> tokenNames) |  |
| **UnwantedTokenException**(string message, int expecting, [IIntStream](IIntStream.md) input, IList<string> tokenNames) |  |
| **UnwantedTokenException**(string message, int expecting, [IIntStream](IIntStream.md) input, IList<string> tokenNames, Exception innerException) |  |

**UnwantedTokenException**()

---

**UnwantedTokenException**(**message**: string)

**Parameters**

- **message** (string)  

---

**UnwantedTokenException**(**message**: string, **innerException**: Exception)

**Parameters**

- **message** (string)  
- **innerException** (Exception)  

---

**UnwantedTokenException**(**expecting**: int, **input**: [IIntStream](IIntStream.md))

**Parameters**

- **expecting** (int)  
- **input** ([IIntStream](IIntStream.md))  

---

**UnwantedTokenException**(**info**: SerializationInfo, **context**: StreamingContext)

**Parameters**

- **info** (SerializationInfo)  
- **context** (StreamingContext)  

---

**UnwantedTokenException**(**expecting**: int, **input**: [IIntStream](IIntStream.md), **tokenNames**: IList<string>)

**Parameters**

- **expecting** (int)  
- **input** ([IIntStream](IIntStream.md))  
- **tokenNames** (IList<string>)  

---

**UnwantedTokenException**(**message**: string, **expecting**: int, **input**: [IIntStream](IIntStream.md), **tokenNames**: IList<string>)

**Parameters**

- **message** (string)  
- **expecting** (int)  
- **input** ([IIntStream](IIntStream.md))  
- **tokenNames** (IList<string>)  

---

**UnwantedTokenException**(**message**: string, **expecting**: int, **input**: [IIntStream](IIntStream.md), **tokenNames**: IList<string>, **innerException**: Exception)

**Parameters**

- **message** (string)  
- **expecting** (int)  
- **input** ([IIntStream](IIntStream.md))  
- **tokenNames** (IList<string>)  
- **innerException** (Exception)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ToString** | string |  |

---

### Method Details

#### ToString

**ToString**(): string

**Returns** string

