---
title: "DateParseHandling Enum"
---

## DateParseHandling Enum

**Namespace:** `Stimulsoft.Base.Json`

Specifies how date formatted strings, e.g. "\/Date(1198908717056)\/" and "2012-03-21T05:40Z", are parsed when reading JSON text.

### Members

| Member | Value | Description |
| --- | --- | --- |
| **None** | 0 | Date formatted strings are not parsed to a date type and are read as strings. |
| **DateTime** | 1 | Date formatted strings, e.g. "\/Date(1198908717056)\/" and "2012-03-21T05:40Z", are parsed to DateTime. |
| **DateTimeOffset** | 2 | Date formatted strings, e.g. "\/Date(1198908717056)\/" and "2012-03-21T05:40Z", are parsed to DateTimeOffset. |
