---
title: "EarlyExitException Class"
---

## EarlyExitException Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Inherits from: [RecognitionException](RecognitionException.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **EarlyExitException**() |  |
| **EarlyExitException**(string message) |  |
| **EarlyExitException**(string message, Exception innerException) |  |
| **EarlyExitException**(int decisionNumber, [IIntStream](IIntStream.md) input) |  |
| **EarlyExitException**(SerializationInfo info, StreamingContext context) |  |
| **EarlyExitException**(string message, int decisionNumber, [IIntStream](IIntStream.md) input) |  |
| **EarlyExitException**(string message, int decisionNumber, [IIntStream](IIntStream.md) input, Exception innerException) |  |

**EarlyExitException**()

---

**EarlyExitException**(**message**: string)

**Parameters**

- **message** (string)  

---

**EarlyExitException**(**message**: string, **innerException**: Exception)

**Parameters**

- **message** (string)  
- **innerException** (Exception)  

---

**EarlyExitException**(**decisionNumber**: int, **input**: [IIntStream](IIntStream.md))

**Parameters**

- **decisionNumber** (int)  
- **input** ([IIntStream](IIntStream.md))  

---

**EarlyExitException**(**info**: SerializationInfo, **context**: StreamingContext)

**Parameters**

- **info** (SerializationInfo)  
- **context** (StreamingContext)  

---

**EarlyExitException**(**message**: string, **decisionNumber**: int, **input**: [IIntStream](IIntStream.md))

**Parameters**

- **message** (string)  
- **decisionNumber** (int)  
- **input** ([IIntStream](IIntStream.md))  

---

**EarlyExitException**(**message**: string, **decisionNumber**: int, **input**: [IIntStream](IIntStream.md), **innerException**: Exception)

**Parameters**

- **message** (string)  
- **decisionNumber** (int)  
- **input** ([IIntStream](IIntStream.md))  
- **innerException** (Exception)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetObjectData** | void |  |

---

### Method Details

#### GetObjectData

**GetObjectData**(**info**: SerializationInfo, **context**: StreamingContext): void

**Parameters**

- **info** (SerializationInfo)  
- **context** (StreamingContext)  

