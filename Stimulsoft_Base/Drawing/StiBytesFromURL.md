---
title: "StiBytesFromURL Class"
---

## StiBytesFromURL Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowCacheFails** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Load** `static` | byte[] | Loads bytes from the specified hyperlink. |
| **LoadAsync** `static` | Task<byte[]> | Loads asynchronously bytes from the specified hyperlink. |
| **TryLoad** `static` | byte[] | Tries to load bytes from the specified hyperlink. |

---

### Method Details

#### Load `static`

**Load**(**url**: string, **cookieContainer**: CookieContainer, **headers**: NameValueCollection): byte[]

Loads bytes from the specified hyperlink.

**Parameters**

- **url** (string)  
- **cookieContainer** (CookieContainer)  
- **headers** (NameValueCollection)  

**Returns** byte[]


---

#### LoadAsync `static`

**LoadAsync**(**url**: string, **cookieContainer**: CookieContainer, **headers**: NameValueCollection): Task<byte[]>

Loads asynchronously bytes from the specified hyperlink.

**Parameters**

- **url** (string)  
- **cookieContainer** (CookieContainer)  
- **headers** (NameValueCollection)  

**Returns** Task<byte[]>


---

#### TryLoad `static`

**TryLoad**(**url**: string, **cookieContainer**: CookieContainer, **headers**: NameValueCollection): byte[]

Tries to load bytes from the specified hyperlink.

**Parameters**

- **url** (string)  
- **cookieContainer** (CookieContainer)  
- **headers** (NameValueCollection)  

**Returns** byte[]

