---
title: "FontFamily Class"
---

## FontFamily Class

**Namespace:** `Stimulsoft.Drawing`

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| **FontFamily**(string name) |  |
| **FontFamily**(string name, [FontCollection](../Text/FontCollection.md) fontCollection) |  |

**FontFamily**(**name**: string)

**Parameters**

- **name** (string)  

---

**FontFamily**(**name**: string, **fontCollection**: [FontCollection](../Text/FontCollection.md))

**Parameters**

- **name** (string)  
- **fontCollection** ([FontCollection](../Text/FontCollection.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **GetCellAscent** | int |  |
| **GetCellDescent** | int |  |
| **GetEmHeight** | int |  |
| **GetLineSpacing** | int |  |
| **GetName** | string |  |
| **IsStyleAvailable** | bool |  |
| **ToString** | string |  |

---

### Method Details

#### Dispose

**Dispose**(): void


---

#### GetCellAscent

**GetCellAscent**(**style**: System.Drawing.FontStyle): int

**Parameters**

- **style** (System.Drawing.FontStyle)  

**Returns** int


---

#### GetCellDescent

**GetCellDescent**(**style**: System.Drawing.FontStyle): int

**Parameters**

- **style** (System.Drawing.FontStyle)  

**Returns** int


---

#### GetEmHeight

**GetEmHeight**(**style**: System.Drawing.FontStyle): int

**Parameters**

- **style** (System.Drawing.FontStyle)  

**Returns** int


---

#### GetLineSpacing

**GetLineSpacing**(**style**: System.Drawing.FontStyle): int

**Parameters**

- **style** (System.Drawing.FontStyle)  

**Returns** int


---

#### GetName

**GetName**(**language**: int): string

**Parameters**

- **language** (int)  

**Returns** string


---

#### IsStyleAvailable

**IsStyleAvailable**(**style**: System.Drawing.FontStyle): bool

**Parameters**

- **style** (System.Drawing.FontStyle)  

**Returns** bool


---

#### ToString

**ToString**(): string

**Returns** string

