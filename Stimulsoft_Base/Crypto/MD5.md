---
title: "MD5 Class"
---

## MD5 Class

**Namespace:** `Stimulsoft.Base.Crypto`

Implementation of MD5 as outlined in "Handbook of Applied Cryptography", pages 346 - 347.

### Constructors

| Constructor | Description |
| --- | --- |
| **MD5**() | Creates a new instance |

**MD5**()

Creates a new instance


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BlockUpdate** | void | Update hash by byte array |
| **GetHash** | byte[] | Get resulting hash |
| **Reset** | void | Reset the chaining variables to the initial values. |
| **Update** | void | Update hash by one byte |

---

### Method Details

#### BlockUpdate

**BlockUpdate**(****: byteinput, **inOff**: int, **length**: int): void

Update hash by byte array

**Parameters**

- **** (byteinput)  
- **inOff** (int) — Offset of the first element  
- **length** (int) — Count of elements  


---

#### GetHash

**GetHash**(): byte[]

Get resulting hash

**Returns** byte[] — Hash value


---

#### Reset

**Reset**(): void

Reset the chaining variables to the initial values.


---

#### Update

**Update**(**input**: byte): void

Update hash by one byte

**Parameters**

- **input** (byte) — Input byte  

