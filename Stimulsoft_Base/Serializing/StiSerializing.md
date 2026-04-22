---
title: "StiSerializing Class"
---

## StiSerializing Class

**Namespace:** `Stimulsoft.Base.Serializing`  
**Assembly:** `Stimulsoft.Base`

This class contains methods of serialization and deserialization.

```csharp
public class StiSerializing
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiSerializing()` | Creates a new instance of the StiSerializing class. |
| `StiSerializing([StiObjectStringConverter](../StiObjectStringConverter.md) converter)` | Creates a new instance of the StiSerializing class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowFixOldChartTitle** `static` | bool | Gets or sets value which indicates that bug with loading old charts (without Direction property) will be fixed during loading of report. |
| **CheckSerializable** | bool | Gets or sets value, indicates should objects, when serialization, be checked in their capability or not to realize IStiSerializable. |
| **IgnoreSerializableForContainer** | bool | Internal use only. |
| **IsDocument** | bool | Gets or sets a value indicates Document mode. |
| **SortProperties** | bool | Gets or sets value indicates should properties be sorted alphabetically or not. |
| **SourceTypeToDestinationType** `static` | Hashtable |  |
| **StringToType** `static` | Hashtable | Gets or sets table for transformation a string into the type. |
| **ThrowExceptionOnContentMismatch** `static` | bool | If true than throws an exception if a content of deserializing file is mismatch. |
| **TypeToString** `static` | Hashtable | Gets or sets table for transformation of a type into the string. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddSourceTypeToDestinationType** `static` | void | Adds the string representation of type for type conversation. |
| **AddStringProperty** | void | Adds the name of the property and its string substitution. |
| **AddStringType** `static` | void | Adds the type and its string substitution. |
| **ClearPropertyString** | void | Clears the hashtable of strings-properties. |
| **ClearStringType** `static` | void | Clears the hashtable of strings-types. |
| **Deserialize** *(+2 overloads)* | void | Deserializes object from the stream. |
| **GetDefaultValue** | object | Returns the value to default for property. If the value is not assigned by default then null returns. |
| **GetPropertyFromString** | string | Returns the property name from string-substitution. |
| **GetStringFromProperty** | string | Returns the string substitution for a property name. |
| **GetTypeOfArrayElement** `static` | Type | Returns the type of elements in the array or collection. |
| **InvokeDeserializing** | void | Raises the Deserializing event for this control. |
| **InvokeGlobalDeserializing** `static` | void |  |
| **InvokeGlobalSerializing** `static` | void |  |
| **InvokeSerializing** | void | Raises the Serializing event for this control. |
| **IsContent** | bool | Returns true if the object is marked as a content. |
| **OnDeserializing** | void |  |
| **OnSerializing** | void |  |
| **Serialize** *(+3 overloads)* | [StiPropertyInfoCollection](StiPropertyInfoCollection.md) | Serialize an object into the list. |
| **SerializeControl** | [StiPropertyInfoCollection](StiPropertyInfoCollection.md) |  |
| **SerializeObject** *(+1 overloads)* | [StiPropertyInfoCollection](StiPropertyInfoCollection.md) | Serilizes an object into the list. |
| **SetProperty** | void | Sets property p in object obj value. |
| **SetReferenceDeserializing** | void | Sets delayed references for serialization. |
| **SetReferenceSerializing** | void | Sets delayed references for serialization. |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **Deserializing** | EventHandler | Event occurs when deserializing of one element. |
| **GlobalDeserializing** | EventHandler |  |
| **GlobalSerializing** | EventHandler |  |
| **PropertyNotFound** | StiPropertyNotFoundEventHandlers |  |
| **Serializing** | EventHandler | Event occurs when serializing of one element. |
| **TypeNotFound** | StiTypeNotFoundEventHandler |  |
