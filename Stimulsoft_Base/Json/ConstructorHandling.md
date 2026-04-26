---
title: "ConstructorHandling Enum"
---

## ConstructorHandling Enum

**Namespace:** `Stimulsoft.Base.Json`

Specifies how constructors are used when initializing objects during deserialization by the JsonSerializer.

### Members

| Member | Value | Description |
| --- | --- | --- |
| **Default** | 0 | First attempt to use the public default constructor, then fall back to single paramatized constructor, then the non-public default constructor. |
| **AllowNonPublicDefaultConstructor** | 1 | Json.NET will use a non-public default constructor before falling back to a paramatized constructor. |
