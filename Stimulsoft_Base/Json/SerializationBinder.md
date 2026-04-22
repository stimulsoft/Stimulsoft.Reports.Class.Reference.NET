---
title: "SerializationBinder Class"
---

## SerializationBinder Class

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Allows users to control class loading and mandate what class to load.

```csharp
public abstract class SerializationBinder
```

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BindToName** | void | When overridden in a derived class, controls the binding of a serialized object to a type. |
| **BindToType** | Type | When overridden in a derived class, controls the binding of a serialized object to a type. |
