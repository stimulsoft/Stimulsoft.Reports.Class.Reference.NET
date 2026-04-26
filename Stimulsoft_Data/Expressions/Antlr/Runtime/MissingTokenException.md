---
title: "MissingTokenException Class"
---

## MissingTokenException Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Inherits from: [MismatchedTokenException](MismatchedTokenException.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **MissingTokenException**() |  |
| **MissingTokenException**(string message) |  |
| **MissingTokenException**(string message, Exception innerException) |  |
| **MissingTokenException**(SerializationInfo info, StreamingContext context) |  |
| **MissingTokenException**(int expecting, [IIntStream](IIntStream.md) input, object inserted) |  |
| **MissingTokenException**(int expecting, [IIntStream](IIntStream.md) input, object inserted, IList<string> tokenNames) |  |
| **MissingTokenException**(string message, int expecting, [IIntStream](IIntStream.md) input, object inserted, IList<string> tokenNames) |  |
| **MissingTokenException**(string message, int expecting, [IIntStream](IIntStream.md) input, object inserted, IList<string> tokenNames, Exception innerException) |  |

**MissingTokenException**()

---

**MissingTokenException**(**message**: string)

**Parameters**

- **message** (string)  

---

**MissingTokenException**(**message**: string, **innerException**: Exception)

**Parameters**

- **message** (string)  
- **innerException** (Exception)  

---

**MissingTokenException**(**info**: SerializationInfo, **context**: StreamingContext)

**Parameters**

- **info** (SerializationInfo)  
- **context** (StreamingContext)  

---

**MissingTokenException**(**expecting**: int, **input**: [IIntStream](IIntStream.md), **inserted**: object)

**Parameters**

- **expecting** (int)  
- **input** ([IIntStream](IIntStream.md))  
- **inserted** (object)  

---

**MissingTokenException**(**expecting**: int, **input**: [IIntStream](IIntStream.md), **inserted**: object, **tokenNames**: IList<string>)

**Parameters**

- **expecting** (int)  
- **input** ([IIntStream](IIntStream.md))  
- **inserted** (object)  
- **tokenNames** (IList<string>)  

---

**MissingTokenException**(**message**: string, **expecting**: int, **input**: [IIntStream](IIntStream.md), **inserted**: object, **tokenNames**: IList<string>)

**Parameters**

- **message** (string)  
- **expecting** (int)  
- **input** ([IIntStream](IIntStream.md))  
- **inserted** (object)  
- **tokenNames** (IList<string>)  

---

**MissingTokenException**(**message**: string, **expecting**: int, **input**: [IIntStream](IIntStream.md), **inserted**: object, **tokenNames**: IList<string>, **innerException**: Exception)

**Parameters**

- **message** (string)  
- **expecting** (int)  
- **input** ([IIntStream](IIntStream.md))  
- **inserted** (object)  
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

