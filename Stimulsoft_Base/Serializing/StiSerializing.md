---
title: "StiSerializing Class"
---

## StiSerializing Class

**Namespace:** `Stimulsoft.Base.Serializing`

This class contains methods of serialization and deserialization.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSerializing**() | Creates a new instance of the StiSerializing class. |
| **StiSerializing**([StiObjectStringConverter](../root/StiObjectStringConverter.md) converter) | Creates a new instance of the StiSerializing class. |

**StiSerializing**()

Creates a new instance of the StiSerializing class.

---

**StiSerializing**(**converter**: [StiObjectStringConverter](../root/StiObjectStringConverter.md))

Creates a new instance of the StiSerializing class.

**Parameters**

- **converter** ([StiObjectStringConverter](../root/StiObjectStringConverter.md)) — Converter for transformation of objects into the string and back.  


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

---

### Method Details

#### AddSourceTypeToDestinationType `static`

**AddSourceTypeToDestinationType**(**typeDestination**: string, **typeSource**: string): void

Adds the string representation of type for type conversation.

**Parameters**

- **typeDestination** (string)  
- **typeSource** (string)  


---

#### AddStringProperty

**AddStringProperty**(**property**: string, **str**: string): void

Adds the name of the property and its string substitution.

**Parameters**

- **property** (string)  
- **str** (string)  


---

#### AddStringType `static`

**AddStringType**(**type**: Type, **str**: string): void

Adds the type and its string substitution.

**Parameters**

- **type** (Type)  
- **str** (string)  


---

#### ClearPropertyString

**ClearPropertyString**(): void

Clears the hashtable of strings-properties.


---

#### ClearStringType `static`

**ClearStringType**(): void

Clears the hashtable of strings-types.


---

#### Deserialize

**Deserialize**(**obj**: object, **stream**: Stream, **application**: string): void

Deserializes object from the stream.

**Parameters**

- **obj** (object) — Object for deserialization.  
- **stream** (Stream) — Stream from which deserialization is generated.  
- **application** (string) — Application that generates deserialization.  

---

**Deserialize**(**obj**: object, **textReader**: TextReader, **application**: string): void

Deserializes object using textReader.

**Parameters**

- **obj** (object) — Object for deserialization.  
- **textReader** (TextReader) — TextReader from which deserialization will be generated.  
- **application** (string) — Application that generates deserialization.  

---

**Deserialize**(**obj**: object, **path**: string, **application**: string): void

Deserializes object from the file.

**Parameters**

- **obj** (object) — Object for deserialization.  
- **path** (string) — File from which deserialization will be generated.  
- **application** (string) — Application that generates deserialization.  


---

#### GetDefaultValue

**GetDefaultValue**(**prop**: MemberDescriptor): object

Returns the value to default for property. If the value is not assigned by default then null returns.

**Parameters**

- **prop** (MemberDescriptor) — Descriptor.  

**Returns** object — Default.


---

#### GetPropertyFromString

**GetPropertyFromString**(**str**: string): string

Returns the property name from string-substitution.

**Parameters**

- **str** (string)  

**Returns** string


---

#### GetStringFromProperty

**GetStringFromProperty**(**propertyName**: string): string

Returns the string substitution for a property name.

**Parameters**

- **propertyName** (string)  

**Returns** string


---

#### GetTypeOfArrayElement `static`

**GetTypeOfArrayElement**(**array**: object): Type

Returns the type of elements in the array or collection.

**Parameters**

- **array** (object) — Array or collection.  

**Returns** Type — Element type.


---

#### InvokeDeserializing

**InvokeDeserializing**(): void

Raises the Deserializing event for this control.


---

#### InvokeGlobalDeserializing `static`

**InvokeGlobalDeserializing**(**sender**: object, **e**: EventArgs): void

**Parameters**

- **sender** (object)  
- **e** (EventArgs)  


---

#### InvokeGlobalSerializing `static`

**InvokeGlobalSerializing**(**sender**: object, **e**: EventArgs): void

**Parameters**

- **sender** (object)  
- **e** (EventArgs)  


---

#### InvokeSerializing

**InvokeSerializing**(): void

Raises the Serializing event for this control.


---

#### IsContent

**IsContent**(**obj**: object): bool

Returns true if the object is marked as a content.

**Parameters**

- **obj** (object) — Object for check.  

**Returns** bool — Result of check.


---

#### OnDeserializing

**OnDeserializing**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


---

#### OnSerializing

**OnSerializing**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


---

#### Serialize

**Serialize**(**obj**: object, **serializeType**: [StiSerializeTypes](StiSerializeTypes.md)): [StiPropertyInfoCollection](StiPropertyInfoCollection.md)

Serialize an object into the list.

**Parameters**

- **obj** (object) — Object for serialization.  
- **serializeType** ([StiSerializeTypes](StiSerializeTypes.md)) — Serialization type.  

**Returns** [StiPropertyInfoCollection](StiPropertyInfoCollection.md) — Serialized objects list.

---

**Serialize**(**obj**: object, **stream**: Stream, **application**: string): void

Serializes an object into the stream.

**Parameters**

- **obj** (object) — Object for serialization.  
- **stream** (Stream) — Stream in which serialization will be generated.  
- **application** (string) — Application that generates serialization.  

---

**Serialize**(**obj**: object, **stream**: Stream, **application**: string, **serializeType**: [StiSerializeTypes](StiSerializeTypes.md)): void

Serializes object into the stream.

**Parameters**

- **obj** (object) — Object for serialization.  
- **stream** (Stream) — Stream in which serialization will be generated.  
- **application** (string) — Application that generates serialization.  
- **serializeType** ([StiSerializeTypes](StiSerializeTypes.md)) — Serialization type.  

---

**Serialize**(**obj**: object, **path**: string, **application**: string): void

Serializes object into the file.

**Parameters**

- **obj** (object) — Object for serialization.  
- **path** (string) — File in which serialization will be generated.  
- **application** (string) — Application that generates serialization.  


---

#### SerializeControl

**SerializeControl**(**obj**: Control, **serializeType**: [StiSerializeTypes](StiSerializeTypes.md)): [StiPropertyInfoCollection](StiPropertyInfoCollection.md)

**Parameters**

- **obj** (Control)  
- **serializeType** ([StiSerializeTypes](StiSerializeTypes.md))  

**Returns** [StiPropertyInfoCollection](StiPropertyInfoCollection.md)


---

#### SerializeObject

**SerializeObject**(**obj**: object, **serializeType**: [StiSerializeTypes](StiSerializeTypes.md)): [StiPropertyInfoCollection](StiPropertyInfoCollection.md)

Serilizes an object into the list.

**Parameters**

- **obj** (object) — Object for serialization.  
- **serializeType** ([StiSerializeTypes](StiSerializeTypes.md)) — Serialization type.  

**Returns** [StiPropertyInfoCollection](StiPropertyInfoCollection.md) — List of serialized objects.

---

**SerializeObject**(**tw**: XmlTextWriter, **props**: [StiPropertyInfoCollection](StiPropertyInfoCollection.md)): void

Saves the list serialized objects into XML.

**Parameters**

- **tw** (XmlTextWriter) — Object to save into XML  
- **props** ([StiPropertyInfoCollection](StiPropertyInfoCollection.md)) — Serialized objects list.  


---

#### SetProperty

**SetProperty**(**p**: PropertyInfo, **obj**: object, **value**: object): void

Sets property p in object obj value.

**Parameters**

- **p** (PropertyInfo) — Property for set.  
- **obj** (object) — Object in which the property is situated.  
- **value** (object) — Value for setup.  


---

#### SetReferenceDeserializing

**SetReferenceDeserializing**(): void

Sets delayed references for serialization.


---

#### SetReferenceSerializing

**SetReferenceSerializing**(): void

Sets delayed references for serialization.


### Events

| Event | Type | Description |
| --- | --- | --- |
| **Deserializing** | EventHandler | Event occurs when deserializing of one element. |
| **GlobalDeserializing** | EventHandler |  |
| **GlobalSerializing** | EventHandler |  |
| **PropertyNotFound** | StiPropertyNotFoundEventHandlers |  |
| **Serializing** | EventHandler | Event occurs when serializing of one element. |
| **TypeNotFound** | StiTypeNotFoundEventHandler |  |
