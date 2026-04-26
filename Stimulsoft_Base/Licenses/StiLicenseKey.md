---
title: "StiLicenseKey Class"
---

## StiLicenseKey Class

**Namespace:** `Stimulsoft.Base.Licenses`

### Inheritance

Inherits from: [StiLicenseObject](StiLicenseObject.md)  
Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLicenseKey**() |  |

**StiLicenseKey**()


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

---

### Method Details

#### Clone

**Clone**(): object

**Returns** object


---

#### Get `static`

**Get**(****: bytebytes): [StiLicenseKey](StiLicenseKey.md)

**Parameters**

- **** (bytebytes)  

**Returns** [StiLicenseKey](StiLicenseKey.md)

---

**Get**(**str**: string): [StiLicenseKey](StiLicenseKey.md)

**Parameters**

- **str** (string)  

**Returns** [StiLicenseKey](StiLicenseKey.md)


---

#### GetCSharpCode

**GetCSharpCode**(**maxSymbols**: int, **onlyKey**: bool): string

**Parameters**

- **maxSymbols** (int)  
- **onlyKey** (bool)  

**Returns** string


---

#### GetCheckBytes

**GetCheckBytes**(): byte[]

**Returns** byte[]


---

#### GetSignatureBytes

**GetSignatureBytes**(): byte[]

**Returns** byte[]


---

#### GetVbNetCode

**GetVbNetCode**(**maxSymbols**: int, **onlyKey**: bool): string

**Parameters**

- **maxSymbols** (int)  
- **onlyKey** (bool)  

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **IsProductLicense** | bool |  |
| **IsServerLicense** | bool |  |
