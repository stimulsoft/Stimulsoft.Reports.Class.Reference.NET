---
title: "Stimulsoft.Base.Json Namespace"
---

## Stimulsoft.Base.Json Namespace

### Classes

| Name | Description |
| --- | --- |
| [JsonArrayAttribute](JsonArrayAttribute.md) |  |
| [JsonConstructorAttribute](JsonConstructorAttribute.md) |  |
| [JsonContainerAttribute](JsonContainerAttribute.md) |  |
| [JsonConvert](JsonConvert.md) | Provides methods for converting between common language runtime types and JSON types. |
| [JsonConverter](JsonConverter.md) | Converts an object to and from JSON. |
| [JsonConverterAttribute](JsonConverterAttribute.md) |  |
| [JsonConverterCollection](JsonConverterCollection.md) | Represents a collection of JsonConverter. |
| [JsonDictionaryAttribute](JsonDictionaryAttribute.md) |  |
| [JsonException](JsonException.md) |  |
| [JsonExtensionDataAttribute](JsonExtensionDataAttribute.md) |  |
| [JsonIgnoreAttribute](JsonIgnoreAttribute.md) |  |
| [JsonObjectAttribute](JsonObjectAttribute.md) |  |
| [JsonPropertyAttribute](JsonPropertyAttribute.md) |  |
| [JsonReader](JsonReader.md) | Represents a reader that provides fast, non-cached, forward-only access to serialized JSON data. |
| [JsonReaderException](JsonReaderException.md) |  |
| [JsonSerializationException](JsonSerializationException.md) |  |
| [JsonSerializer](JsonSerializer.md) | Serializes and deserializes objects into and from the JSON format. The JsonSerializer enables you to control how objects are encoded into JSON. |
| [JsonSerializerSettings](JsonSerializerSettings.md) | Specifies the settings on a JsonSerializer object. |
| [JsonTextReader](JsonTextReader.md) | Represents a reader that provides fast, non-cached, forward-only access to JSON text data. |
| [JsonTextWriter](JsonTextWriter.md) | Represents a writer that provides a fast, non-cached, forward-only way of generating JSON data. |
| [JsonValidatingReader](JsonValidatingReader.md) |  |
| [JsonWriter](JsonWriter.md) | Represents a writer that provides a fast, non-cached, forward-only way of generating JSON data. |
| [JsonWriterException](JsonWriterException.md) |  |
| [SerializationBinder](SerializationBinder.md) | Allows users to control class loading and mandate what class to load. |

### Interfaces

| Name | Description |
| --- | --- |
| [IJsonLineInfo](IJsonLineInfo.md) | Provides an interface to enable a class to return line and position information. |

### Enumerations

| Name | Description |
| --- | --- |
| [ConstructorHandling](ConstructorHandling.md) | Specifies how constructors are used when initializing objects during deserialization by the JsonSerializer. |
| [DateFormatHandling](DateFormatHandling.md) | Specifies how dates are formatted when writing JSON text. |
| [DateParseHandling](DateParseHandling.md) | Specifies how date formatted strings, e.g. "\/Date(1198908717056)\/" and "2012-03-21T05:40Z", are parsed when reading JSON text. |
| [DateTimeZoneHandling](DateTimeZoneHandling.md) | Specifies how to treat the time value when converting between string and DateTime. |
| [DefaultValueHandling](DefaultValueHandling.md) |  |
| [FloatFormatHandling](FloatFormatHandling.md) | Specifies float format handling options when writing special floating point numbers, e.g. NaN, PositiveInfinity and NegativeInfinity with JsonWriter. |
| [FloatParseHandling](FloatParseHandling.md) | Specifies how floating point numbers, e.g. 1.0 and 9.9, are parsed when reading JSON text. |
| [Formatting](Formatting.md) | Specifies formatting options for the JsonTextWriter. |
| [JsonToken](JsonToken.md) | Specifies the type of JSON token. |
| [MemberSerialization](MemberSerialization.md) | Specifies the member serialization options for the JsonSerializer. |
| [MetadataPropertyHandling](MetadataPropertyHandling.md) | Specifies metadata property handling options for the JsonSerializer. |
| [MissingMemberHandling](MissingMemberHandling.md) | Specifies missing member handling options for the JsonSerializer. |
| [NullValueHandling](NullValueHandling.md) | Specifies null value handling options for the JsonSerializer. |
| [ObjectCreationHandling](ObjectCreationHandling.md) | Specifies how object creation is handled by the JsonSerializer. |
| [PreserveReferencesHandling](PreserveReferencesHandling.md) |  |
| [ReferenceLoopHandling](ReferenceLoopHandling.md) | Specifies reference loop handling options for the JsonSerializer. |
| [Required](Required.md) | Indicating whether a property is required. |
| [StringEscapeHandling](StringEscapeHandling.md) | Specifies how strings are escaped when writing JSON text. |
| [TraceLevel](TraceLevel.md) | Specifies what messages to output for the ITraceWriter class. |
| [TypeNameHandling](TypeNameHandling.md) |  |
| [WriteState](WriteState.md) | Specifies the state of the JsonWriter. |
