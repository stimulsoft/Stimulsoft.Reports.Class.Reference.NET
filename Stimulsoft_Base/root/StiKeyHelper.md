---
title: "StiKeyHelper Class"
---

## StiKeyHelper Class

**Namespace:** `Stimulsoft.Base`

This class helps work with keys.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GenerateKey** `static` | string | Returns new generated key. |
| **GetOrGeneratedKey** `static` *(+1 overloads)* | string | Returns specified key if it is not empty. Otherwise returns new generated key. |
| **IsCorrectKey** `static` | bool | Returns true if the specified key is correct. |
| **IsEmptyKey** `static` *(+1 overloads)* | bool | Returns true if the specifeid key is empty. |
| **IsEqualKeys** `static` | bool | Returns true if both keys equals. |
| **IsKey** `static` | bool | Returns true if the specified key is not empty. |
| **SelectKey** `static` | string | Returns key1 if it is not empty. Otherwise returns key2. |

---

### Method Details

#### GenerateKey `static`

**GenerateKey**(): string

Returns new generated key.

**Returns** string


---

#### GetOrGeneratedKey `static`

**GetOrGeneratedKey**(**key**: string): string

Returns specified key if it is not empty. Otherwise returns new generated key.

**Parameters**

- **key** (string)  

**Returns** string

---

**GetOrGeneratedKey**(**key1**: string, **key2**: string): string

Returns key1 if it is not empty or key2 if it is not empty. Returns new generated key if both key1 and key2 is empty.

**Parameters**

- **key1** (string)  
- **key2** (string)  

**Returns** string


---

#### IsCorrectKey `static`

**IsCorrectKey**(**key**: string): bool

Returns true if the specified key is correct.

**Parameters**

- **key** (string)  

**Returns** bool


---

#### IsEmptyKey `static`

**IsEmptyKey**(**key**: string): bool

Returns true if the specifeid key is empty.

**Parameters**

- **key** (string)  

**Returns** bool

---

**IsEmptyKey**(**key1**: string, **key2**: string): bool

Returns true if both specifeid keys is empty.

**Parameters**

- **key1** (string)  
- **key2** (string)  

**Returns** bool


---

#### IsEqualKeys `static`

**IsEqualKeys**(**key1**: string, **key2**: string): bool

Returns true if both keys equals.

**Parameters**

- **key1** (string)  
- **key2** (string)  

**Returns** bool


---

#### IsKey `static`

**IsKey**(**key**: string): bool

Returns true if the specified key is not empty.

**Parameters**

- **key** (string)  

**Returns** bool


---

#### SelectKey `static`

**SelectKey**(**key1**: string, **key2**: string): string

Returns key1 if it is not empty. Otherwise returns key2.

**Parameters**

- **key1** (string)  
- **key2** (string)  

**Returns** string

