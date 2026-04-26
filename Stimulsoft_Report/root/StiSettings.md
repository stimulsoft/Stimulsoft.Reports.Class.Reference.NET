---
title: "StiSettings Class"
---

## StiSettings Class

**Namespace:** `Stimulsoft.Report`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clear** `static` | void |  |
| **ClearKey** `static` *(+1 overloads)* | void |  |
| **Get** `static` *(+1 overloads)* | object |  |
| **GetBool** `static` *(+1 overloads)* | bool |  |
| **GetCategory** `static` | Hashtable |  |
| **GetColor** `static` | Color |  |
| **GetDecimal** `static` *(+1 overloads)* | decimal |  |
| **GetDefaultReportSettingsPath** `static` | string |  |
| **GetDouble** `static` *(+1 overloads)* | double |  |
| **GetFloat** `static` *(+1 overloads)* | float |  |
| **GetInt** `static` *(+1 overloads)* | int |  |
| **GetLong** `static` *(+1 overloads)* | long |  |
| **GetStr** `static` *(+1 overloads)* | string |  |
| **Load** `static` *(+2 overloads)* | void |  |
| **ReLoad** `static` | void |  |
| **Save** `static` *(+2 overloads)* | void |  |
| **Set** `static` *(+1 overloads)* | void |  |

---

### Method Details

#### Clear `static`

**Clear**(): void


---

#### ClearKey `static`

**ClearKey**(**key**: string): void

**Parameters**

- **key** (string)  

---

**ClearKey**(**key**: string, **subkey**: string): void

**Parameters**

- **key** (string)  
- **subkey** (string)  


---

#### Get `static`

**Get**(**key**: string, **subkey**: string): object

**Parameters**

- **key** (string)  
- **subkey** (string)  

**Returns** object

---

**Get**(**key**: string, **subkey**: string, **nullValue**: object): object

**Parameters**

- **key** (string)  
- **subkey** (string)  
- **nullValue** (object)  

**Returns** object


---

#### GetBool `static`

**GetBool**(**key**: string, **subkey**: string): bool

**Parameters**

- **key** (string)  
- **subkey** (string)  

**Returns** bool

---

**GetBool**(**key**: string, **subkey**: string, **nullValue**: bool): bool

**Parameters**

- **key** (string)  
- **subkey** (string)  
- **nullValue** (bool)  

**Returns** bool


---

#### GetCategory `static`

**GetCategory**(**key**: string): Hashtable

**Parameters**

- **key** (string)  

**Returns** Hashtable


---

#### GetColor `static`

**GetColor**(**key**: string, **subkey**: string, **nullValue**: Color): Color

**Parameters**

- **key** (string)  
- **subkey** (string)  
- **nullValue** (Color)  

**Returns** Color


---

#### GetDecimal `static`

**GetDecimal**(**key**: string, **subkey**: string): decimal

**Parameters**

- **key** (string)  
- **subkey** (string)  

**Returns** decimal

---

**GetDecimal**(**key**: string, **subkey**: string, **nullValue**: decimal): decimal

**Parameters**

- **key** (string)  
- **subkey** (string)  
- **nullValue** (decimal)  

**Returns** decimal


---

#### GetDefaultReportSettingsPath `static`

**GetDefaultReportSettingsPath**(): string

**Returns** string


---

#### GetDouble `static`

**GetDouble**(**key**: string, **subkey**: string): double

**Parameters**

- **key** (string)  
- **subkey** (string)  

**Returns** double

---

**GetDouble**(**key**: string, **subkey**: string, **nullValue**: double): double

**Parameters**

- **key** (string)  
- **subkey** (string)  
- **nullValue** (double)  

**Returns** double


---

#### GetFloat `static`

**GetFloat**(**key**: string, **subkey**: string): float

**Parameters**

- **key** (string)  
- **subkey** (string)  

**Returns** float

---

**GetFloat**(**key**: string, **subkey**: string, **nullValue**: float): float

**Parameters**

- **key** (string)  
- **subkey** (string)  
- **nullValue** (float)  

**Returns** float


---

#### GetInt `static`

**GetInt**(**key**: string, **subkey**: string): int

**Parameters**

- **key** (string)  
- **subkey** (string)  

**Returns** int

---

**GetInt**(**key**: string, **subkey**: string, **nullValue**: int, **isZoom**: bool): int

**Parameters**

- **key** (string)  
- **subkey** (string)  
- **nullValue** (int)  
- **isZoom** (bool)  

**Returns** int


---

#### GetLong `static`

**GetLong**(**key**: string, **subkey**: string): long

**Parameters**

- **key** (string)  
- **subkey** (string)  

**Returns** long

---

**GetLong**(**key**: string, **subkey**: string, **nullValue**: long, **isZoom**: bool): long

**Parameters**

- **key** (string)  
- **subkey** (string)  
- **nullValue** (long)  
- **isZoom** (bool)  

**Returns** long


---

#### GetStr `static`

**GetStr**(**key**: string, **subkey**: string): string

**Parameters**

- **key** (string)  
- **subkey** (string)  

**Returns** string

---

**GetStr**(**key**: string, **subkey**: string, **nullValue**: string): string

**Parameters**

- **key** (string)  
- **subkey** (string)  
- **nullValue** (string)  

**Returns** string


---

#### Load `static`

**Load**(): void

---

**Load**(**file**: string): void

**Parameters**

- **file** (string)  

---

**Load**(**stream**: Stream): void

**Parameters**

- **stream** (Stream)  


---

#### ReLoad `static`

**ReLoad**(): void


---

#### Save `static`

**Save**(): void

---

**Save**(**file**: string): void

**Parameters**

- **file** (string)  

---

**Save**(**stream**: Stream): void

**Parameters**

- **stream** (Stream)  


---

#### Set `static`

**Set**(**key**: string, **subkey**: string, **value**: int, **isZoom**: bool): void

**Parameters**

- **key** (string)  
- **subkey** (string)  
- **value** (int)  
- **isZoom** (bool)  

---

**Set**(**key**: string, **subkey**: string, **value**: object): void

**Parameters**

- **key** (string)  
- **subkey** (string)  
- **value** (object)  

