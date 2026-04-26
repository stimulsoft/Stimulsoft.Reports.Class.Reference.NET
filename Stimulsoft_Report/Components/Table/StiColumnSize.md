---
title: "StiColumnSize Class"
---

## StiColumnSize Class

**Namespace:** `Stimulsoft.Report.Components.Table`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiColumnSize**(int size) |  |

**StiColumnSize**(**size**: int)

**Parameters**

- **size** (int)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** | void |  |
| **AddLastNotFixed** | void |  |
| **GetCountNotFixedColumn** | int |  |
| **GetCountNotFixedColumnAndNotMinSize** | int |  |
| **GetCountNotFixedColumnAndWidth** | int |  |
| **GetFixed** | bool |  |
| **GetWidth** | double |  |
| **Normalize** | void |  |
| **SetFixedColumn** | void |  |
| **SetMinWidths** | void |  |
| **SetWidth** | void |  |
| **Subtract** | void |  |

---

### Method Details

#### Add

**Add**(**indexCol**: int, **width**: double): void

**Parameters**

- **indexCol** (int)  
- **width** (double)  


---

#### AddLastNotFixed

**AddLastNotFixed**(**width**: double): void

**Parameters**

- **width** (double)  


---

#### GetCountNotFixedColumn

**GetCountNotFixedColumn**(): int

**Returns** int


---

#### GetCountNotFixedColumnAndNotMinSize

**GetCountNotFixedColumnAndNotMinSize**(): int

**Returns** int


---

#### GetCountNotFixedColumnAndWidth

**GetCountNotFixedColumnAndWidth**(): int

**Returns** int


---

#### GetFixed

**GetFixed**(**index**: int): bool

**Parameters**

- **index** (int)  

**Returns** bool


---

#### GetWidth

**GetWidth**(**indexCol**: int): double

**Parameters**

- **indexCol** (int)  

**Returns** double


---

#### Normalize

**Normalize**(): void


---

#### SetFixedColumn

**SetFixedColumn**(**indexCol**: int, **width**: double): void

**Parameters**

- **indexCol** (int)  
- **width** (double)  


---

#### SetMinWidths

**SetMinWidths**(**indexCol**: int, **minWidth**: double): void

**Parameters**

- **indexCol** (int)  
- **minWidth** (double)  


---

#### SetWidth

**SetWidth**(**indexCol**: int, **width**: double): void

**Parameters**

- **indexCol** (int)  
- **width** (double)  


---

#### Subtract

**Subtract**(**indexCol**: int, **width**: double, **checkMin**: bool): void

**Parameters**

- **indexCol** (int)  
- **width** (double)  
- **checkMin** (bool)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Length** | int |  |
