---
title: "DateTimeZoneHandling Enum"
---

## DateTimeZoneHandling Enum

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Specifies how to treat the time value when converting between string and DateTime.

```csharp
public enum DateTimeZoneHandling
```

### Members

| Member | Value | Description |
| --- | --- | --- |
| **Local** | 0 | Treat as local time. If the DateTime object represents a Coordinated Universal Time (UTC), it is converted to the local time. |
| **Utc** | 1 | Treat as a UTC. If the DateTime object represents a local time, it is converted to a UTC. |
| **Unspecified** | 2 | Treat as a local time if a DateTime is being converted to a string. If a string is being converted to DateTime, convert to a local time if a time zone is specified. |
| **RoundtripKind** | 3 | Time zone information should be preserved when converting. |
