---
title: "ANTLRReaderStream Class"
---

## ANTLRReaderStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Inherits from: [ANTLRStringStream](ANTLRStringStream.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **ANTLRReaderStream**(TextReader r) |  |
| **ANTLRReaderStream**(TextReader r, int size) |  |
| **ANTLRReaderStream**(TextReader r, int size, int readChunkSize) |  |

**ANTLRReaderStream**(**r**: TextReader)

**Parameters**

- **r** (TextReader)  

---

**ANTLRReaderStream**(**r**: TextReader, **size**: int)

**Parameters**

- **r** (TextReader)  
- **size** (int)  

---

**ANTLRReaderStream**(**r**: TextReader, **size**: int, **readChunkSize**: int)

**Parameters**

- **r** (TextReader)  
- **size** (int)  
- **readChunkSize** (int)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Load** | void |  |

---

### Method Details

#### Load

**Load**(**r**: TextReader, **size**: int, **readChunkSize**: int): void

**Parameters**

- **r** (TextReader)  
- **size** (int)  
- **readChunkSize** (int)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **InitialBufferSize** | int |  |
| **ReadBufferSize** | int |  |
