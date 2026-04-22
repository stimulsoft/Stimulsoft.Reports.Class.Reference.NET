---
title: "UndefinedSchemaIdHandling Enum"
---

## UndefinedSchemaIdHandling Enum

**Namespace:** `Stimulsoft.Base.Json.Schema`  
**Assembly:** `Stimulsoft.Base`

```csharp
public enum UndefinedSchemaIdHandling
```

### Members

| Member | Value | Description |
| --- | --- | --- |
| **None** | 0 | Do not infer a schema Id. |
| **UseTypeName** | 1 | Use the .NET type name as the schema Id. |
| **UseAssemblyQualifiedName** | 2 | Use the assembly qualified .NET type name as the schema Id. |
