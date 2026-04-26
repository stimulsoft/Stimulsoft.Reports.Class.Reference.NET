---
title: "JsonToken Enum"
---

## JsonToken Enum

**Namespace:** `Stimulsoft.Base.Json`

Specifies the type of JSON token.

### Members

| Member | Value | Description |
| --- | --- | --- |
| **None** | 0 | This is returned by the JsonReader if a Read method has not been called. |
| **StartObject** | 1 | An object start token. |
| **StartArray** | 2 | An array start token. |
| **StartConstructor** | 3 | A constructor start token. |
| **PropertyName** | 4 | An object property name. |
| **Comment** | 5 | A comment. |
| **Raw** | 6 | Raw JSON. |
| **Integer** | 7 | An integer. |
| **Float** | 8 | A float. |
| **String** | 9 | A string. |
| **Boolean** | 10 | A boolean. |
| **Null** | 11 | A null token. |
| **Undefined** | 12 | An undefined token. |
| **EndObject** | 13 | An object end token. |
| **EndArray** | 14 | An array end token. |
| **EndConstructor** | 15 | A constructor end token. |
| **Date** | 16 | A Date. |
| **Bytes** | 17 | Byte data. |
