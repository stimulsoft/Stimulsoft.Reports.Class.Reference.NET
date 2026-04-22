---
title: "JProperty Class"
---

## JProperty Class

**Namespace:** `Stimulsoft.Base.Json.Linq`  
**Assembly:** `Stimulsoft.Base`

Represents a JSON property.

```csharp
public class JProperty
```

### Inheritance

Inherits from: [JContainer](JContainer.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `JProperty([JProperty](JProperty.md) other)` | Initializes a new instance of the JProperty class from another JProperty object. |
| `JProperty(string name, objectcontent )` | Initializes a new instance of the JProperty class. |
| `JProperty(string name, object content)` | Initializes a new instance of the JProperty class. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** | void |  |
| **Clear** | void |  |
| **Contains** | bool |  |
| **CopyTo** | void |  |
| **GetEnumerator** | IEnumerator<[JToken](JToken.md)> |  |
| **IndexOf** | int |  |
| **Insert** | void |  |
| **Load** `static` | [JProperty](JProperty.md) | Loads an JProperty from a JsonReader. |
| **Remove** | bool |  |
| **RemoveAt** | void |  |
| **WriteTo** | void | Writes this token to a JsonWriter. |
