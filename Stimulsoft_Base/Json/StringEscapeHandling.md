---
title: "StringEscapeHandling Enum"
---

## StringEscapeHandling Enum

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Specifies how strings are escaped when writing JSON text.

```csharp
public enum StringEscapeHandling
```

### Members

| Member | Value | Description |
| --- | --- | --- |
| **Default** | 0 | Only control characters (e.g. newline) are escaped. |
| **EscapeNonAscii** | 1 | All non-ASCII and control characters (e.g. newline) are escaped. |
| **EscapeHtml** | 2 | HTML (&lt;, &gt;, &amp;, &apos;, &quot;) and control characters (e.g. newline) are escaped. |
