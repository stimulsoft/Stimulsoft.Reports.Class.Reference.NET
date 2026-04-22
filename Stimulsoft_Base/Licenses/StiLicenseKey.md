---
title: "StiLicenseKey Class"
---

## StiLicenseKey Class

**Namespace:** `Stimulsoft.Base.Licenses`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiLicenseKey
```

### Inheritance

Inherits from: [StiLicenseObject](StiLicenseObject.md)  
Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLicenseKey**() |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ActivationDate** | DateTime |  |
| **DeviceId** | string |  |
| **EndDate** | DateTime? |  |
| **Owner** | string |  |
| **PlanId** | StiPlanIdent? |  |
| **ProductDescription** | string |  |
| **ProductFavIcon** | byte[] |  |
| **ProductLogo** | byte[] |  |
| **ProductName** | string |  |
| **ProductUrl** | string |  |
| **Products** | List<[StiLicenseProduct](StiLicenseProduct.md)> |  |
| **Signature** | string |  |
| **StartDate** | DateTime? |  |
| **UserName** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **Get** `static` *(+1 overloads)* | [StiLicenseKey](StiLicenseKey.md) |  |
| **GetCSharpCode** | string |  |
| **GetCheckBytes** | byte[] |  |
| **GetSignatureBytes** | byte[] |  |
| **GetVbNetCode** | string |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **IsProductLicense** | bool |  |
| **IsServerLicense** | bool |  |
