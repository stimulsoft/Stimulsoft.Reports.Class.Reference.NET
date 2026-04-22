---
title: "StiLicenseActivationResponse Class"
---

## StiLicenseActivationResponse Class

**Namespace:** `Stimulsoft.Base.Licenses`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiLicenseActivationResponse
```

### Inheritance

Inherits from: [StiLicenseObject](StiLicenseObject.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Exception** | string | An information about exception which occurs during activation process. |
| **LicenseKey** | [StiLicenseKey](StiLicenseKey.md) |  |
| **ResultNotice** | [StiNotice](../StiNotice.md) | A message about the running command. This Result can be skipped. |
| **ResultSuccess** | bool | True or False value which depend on the status of the running command. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateStik** | string |  |
| **Get** `static` *(+1 overloads)* | [StiLicenseActivationResponse](StiLicenseActivationResponse.md) |  |
| **MakeFine** `static` | [StiLicenseActivationResponse](StiLicenseActivationResponse.md) |  |
| **MakeWrong** `static` | [StiLicenseActivationResponse](StiLicenseActivationResponse.md) |  |
