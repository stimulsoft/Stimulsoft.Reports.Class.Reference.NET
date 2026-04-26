---
title: "LookaheadStream<T> Class"
---

## LookaheadStream<T> Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Misc`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Consume** | void |  |
| **Dequeue** | T |  |
| **Fill** | void |  |
| **IsEndOfFile** | bool |  |
| **LB** | T |  |
| **LT** | T |  |
| **Mark** | int |  |
| **NextElement** | T |  |
| **Release** | void |  |
| **Reset** | void |  |
| **Rewind** *(+1 overloads)* | void |  |
| **Seek** | void |  |
| **SyncAhead** | void |  |

---

### Method Details

#### Consume

**Consume**(): void


---

#### Dequeue

**Dequeue**(): T

**Returns** T


---

#### Fill

**Fill**(**n**: int): void

**Parameters**

- **n** (int)  


---

#### IsEndOfFile

**IsEndOfFile**(**o**: T): bool

**Parameters**

- **o** (T)  

**Returns** bool


---

#### LB

**LB**(**k**: int): T

**Parameters**

- **k** (int)  

**Returns** T


---

#### LT

**LT**(**k**: int): T

**Parameters**

- **k** (int)  

**Returns** T


---

#### Mark

**Mark**(): int

**Returns** int


---

#### NextElement

**NextElement**(): T

**Returns** T


---

#### Release

**Release**(**marker**: int): void

**Parameters**

- **marker** (int)  


---

#### Reset

**Reset**(): void


---

#### Rewind

**Rewind**(**marker**: int): void

**Parameters**

- **marker** (int)  

---

**Rewind**(): void


---

#### Seek

**Seek**(**index**: int): void

**Parameters**

- **index** (int)  


---

#### SyncAhead

**SyncAhead**(**need**: int): void

**Parameters**

- **need** (int)  

