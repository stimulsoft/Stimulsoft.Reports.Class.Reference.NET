---
title: "MissingMemberHandling Enum"
---

## MissingMemberHandling Enum

**Namespace:** `Stimulsoft.Base.Json`

Specifies missing member handling options for the JsonSerializer.

### Members

| Member | Value | Description |
| --- | --- | --- |
| **Ignore** | 0 | Ignore a missing member and do not attempt to deserialize it. |
| **Error** | 1 | Throw a JsonSerializationException when a missing member is encountered during deserialization. |
