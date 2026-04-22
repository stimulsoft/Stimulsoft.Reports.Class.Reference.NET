---
title: "JValue Class"
---

## JValue Class

**Namespace:** `Stimulsoft.Base.Json.Linq`  
**Assembly:** `Stimulsoft.Base`

Represents a value in JSON (string, integer, date, etc).

```csharp
public class JValue
```

### Inheritance

Inherits from: [JToken](JToken.md)  
Implements: IEquatable<[JValue](JValue.md)>, IFormattable, IComparable, IComparable<[JValue](JValue.md)>  

### Constructors

| Constructor | Description |
| --- | --- |
| `JValue([JValue](JValue.md) other)` | Initializes a new instance of the JValue class from another JValue object. |
| `JValue(long value)` | Initializes a new instance of the JValue class with the given value. |
| `JValue(decimal value)` | Initializes a new instance of the JValue class with the given value. |
| `JValue(char value)` | Initializes a new instance of the JValue class with the given value. |
| `JValue(ulong value)` |  |
| `JValue(double value)` | Initializes a new instance of the JValue class with the given value. |
| `JValue(float value)` | Initializes a new instance of the JValue class with the given value. |
| `JValue(DateTime value)` | Initializes a new instance of the JValue class with the given value. |
| `JValue(DateTimeOffset value)` | Initializes a new instance of the JValue class with the given value. |
| `JValue(bool value)` | Initializes a new instance of the JValue class with the given value. |
| `JValue(string value)` | Initializes a new instance of the JValue class with the given value. |
| `JValue(Guid value)` | Initializes a new instance of the JValue class with the given value. |
| `JValue(Uri value)` | Initializes a new instance of the JValue class with the given value. |
| `JValue(TimeSpan value)` | Initializes a new instance of the JValue class with the given value. |
| `JValue(object value)` | Initializes a new instance of the JValue class with the given value. |

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
