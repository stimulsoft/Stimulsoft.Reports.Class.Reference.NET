---
title: "JValue Class"
---

## JValue Class

**Namespace:** `Stimulsoft.Base.Json.Linq`

Represents a value in JSON (string, integer, date, etc).

### Inheritance

Inherits from: [JToken](JToken.md)  
Implements: IEquatable<[JValue](JValue.md)>, IFormattable, IComparable, IComparable<[JValue](JValue.md)>  

### Constructors

| Constructor | Description |
| --- | --- |
| **JValue**([JValue](JValue.md) other) | Initializes a new instance of the JValue class from another JValue object. |
| **JValue**(long value) | Initializes a new instance of the JValue class with the given value. |
| **JValue**(decimal value) | Initializes a new instance of the JValue class with the given value. |
| **JValue**(char value) | Initializes a new instance of the JValue class with the given value. |
| **JValue**(ulong value) |  |
| **JValue**(double value) | Initializes a new instance of the JValue class with the given value. |
| **JValue**(float value) | Initializes a new instance of the JValue class with the given value. |
| **JValue**(DateTime value) | Initializes a new instance of the JValue class with the given value. |
| **JValue**(DateTimeOffset value) | Initializes a new instance of the JValue class with the given value. |
| **JValue**(bool value) | Initializes a new instance of the JValue class with the given value. |
| **JValue**(string value) | Initializes a new instance of the JValue class with the given value. |
| **JValue**(Guid value) | Initializes a new instance of the JValue class with the given value. |
| **JValue**(Uri value) | Initializes a new instance of the JValue class with the given value. |
| **JValue**(TimeSpan value) | Initializes a new instance of the JValue class with the given value. |
| **JValue**(object value) | Initializes a new instance of the JValue class with the given value. |

**JValue**(**other**: [JValue](JValue.md))

Initializes a new instance of the JValue class from another JValue object.

**Parameters**

- **other** ([JValue](JValue.md)) — A JValue object to copy from.  

---

**JValue**(**value**: long)

Initializes a new instance of the JValue class with the given value.

**Parameters**

- **value** (long) — The value.  

---

**JValue**(**value**: decimal)

Initializes a new instance of the JValue class with the given value.

**Parameters**

- **value** (decimal) — The value.  

---

**JValue**(**value**: char)

Initializes a new instance of the JValue class with the given value.

**Parameters**

- **value** (char) — The value.  

---

**JValue**(**value**: ulong)

**Parameters**

- **value** (ulong)  

---

**JValue**(**value**: double)

Initializes a new instance of the JValue class with the given value.

**Parameters**

- **value** (double) — The value.  

---

**JValue**(**value**: float)

Initializes a new instance of the JValue class with the given value.

**Parameters**

- **value** (float) — The value.  

---

**JValue**(**value**: DateTime)

Initializes a new instance of the JValue class with the given value.

**Parameters**

- **value** (DateTime) — The value.  

---

**JValue**(**value**: DateTimeOffset)

Initializes a new instance of the JValue class with the given value.

**Parameters**

- **value** (DateTimeOffset) — The value.  

---

**JValue**(**value**: bool)

Initializes a new instance of the JValue class with the given value.

**Parameters**

- **value** (bool) — The value.  

---

**JValue**(**value**: string)

Initializes a new instance of the JValue class with the given value.

**Parameters**

- **value** (string) — The value.  

---

**JValue**(**value**: Guid)

Initializes a new instance of the JValue class with the given value.

**Parameters**

- **value** (Guid) — The value.  

---

**JValue**(**value**: Uri)

Initializes a new instance of the JValue class with the given value.

**Parameters**

- **value** (Uri) — The value.  

---

**JValue**(**value**: TimeSpan)

Initializes a new instance of the JValue class with the given value.

**Parameters**

- **value** (TimeSpan) — The value.  

---

**JValue**(**value**: object)

Initializes a new instance of the JValue class with the given value.

**Parameters**

- **value** (object) — The value.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CompareTo** | int | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
| **CreateComment** `static` | [JValue](JValue.md) | Creates a JValue comment with the given value. |
| **CreateNull** `static` | [JValue](JValue.md) | Creates a JValue null value. |
| **CreateString** `static` | [JValue](JValue.md) | Creates a JValue string with the given value. |
| **CreateUndefined** `static` | [JValue](JValue.md) | Creates a JValue null value. |
| **Equals** *(+1 overloads)* | bool | Indicates whether the current object is equal to another object of the same type. |
| **GetHashCode** | int | Serves as a hash function for a particular type. |
| **GetMetaObject** | DynamicMetaObject | Returns the DynamicMetaObject responsible for binding operations performed on this object. |
| **ToString** *(+3 overloads)* | string | Returns a String that represents this instance. |
| **TryBinaryOperation** | bool |  |
| **TryConvert** | bool |  |
| **WriteTo** | void | Writes this token to a JsonWriter. |

---

### Method Details

#### CompareTo

**CompareTo**(**obj**: [JValue](JValue.md)): int

Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object.

**Parameters**

- **obj** ([JValue](JValue.md)) — An object to compare with this instance.  

**Returns** int — A 32-bit signed integer that indicates the relative order of the objects being compared. The return value has these meanings: Value Meaning Less than zero This instance is less than . Zero This instance is equal to . Greater than zero This instance is greater than .


---

#### CreateComment `static`

**CreateComment**(**value**: string): [JValue](JValue.md)

Creates a JValue comment with the given value.

**Parameters**

- **value** (string) — The value.  

**Returns** [JValue](JValue.md) — A JValue comment with the given value.


---

#### CreateNull `static`

**CreateNull**(): [JValue](JValue.md)

Creates a JValue null value.

**Returns** [JValue](JValue.md) — A JValue null value.


---

#### CreateString `static`

**CreateString**(**value**: string): [JValue](JValue.md)

Creates a JValue string with the given value.

**Parameters**

- **value** (string) — The value.  

**Returns** [JValue](JValue.md) — A JValue string with the given value.


---

#### CreateUndefined `static`

**CreateUndefined**(): [JValue](JValue.md)

Creates a JValue null value.

**Returns** [JValue](JValue.md) — A JValue null value.


---

#### Equals

**Equals**(**other**: [JValue](JValue.md)): bool

Indicates whether the current object is equal to another object of the same type.

**Parameters**

- **other** ([JValue](JValue.md)) — An object to compare with this object.  

**Returns** bool — true if the current object is equal to the parameter; otherwise, false.

---

**Equals**(**obj**: object): bool

Determines whether the specified Object is equal to the current Object.

**Parameters**

- **obj** (object) — The Object to compare with the current Object.  

**Returns** bool — true if the specified Object is equal to the current Object; otherwise, false.


---

#### GetHashCode

**GetHashCode**(): int

Serves as a hash function for a particular type.

**Returns** int — A hash code for the current Object.


---

#### GetMetaObject

**GetMetaObject**(**parameter**: [Expression](../../../Stimulsoft_Data/Expressions/NCalc/Expression.md)): DynamicMetaObject

Returns the DynamicMetaObject responsible for binding operations performed on this object.

**Parameters**

- **parameter** ([Expression](../../../Stimulsoft_Data/Expressions/NCalc/Expression.md)) — The expression tree representation of the runtime value.  

**Returns** DynamicMetaObject — The DynamicMetaObject to bind this object.


---

#### ToString

**ToString**(): string

Returns a String that represents this instance.

**Returns** string — A String that represents this instance.

---

**ToString**(**format**: string): string

Returns a String that represents this instance.

**Parameters**

- **format** (string) — The format.  

**Returns** string — A String that represents this instance.

---

**ToString**(**formatProvider**: IFormatProvider): string

Returns a String that represents this instance.

**Parameters**

- **formatProvider** (IFormatProvider) — The format provider.  

**Returns** string — A String that represents this instance.

---

**ToString**(**format**: string, **formatProvider**: IFormatProvider): string

Returns a String that represents this instance.

**Parameters**

- **format** (string) — The format.  
- **formatProvider** (IFormatProvider) — The format provider.  

**Returns** string — A String that represents this instance.


---

#### TryBinaryOperation

**TryBinaryOperation**(**instance**: [JValue](JValue.md), **binder**: BinaryOperationBinder, **arg**: object, **result**: object): bool

**Parameters**

- **instance** ([JValue](JValue.md))  
- **binder** (BinaryOperationBinder)  
- **arg** (object)  
- **result** (object)  

**Returns** bool


---

#### TryConvert

**TryConvert**(**instance**: [JValue](JValue.md), **binder**: ConvertBinder, **result**: object): bool

**Parameters**

- **instance** ([JValue](JValue.md))  
- **binder** (ConvertBinder)  
- **result** (object)  

**Returns** bool


---

#### WriteTo

**WriteTo**(**writer**: [JsonWriter](../JsonWriter.md), ****: JsonConverterconverters): void

Writes this token to a JsonWriter.

**Parameters**

- **writer** ([JsonWriter](../JsonWriter.md)) — A JsonWriter into which this method will write.  
- **** (JsonConverterconverters)  

