---
title: "BitSet Class"
---

## BitSet Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **BitSet**() |  |
| **BitSet**(ulongbits ) |  |
| **BitSet**(IEnumerable<int> items) |  |
| **BitSet**(int nbits) |  |

**BitSet**()

---

**BitSet**(****: ulongbits)

**Parameters**

- **** (ulongbits)  

---

**BitSet**(**items**: IEnumerable<int>)

**Parameters**

- **items** (IEnumerable<int>)  

---

**BitSet**(**nbits**: int)

**Parameters**

- **nbits** (int)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** | void |  |
| **Clone** | object |  |
| **Equals** | bool |  |
| **GetHashCode** | int |  |
| **GrowToInclude** | void |  |
| **IsNil** | bool |  |
| **LengthInLongWords** | int |  |
| **Member** | bool |  |
| **NumBits** | int |  |
| **Of** `static` *(+3 overloads)* | [BitSet](BitSet.md) |  |
| **Or** | [BitSet](BitSet.md) |  |
| **OrInPlace** | void |  |
| **Remove** | void |  |
| **Size** | int |  |
| **ToArray** | int[] |  |
| **ToString** *(+1 overloads)* | string |  |

---

### Method Details

#### Add

**Add**(**el**: int): void

**Parameters**

- **el** (int)  


---

#### Clone

**Clone**(): object

**Returns** object


---

#### Equals

**Equals**(**other**: object): bool

**Parameters**

- **other** (object)  

**Returns** bool


---

#### GetHashCode

**GetHashCode**(): int

**Returns** int


---

#### GrowToInclude

**GrowToInclude**(**bit**: int): void

**Parameters**

- **bit** (int)  


---

#### IsNil

**IsNil**(): bool

**Returns** bool


---

#### LengthInLongWords

**LengthInLongWords**(): int

**Returns** int


---

#### Member

**Member**(**el**: int): bool

**Parameters**

- **el** (int)  

**Returns** bool


---

#### NumBits

**NumBits**(): int

**Returns** int


---

#### Of `static`

**Of**(**el**: int): [BitSet](BitSet.md)

**Parameters**

- **el** (int)  

**Returns** [BitSet](BitSet.md)

---

**Of**(**a**: int, **b**: int): [BitSet](BitSet.md)

**Parameters**

- **a** (int)  
- **b** (int)  

**Returns** [BitSet](BitSet.md)

---

**Of**(**a**: int, **b**: int, **c**: int): [BitSet](BitSet.md)

**Parameters**

- **a** (int)  
- **b** (int)  
- **c** (int)  

**Returns** [BitSet](BitSet.md)

---

**Of**(**a**: int, **b**: int, **c**: int, **d**: int): [BitSet](BitSet.md)

**Parameters**

- **a** (int)  
- **b** (int)  
- **c** (int)  
- **d** (int)  

**Returns** [BitSet](BitSet.md)


---

#### Or

**Or**(**a**: [BitSet](BitSet.md)): [BitSet](BitSet.md)

**Parameters**

- **a** ([BitSet](BitSet.md))  

**Returns** [BitSet](BitSet.md)


---

#### OrInPlace

**OrInPlace**(**a**: [BitSet](BitSet.md)): void

**Parameters**

- **a** ([BitSet](BitSet.md))  


---

#### Remove

**Remove**(**el**: int): void

**Parameters**

- **el** (int)  


---

#### Size

**Size**(): int

**Returns** int


---

#### ToArray

**ToArray**(): int[]

**Returns** int[]


---

#### ToString

**ToString**(): string

**Returns** string

---

**ToString**(****: stringtokenNames): string

**Parameters**

- **** (stringtokenNames)  

**Returns** string

