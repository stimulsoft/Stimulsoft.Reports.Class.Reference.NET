---
title: "StiDownloadCache Class"
---

## StiDownloadCache Class

**Namespace:** `Stimulsoft.Base`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Enabled** `static` | bool |  |
| **TicksDelayInProcess** `static` | int |  |
| **TicksToExpired** `static` | int |  |
| **TicksToFailedAttempt** `static` | int |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CheckExpiredUrls** `static` | void |  |
| **Clear** `static` | void |  |
| **Get** `static` | byte[] |  |

---

### Method Details

#### CheckExpiredUrls `static`

**CheckExpiredUrls**(): void


---

#### Clear `static`

**Clear**(): void


---

#### Get `static`

**Get**(**url**: string, **cookieContainer**: CookieContainer, **headers**: NameValueCollection): byte[]

**Parameters**

- **url** (string)  
- **cookieContainer** (CookieContainer)  
- **headers** (NameValueCollection)  

**Returns** byte[]


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Data** | byte[] |  |
| **Ticks** | int |  |
| **Url** | string |  |
