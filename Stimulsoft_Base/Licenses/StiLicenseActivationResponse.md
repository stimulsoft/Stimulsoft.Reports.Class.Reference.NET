---
title: "StiLicenseActivationResponse Class"
---

## StiLicenseActivationResponse Class

**Namespace:** `Stimulsoft.Base.Licenses`

### Inheritance

Inherits from: [StiLicenseObject](StiLicenseObject.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Exception** | string | An information about exception which occurs during activation process. |
| **LicenseKey** | [StiLicenseKey](StiLicenseKey.md) |  |
| **ResultNotice** | [StiNotice](../root/StiNotice.md) | A message about the running command. This Result can be skipped. |
| **ResultSuccess** | bool | True or False value which depend on the status of the running command. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateStik** | string |  |
| **Get** `static` *(+1 overloads)* | [StiLicenseActivationResponse](StiLicenseActivationResponse.md) |  |
| **MakeFine** `static` | [StiLicenseActivationResponse](StiLicenseActivationResponse.md) |  |
| **MakeWrong** `static` | [StiLicenseActivationResponse](StiLicenseActivationResponse.md) |  |

---

### Method Details

#### CreateStik

**CreateStik**(): string

**Returns** string


---

#### Get `static`

**Get**(****: bytebytes): [StiLicenseActivationResponse](StiLicenseActivationResponse.md)

**Parameters**

- **** (bytebytes)  

**Returns** [StiLicenseActivationResponse](StiLicenseActivationResponse.md)

---

**Get**(**str**: string): [StiLicenseActivationResponse](StiLicenseActivationResponse.md)

**Parameters**

- **str** (string)  

**Returns** [StiLicenseActivationResponse](StiLicenseActivationResponse.md)


---

#### MakeFine `static`

**MakeFine**(**licenseKey**: [StiLicenseKey](StiLicenseKey.md)): [StiLicenseActivationResponse](StiLicenseActivationResponse.md)

**Parameters**

- **licenseKey** ([StiLicenseKey](StiLicenseKey.md))  

**Returns** [StiLicenseActivationResponse](StiLicenseActivationResponse.md)


---

#### MakeWrong `static`

**MakeWrong**(**notice**: [StiNotice](../root/StiNotice.md)): [StiLicenseActivationResponse](StiLicenseActivationResponse.md)

**Parameters**

- **notice** ([StiNotice](../root/StiNotice.md))  

**Returns** [StiLicenseActivationResponse](StiLicenseActivationResponse.md)

