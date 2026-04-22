---
title: "JsonContainerContract Class"
---

## JsonContainerContract Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`  
**Assembly:** `Stimulsoft.Base`

Contract details for a Type used by the JsonSerializer.

```csharp
public class JsonContainerContract
```

### Inheritance

Inherits from: [JsonContract](JsonContract.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ItemConverter** | [JsonConverter](../JsonConverter.md) | Gets or sets the default collection items JsonConverter. |
| **ItemIsReference** | bool? | Gets or sets a value indicating whether the collection items preserve object references. |
| **ItemReferenceLoopHandling** | ReferenceLoopHandling? | Gets or sets the collection item reference loop handling. |
| **ItemTypeNameHandling** | TypeNameHandling? | Gets or sets the collection item type name handling. |
