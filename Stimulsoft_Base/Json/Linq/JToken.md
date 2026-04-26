---
title: "JToken Class"
---

## JToken Class

**Namespace:** `Stimulsoft.Base.Json.Linq`

Represents an abstract JSON token.

### Inheritance

Implements: IJEnumerable<[JToken](JToken.md)>, [IJsonLineInfo](../IJsonLineInfo.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **HasValues** | bool | Gets a value indicating whether this token has child tokens. |
| **Type** | [JTokenType](JTokenType.md) | Gets the node type for this JToken. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddAfterSelf** | void | Adds the specified content immediately after this token. |
| **AddAnnotation** | void | Adds an object to the annotation list of this JToken. |
| **AddBeforeSelf** | void | Adds the specified content immediately before this token. |
| **AfterSelf** | IEnumerable<[JToken](JToken.md)> | Returns a collection of the sibling tokens after this token, in document order. |
| **Ancestors** | IEnumerable<[JToken](JToken.md)> | Returns a collection of the ancestor tokens of this token. |
| **AncestorsAndSelf** | IEnumerable<[JToken](JToken.md)> | Returns a collection of tokens that contain this token, and the ancestors of this token. |
| **Annotation** | object | Gets the first annotation object of the specified type from this JToken. |
| **Annotations** | IEnumerable<object> | Gets a collection of annotations of the specified type for this JToken. |
| **BeforeSelf** | IEnumerable<[JToken](JToken.md)> | Returns a collection of the sibling tokens before this token, in document order. |
| **Children** *(+1 overloads)* | [JEnumerable](JEnumerable.md)<[JToken](JToken.md)> | Returns a collection of the child tokens of this token, in document order. |
| **CreateReader** | [JsonReader](../JsonReader.md) | Creates an JsonReader for this token. |
| **DeepClone** | [JToken](JToken.md) | Creates a new instance of the JToken. All child tokens are recursively cloned. |
| **DeepEquals** `static` | bool | Compares the values of two tokens, including the values of all descendant tokens. |
| **FromObject** `static` *(+1 overloads)* | [JToken](JToken.md) | Creates a JToken from an object. |
| **GetMetaObject** | DynamicMetaObject | Returns the DynamicMetaObject responsible for binding operations performed on this object. |
| **Load** `static` | [JToken](JToken.md) | Creates a JToken from a JsonReader. |
| **Parse** `static` | [JToken](JToken.md) | Load a JToken from a string that contains JSON. |
| **ReadFrom** `static` | [JToken](JToken.md) | Creates a JToken from a JsonReader. |
| **Remove** | void | Removes this token from its parent. |
| **RemoveAnnotations** | void | Removes the annotations of the specified type from this JToken. |
| **Replace** | void | Replaces this token with the specified token. |
| **SelectToken** *(+1 overloads)* | [JToken](JToken.md) | Selects a JToken using a JPath expression. Selects the token that matches the object path. |
| **SelectTokens** *(+1 overloads)* | IEnumerable<[JToken](JToken.md)> | Selects a collection of elements using a JPath expression. |
| **ToObject** *(+3 overloads)* | T | Creates the specified .NET type from the JToken. |
| **ToString** *(+2 overloads)* | string | Returns the indented JSON for this token. |
| **Value** | T | Gets the JToken with the specified key converted to the specified type. |
| **Values** | IEnumerable<T> | Returns a collection of the child values of this token, in document order. |
| **WriteTo** | void | Writes this token to a JsonWriter. |

---

### Method Details

#### AddAfterSelf

**AddAfterSelf**(**content**: object): void

Adds the specified content immediately after this token.

**Parameters**

- **content** (object) — A content object that contains simple content or a collection of content objects to be added after this token.  


---

#### AddAnnotation

**AddAnnotation**(**annotation**: object): void

Adds an object to the annotation list of this JToken.

**Parameters**

- **annotation** (object) — The annotation to add.  


---

#### AddBeforeSelf

**AddBeforeSelf**(**content**: object): void

Adds the specified content immediately before this token.

**Parameters**

- **content** (object) — A content object that contains simple content or a collection of content objects to be added before this token.  


---

#### AfterSelf

**AfterSelf**(): IEnumerable<[JToken](JToken.md)>

Returns a collection of the sibling tokens after this token, in document order.

**Returns** IEnumerable<[JToken](JToken.md)> — A collection of the sibling tokens after this tokens, in document order.


---

#### Ancestors

**Ancestors**(): IEnumerable<[JToken](JToken.md)>

Returns a collection of the ancestor tokens of this token.

**Returns** IEnumerable<[JToken](JToken.md)> — A collection of the ancestor tokens of this token.


---

#### AncestorsAndSelf

**AncestorsAndSelf**(): IEnumerable<[JToken](JToken.md)>

Returns a collection of tokens that contain this token, and the ancestors of this token.

**Returns** IEnumerable<[JToken](JToken.md)> — A collection of tokens that contain this token, and the ancestors of this token.


---

#### Annotation

**Annotation**(**type**: Type): object

Gets the first annotation object of the specified type from this JToken.

**Parameters**

- **type** (Type) — The Type of the annotation to retrieve.  

**Returns** object — The first annotation object that matches the specified type, or `null` if no annotation is of the specified type.


---

#### Annotations

**Annotations**(**type**: Type): IEnumerable<object>

Gets a collection of annotations of the specified type for this JToken.

**Parameters**

- **type** (Type) — The Type of the annotations to retrieve.  

**Returns** IEnumerable<object> — An IEnumerable{T} of Object that contains the annotations that match the specified type for this JToken.


---

#### BeforeSelf

**BeforeSelf**(): IEnumerable<[JToken](JToken.md)>

Returns a collection of the sibling tokens before this token, in document order.

**Returns** IEnumerable<[JToken](JToken.md)> — A collection of the sibling tokens before this token, in document order.


---

#### Children

**Children**(): [JEnumerable](JEnumerable.md)<[JToken](JToken.md)>

Returns a collection of the child tokens of this token, in document order.

**Returns** [JEnumerable](JEnumerable.md)<[JToken](JToken.md)> — An IEnumerable{T} of JToken containing the child tokens of this JToken, in document order.

---

**Children**(): [JEnumerable](JEnumerable.md)<T>

Returns a collection of the child tokens of this token, in document order, filtered by the specified type.

**Returns** [JEnumerable](JEnumerable.md)<T> — A JEnumerable{T} containing the child tokens of this JToken, in document order.


---

#### CreateReader

**CreateReader**(): [JsonReader](../JsonReader.md)

Creates an JsonReader for this token.

**Returns** [JsonReader](../JsonReader.md) — An JsonReader that can be used to read this token and its descendants.


---

#### DeepClone

**DeepClone**(): [JToken](JToken.md)

Creates a new instance of the JToken. All child tokens are recursively cloned.

**Returns** [JToken](JToken.md) — A new instance of the JToken.


---

#### DeepEquals `static`

**DeepEquals**(**t1**: [JToken](JToken.md), **t2**: [JToken](JToken.md)): bool

Compares the values of two tokens, including the values of all descendant tokens.

**Parameters**

- **t1** ([JToken](JToken.md)) — The first JToken to compare.  
- **t2** ([JToken](JToken.md)) — The second JToken to compare.  

**Returns** bool — true if the tokens are equal; otherwise false.


---

#### FromObject `static`

**FromObject**(**o**: object): [JToken](JToken.md)

Creates a JToken from an object.

**Parameters**

- **o** (object) — The object that will be used to create JToken.  

**Returns** [JToken](JToken.md) — A JToken with the value of the specified object

---

**FromObject**(**o**: object, **jsonSerializer**: [JsonSerializer](../../Json2/JsonSerializer.md)): [JToken](JToken.md)

Creates a JToken from an object using the specified JsonSerializer.

**Parameters**

- **o** (object) — The object that will be used to create JToken.  
- **jsonSerializer** ([JsonSerializer](../../Json2/JsonSerializer.md)) — The JsonSerializer that will be used when reading the object.  

**Returns** [JToken](JToken.md) — A JToken with the value of the specified object


---

#### GetMetaObject

**GetMetaObject**(**parameter**: [Expression](../../../Stimulsoft_Data/Expressions/NCalc/Expression.md)): DynamicMetaObject

Returns the DynamicMetaObject responsible for binding operations performed on this object.

**Parameters**

- **parameter** ([Expression](../../../Stimulsoft_Data/Expressions/NCalc/Expression.md)) — The expression tree representation of the runtime value.  

**Returns** DynamicMetaObject — The DynamicMetaObject to bind this object.


---

#### Load `static`

**Load**(**reader**: [JsonReader](../JsonReader.md)): [JToken](JToken.md)

Creates a JToken from a JsonReader.

**Parameters**

- **reader** ([JsonReader](../JsonReader.md)) — An JsonReader positioned at the token to read into this JToken.  

**Returns** [JToken](JToken.md) — An JToken that contains the token and its descendant tokens that were read from the reader. The runtime type of the token is determined by the token type of the first token encountered in the reader.


---

#### Parse `static`

**Parse**(**json**: string): [JToken](JToken.md)

Load a JToken from a string that contains JSON.

**Parameters**

- **json** (string) — A String that contains JSON.  

**Returns** [JToken](JToken.md) — A JToken populated from the string that contains JSON.


---

#### ReadFrom `static`

**ReadFrom**(**reader**: [JsonReader](../JsonReader.md)): [JToken](JToken.md)

Creates a JToken from a JsonReader.

**Parameters**

- **reader** ([JsonReader](../JsonReader.md)) — An JsonReader positioned at the token to read into this JToken.  

**Returns** [JToken](JToken.md) — An JToken that contains the token and its descendant tokens that were read from the reader. The runtime type of the token is determined by the token type of the first token encountered in the reader.


---

#### Remove

**Remove**(): void

Removes this token from its parent.


---

#### RemoveAnnotations

**RemoveAnnotations**(**type**: Type): void

Removes the annotations of the specified type from this JToken.

**Parameters**

- **type** (Type) — The Type of annotations to remove.  


---

#### Replace

**Replace**(**value**: [JToken](JToken.md)): void

Replaces this token with the specified token.

**Parameters**

- **value** ([JToken](JToken.md)) — The value.  


---

#### SelectToken

**SelectToken**(**path**: string): [JToken](JToken.md)

Selects a JToken using a JPath expression. Selects the token that matches the object path.

**Parameters**

- **path** (string) — A String that contains a JPath expression.  

**Returns** [JToken](JToken.md) — A JToken, or null.

---

**SelectToken**(**path**: string, **errorWhenNoMatch**: bool): [JToken](JToken.md)

Selects a JToken using a JPath expression. Selects the token that matches the object path.

**Parameters**

- **path** (string) — A String that contains a JPath expression.  
- **errorWhenNoMatch** (bool) — A flag to indicate whether an error should be thrown if no tokens are found when evaluating part of the expression.  

**Returns** [JToken](JToken.md) — A JToken.


---

#### SelectTokens

**SelectTokens**(**path**: string): IEnumerable<[JToken](JToken.md)>

Selects a collection of elements using a JPath expression.

**Parameters**

- **path** (string) — A String that contains a JPath expression.  

**Returns** IEnumerable<[JToken](JToken.md)> — An IEnumerable{JToken} that contains the selected elements.

---

**SelectTokens**(**path**: string, **errorWhenNoMatch**: bool): IEnumerable<[JToken](JToken.md)>

Selects a collection of elements using a JPath expression.

**Parameters**

- **path** (string) — A String that contains a JPath expression.  
- **errorWhenNoMatch** (bool) — A flag to indicate whether an error should be thrown if no tokens are found when evaluating part of the expression.  

**Returns** IEnumerable<[JToken](JToken.md)> — An IEnumerable{JToken} that contains the selected elements.


---

#### ToObject

**ToObject**(): T

Creates the specified .NET type from the JToken.

**Returns** T — The new object created from the JSON value.

---

**ToObject**(**objectType**: Type): object

Creates the specified .NET type from the JToken.

**Parameters**

- **objectType** (Type) — The object type that the token will be deserialized to.  

**Returns** object — The new object created from the JSON value.

---

**ToObject**(**jsonSerializer**: [JsonSerializer](../../Json2/JsonSerializer.md)): T

Creates the specified .NET type from the JToken using the specified JsonSerializer.

**Parameters**

- **jsonSerializer** ([JsonSerializer](../../Json2/JsonSerializer.md)) — The JsonSerializer that will be used when creating the object.  

**Returns** T — The new object created from the JSON value.

---

**ToObject**(**objectType**: Type, **jsonSerializer**: [JsonSerializer](../../Json2/JsonSerializer.md)): object

Creates the specified .NET type from the JToken using the specified JsonSerializer.

**Parameters**

- **objectType** (Type) — The object type that the token will be deserialized to.  
- **jsonSerializer** ([JsonSerializer](../../Json2/JsonSerializer.md)) — The JsonSerializer that will be used when creating the object.  

**Returns** object — The new object created from the JSON value.


---

#### ToString

**ToString**(): string

Returns the indented JSON for this token.

**Returns** string — The indented JSON for this token.

---

**ToString**(**cultureInfo**: CultureInfo): string

Returns the indented JSON for this token.

**Parameters**

- **cultureInfo** (CultureInfo)  

**Returns** string — The indented JSON for this token.

---

**ToString**(**formatting**: [Formatting](../Formatting.md), **cultureInfo**: CultureInfo, ****: JsonConverterconverters): string

Returns the JSON for this token using the given formatting and converters.

**Parameters**

- **formatting** ([Formatting](../Formatting.md)) — Indicates how the output is formatted.  
- **cultureInfo** (CultureInfo)  
- **** (JsonConverterconverters)  

**Returns** string — The JSON for this token using the given formatting and converters.


---

#### Value

**Value**(**key**: object): T

Gets the JToken with the specified key converted to the specified type.

**Parameters**

- **key** (object) — The token key.  

**Returns** T — The converted token value.


---

#### Values

**Values**(): IEnumerable<T>

Returns a collection of the child values of this token, in document order.

**Returns** IEnumerable<T> — A IEnumerable{T} containing the child values of this JToken, in document order.


---

#### WriteTo

**WriteTo**(**writer**: [JsonWriter](../JsonWriter.md), ****: JsonConverterconverters): void

Writes this token to a JsonWriter.

**Parameters**

- **writer** ([JsonWriter](../JsonWriter.md)) — A JsonWriter into which this method will write.  
- **** (JsonConverterconverters)  

