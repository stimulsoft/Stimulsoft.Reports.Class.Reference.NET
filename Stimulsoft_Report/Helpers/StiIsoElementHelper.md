---
title: "StiIsoElementHelper Class"
---

## StiIsoElementHelper Class

**Namespace:** `Stimulsoft.Report.Helpers`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetCountryFromAlpha2** `static` | [StiIsoCountry](StiIsoCountry.md) | Obtain ISO3166-1 Country based on its alpha2 code. |
| **GetCountryFromAlpha3** `static` | [StiIsoCountry](StiIsoCountry.md) | Gets ISO3166-1 Country based on its alpha3 code. |
| **GetCountryFromName** `static` | [StiIsoCountry](StiIsoCountry.md) | Gets ISO3166-1 Country based on its alpha3 code. Returns null, if country is not recognized. |
| **GetIsoAlpha2FromName** `static` | string | Gets ISO3166-1 Alpha2 code based on country name. Returns null, if country is not recognized. |
| **GetIsoAlpha3FromName** `static` | string | Gets ISO3166-1 Alpha3 code based on country name. Returns null, if country is not recognized. |

---

### Method Details

#### GetCountryFromAlpha2 `static`

**GetCountryFromAlpha2**(**alpha2**: string, **mapId**: string): [StiIsoCountry](StiIsoCountry.md)

Obtain ISO3166-1 Country based on its alpha2 code.

**Parameters**

- **alpha2** (string)  
- **mapId** (string)  

**Returns** [StiIsoCountry](StiIsoCountry.md)


---

#### GetCountryFromAlpha3 `static`

**GetCountryFromAlpha3**(**alpha3**: string, **mapId**: string): [StiIsoCountry](StiIsoCountry.md)

Gets ISO3166-1 Country based on its alpha3 code.

**Parameters**

- **alpha3** (string)  
- **mapId** (string)  

**Returns** [StiIsoCountry](StiIsoCountry.md)


---

#### GetCountryFromName `static`

**GetCountryFromName**(**name**: string, **mapId**: string): [StiIsoCountry](StiIsoCountry.md)

Gets ISO3166-1 Country based on its alpha3 code. Returns null, if country is not recognized.

**Parameters**

- **name** (string)  
- **mapId** (string)  

**Returns** [StiIsoCountry](StiIsoCountry.md)


---

#### GetIsoAlpha2FromName `static`

**GetIsoAlpha2FromName**(**name**: string, **mapId**: string): string

Gets ISO3166-1 Alpha2 code based on country name. Returns null, if country is not recognized.

**Parameters**

- **name** (string)  
- **mapId** (string)  

**Returns** string


---

#### GetIsoAlpha3FromName `static`

**GetIsoAlpha3FromName**(**name**: string, **mapId**: string): string

Gets ISO3166-1 Alpha3 code based on country name. Returns null, if country is not recognized.

**Parameters**

- **name** (string)  
- **mapId** (string)  

**Returns** string

