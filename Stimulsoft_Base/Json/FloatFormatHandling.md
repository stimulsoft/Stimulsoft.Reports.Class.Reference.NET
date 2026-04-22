---
title: "FloatFormatHandling Enum"
---

## FloatFormatHandling Enum

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Specifies float format handling options when writing special floating point numbers, e.g. NaN, PositiveInfinity and NegativeInfinity with JsonWriter.

```csharp
public enum FloatFormatHandling
```

### Members

| Member | Value | Description |
| --- | --- | --- |
| **String** | 0 | Write special floating point values as strings in JSON, e.g. "NaN", "Infinity", "-Infinity". |
| **Symbol** | 1 | Write special floating point values as symbols in JSON, e.g. NaN, Infinity, -Infinity. Note that this will produce non-valid JSON. |
| **DefaultValue** | 2 | Write special floating point values as the property's default value in JSON, e.g. 0.0 for a Double property, null for a Nullable{Double} property. |
