---
title: "FormatterAssemblyStyle Enum"
---

## FormatterAssemblyStyle Enum

**Namespace:** `System.Runtime.Serialization.Formatters`  
**Assembly:** `Stimulsoft.Base`

Indicates the method that will be used during deserialization for locating and loading assemblies.

```csharp
public enum FormatterAssemblyStyle
```

### Members

| Member | Value | Description |
| --- | --- | --- |
| **Simple** | 0 | In simple mode, the assembly used during deserialization need not match exactly the assembly used during serialization. Specifically, the version numbers need not match as the LoadWithPartialName method is used to load the assembly. |
| **Full** | 1 | In full mode, the assembly used during deserialization must match exactly the assembly used during serialization. The Load method of the Assembly class is used to load the assembly. |
