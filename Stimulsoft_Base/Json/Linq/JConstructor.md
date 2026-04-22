---
title: "JConstructor Class"
---

## JConstructor Class

**Namespace:** `Stimulsoft.Base.Json.Linq`  
**Assembly:** `Stimulsoft.Base`

Represents a JSON constructor.

```csharp
public class JConstructor
```

### Inheritance

Inherits from: [JContainer](JContainer.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **JConstructor**() | Initializes a new instance of the JConstructor class. |
| **JConstructor**([JConstructor](JConstructor.md) other) | Initializes a new instance of the JConstructor class from another JConstructor object. |
| **JConstructor**(string name) | Initializes a new instance of the JConstructor class with the specified name. |
| **JConstructor**(string name, objectcontent ) | Initializes a new instance of the JConstructor class with the specified name and content. |
| **JConstructor**(string name, object content) | Initializes a new instance of the JConstructor class with the specified name and content. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Load** `static` | [JConstructor](JConstructor.md) | Loads an JConstructor from a JsonReader. |
| **WriteTo** | void | Writes this token to a JsonWriter. |
