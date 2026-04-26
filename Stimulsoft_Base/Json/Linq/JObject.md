---
title: "JObject Class"
---

## JObject Class

**Namespace:** `Stimulsoft.Base.Json.Linq`

Represents a JSON object.

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

**JObject**()

Initializes a new instance of the JObject class.

---

**JObject**(**other**: [JObject](JObject.md))

Initializes a new instance of the JObject class from another JObject object.

**Parameters**

- **other** ([JObject](JObject.md)) — A JObject object to copy from.  

---

**JObject**(****: objectcontent)

Initializes a new instance of the JObject class with the specified content.

**Parameters**

- **** (objectcontent)  

---

**JObject**(**content**: object)

Initializes a new instance of the JObject class with the specified content.

**Parameters**

- **content** (object) — The contents of the object.  


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

---

### Method Details

#### Add

**Add**(**propertyName**: string, **value**: [JToken](JToken.md)): void

Adds the specified property name.

**Parameters**

- **propertyName** (string) — Name of the property.  
- **value** ([JToken](JToken.md)) — The value.  


---

#### ContainsKey

**ContainsKey**(**propertyName**: string): bool

Determines whether the JSON object has the specified property name.

**Parameters**

- **propertyName** (string) — Name of the property.  

**Returns** bool — `true` if the JSON object has the specified property name; otherwise, `false`.


---

#### FromObject `static`

**FromObject**(**o**: object): [JObject](JObject.md)

Creates a JObject from an object.

**Parameters**

- **o** (object) — The object that will be used to create JObject.  

**Returns** [JObject](JObject.md) — A JObject with the values of the specified object

---

**FromObject**(**o**: object, **jsonSerializer**: [JsonSerializer](../../Json2/JsonSerializer.md)): [JObject](JObject.md)

Creates a JObject from an object.

**Parameters**

- **o** (object) — The object that will be used to create JObject.  
- **jsonSerializer** ([JsonSerializer](../../Json2/JsonSerializer.md)) — The JsonSerializer that will be used to read the object.  

**Returns** [JObject](JObject.md) — A JObject with the values of the specified object


---

#### GetDynamicMemberNames

**GetDynamicMemberNames**(**instance**: [JObject](JObject.md)): IEnumerable<string>

**Parameters**

- **instance** ([JObject](JObject.md))  

**Returns** IEnumerable<string>


---

#### GetMetaObject

**GetMetaObject**(**parameter**: [Expression](../../../Stimulsoft_Data/Expressions/NCalc/Expression.md)): DynamicMetaObject

Returns the DynamicMetaObject responsible for binding operations performed on this object.

**Parameters**

- **parameter** ([Expression](../../../Stimulsoft_Data/Expressions/NCalc/Expression.md)) — The expression tree representation of the runtime value.  

**Returns** DynamicMetaObject — The DynamicMetaObject to bind this object.


---

#### GetValue

**GetValue**(**propertyName**: string): [JToken](JToken.md)

Gets the JToken with the specified property name.

**Parameters**

- **propertyName** (string) — Name of the property.  

**Returns** [JToken](JToken.md) — The JToken with the specified property name.

---

**GetValue**(**propertyName**: string, **comparison**: StringComparison): [JToken](JToken.md)

Gets the JToken with the specified property name. The exact property name will be searched for first and if no matching property is found then the StringComparison will be used to match a property.

**Parameters**

- **propertyName** (string) — Name of the property.  
- **comparison** (StringComparison) — One of the enumeration values that specifies how the strings will be compared.  

**Returns** [JToken](JToken.md) — The JToken with the specified property name.


---

#### Load `static`

**Load**(**reader**: [JsonReader](../JsonReader.md)): [JObject](JObject.md)

Loads an JObject from a JsonReader.

**Parameters**

- **reader** ([JsonReader](../JsonReader.md)) — A JsonReader that will be read for the content of the JObject.  

**Returns** [JObject](JObject.md) — A JObject that contains the JSON that was read from the specified JsonReader.


---

#### OnPropertyChanged

**OnPropertyChanged**(**propertyName**: string): void

Raises the PropertyChanged event with the provided arguments.

**Parameters**

- **propertyName** (string) — Name of the property.  


---

#### OnPropertyChanging

**OnPropertyChanging**(**propertyName**: string): void

Raises the PropertyChanging event with the provided arguments.

**Parameters**

- **propertyName** (string) — Name of the property.  


---

#### Parse `static`

**Parse**(**json**: string): [JObject](JObject.md)

Load a JObject from a string that contains JSON.

**Parameters**

- **json** (string) — A String that contains JSON.  

**Returns** [JObject](JObject.md) — A JObject populated from the string that contains JSON.


---

#### Properties

**Properties**(): IEnumerable<[JProperty](JProperty.md)>

Gets an IEnumerable{JProperty} of this object's properties.

**Returns** IEnumerable<[JProperty](JProperty.md)> — An IEnumerable{JProperty} of this object's properties.


---

#### Property

**Property**(**name**: string): [JProperty](JProperty.md)

Gets a JProperty the specified name.

**Parameters**

- **name** (string) — The property name.  

**Returns** [JProperty](JProperty.md) — A JProperty with the specified name or null.


---

#### PropertyValues

**PropertyValues**(): [JEnumerable](JEnumerable.md)<[JToken](JToken.md)>

Gets an JEnumerable{JToken} of this object's property values.

**Returns** [JEnumerable](JEnumerable.md)<[JToken](JToken.md)> — An JEnumerable{JToken} of this object's property values.


---

#### Remove

**Remove**(**propertyName**: string): bool

Removes the property with the specified name.

**Parameters**

- **propertyName** (string) — Name of the property.  

**Returns** bool — true if item was successfully removed; otherwise, false.


---

#### TryGetMember

**TryGetMember**(**instance**: [JObject](JObject.md), **binder**: GetMemberBinder, **result**: object): bool

**Parameters**

- **instance** ([JObject](JObject.md))  
- **binder** (GetMemberBinder)  
- **result** (object)  

**Returns** bool


---

#### TryGetValue

**TryGetValue**(**propertyName**: string, **comparison**: StringComparison, **value**: [JToken](JToken.md)): bool

Tries to get the JToken with the specified property name. The exact property name will be searched for first and if no matching property is found then the StringComparison will be used to match a property.

**Parameters**

- **propertyName** (string) — Name of the property.  
- **comparison** (StringComparison) — One of the enumeration values that specifies how the strings will be compared.  
- **value** ([JToken](JToken.md)) — The value.  

**Returns** bool — true if a value was successfully retrieved; otherwise, false.

---

**TryGetValue**(**propertyName**: string, **value**: [JToken](JToken.md)): bool

Tries the get value.

**Parameters**

- **propertyName** (string) — Name of the property.  
- **value** ([JToken](JToken.md)) — The value.  

**Returns** bool — true if a value was successfully retrieved; otherwise, false.


---

#### TrySetMember

**TrySetMember**(**instance**: [JObject](JObject.md), **binder**: SetMemberBinder, **value**: object): bool

**Parameters**

- **instance** ([JObject](JObject.md))  
- **binder** (SetMemberBinder)  
- **value** (object)  

**Returns** bool


---

#### WriteTo

**WriteTo**(**writer**: [JsonWriter](../JsonWriter.md), ****: JsonConverterconverters): void

Writes this token to a JsonWriter.

**Parameters**

- **writer** ([JsonWriter](../JsonWriter.md)) — A JsonWriter into which this method will write.  
- **** (JsonConverterconverters)  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **PropertyChanged** | PropertyChangedEventHandler | Occurs when a property value changes. |
| **PropertyChanging** | PropertyChangingEventHandler | Occurs when a property value is changing. |
