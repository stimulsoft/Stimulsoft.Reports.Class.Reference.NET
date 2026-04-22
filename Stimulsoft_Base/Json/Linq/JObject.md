---
title: "JObject Class"
---

## JObject Class

**Namespace:** `Stimulsoft.Base.Json.Linq`  
**Assembly:** `Stimulsoft.Base`

Represents a JSON object.

```csharp
public class JObject
```

### Inheritance

Inherits from: [JContainer](JContainer.md)  
Implements: IDictionary<string, [JToken](JToken.md)>, INotifyPropertyChanged  

### Constructors

| Constructor | Description |
| --- | --- |
| **JObject**() | Initializes a new instance of the JObject class. |
| **JObject**([JObject](JObject.md) other) | Initializes a new instance of the JObject class from another JObject object. |
| **JObject**(objectcontent ) | Initializes a new instance of the JObject class with the specified content. |
| **JObject**(object content) | Initializes a new instance of the JObject class with the specified content. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** | void | Adds the specified property name. |
| **ContainsKey** | bool | Determines whether the JSON object has the specified property name. |
| **FromObject** `static` *(+1 overloads)* | [JObject](JObject.md) | Creates a JObject from an object. |
| **GetDynamicMemberNames** | IEnumerable<string> |  |
| **GetMetaObject** | DynamicMetaObject | Returns the DynamicMetaObject responsible for binding operations performed on this object. |
| **GetValue** *(+1 overloads)* | [JToken](JToken.md) | Gets the JToken with the specified property name. |
| **Load** `static` | [JObject](JObject.md) | Loads an JObject from a JsonReader. |
| **OnPropertyChanged** | void | Raises the PropertyChanged event with the provided arguments. |
| **OnPropertyChanging** | void | Raises the PropertyChanging event with the provided arguments. |
| **Parse** `static` | [JObject](JObject.md) | Load a JObject from a string that contains JSON. |
| **Properties** | IEnumerable<[JProperty](JProperty.md)> | Gets an IEnumerable{JProperty} of this object's properties. |
| **Property** | [JProperty](JProperty.md) | Gets a JProperty the specified name. |
| **PropertyValues** | [JEnumerable](JEnumerable.md)<[JToken](JToken.md)> | Gets an JEnumerable{JToken} of this object's property values. |
| **Remove** | bool | Removes the property with the specified name. |
| **TryGetMember** | bool |  |
| **TryGetValue** *(+1 overloads)* | bool | Tries to get the JToken with the specified property name. The exact property name will be searched for first and if no matching property is found then the StringComparison will be used to match a property. |
| **TrySetMember** | bool |  |
| **WriteTo** | void | Writes this token to a JsonWriter. |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **PropertyChanged** | PropertyChangedEventHandler | Occurs when a property value changes. |
| **PropertyChanging** | PropertyChangingEventHandler | Occurs when a property value is changing. |
