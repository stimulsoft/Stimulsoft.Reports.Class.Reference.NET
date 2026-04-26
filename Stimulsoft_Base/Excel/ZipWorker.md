---
title: "ZipWorker Class"
---

## ZipWorker Class

**Namespace:** `Stimulsoft.Base.Excel`

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| **ZipWorker**() |  |

**ZipWorker**()


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **Extract** | bool | Extracts the specified zip file stream. |
| **GetSharedStringsStream** | Stream | Gets the shared strings stream. |
| **GetStylesStream** | Stream | Gets the styles stream. |
| **GetWorkbookRelsStream** | Stream | Gets the workbook rels stream. |
| **GetWorkbookStream** | Stream | Gets the workbook stream. |
| **GetWorksheetStream** *(+1 overloads)* | Stream | Gets the worksheet stream. |

---

### Method Details

#### Dispose

**Dispose**(): void


---

#### Extract

**Extract**(**fileStream**: Stream): bool

Extracts the specified zip file stream.

**Parameters**

- **fileStream** (Stream) — The zip file stream.  

**Returns** bool


---

#### GetSharedStringsStream

**GetSharedStringsStream**(): Stream

Gets the shared strings stream.

**Returns** Stream


---

#### GetStylesStream

**GetStylesStream**(): Stream

Gets the styles stream.

**Returns** Stream


---

#### GetWorkbookRelsStream

**GetWorkbookRelsStream**(): Stream

Gets the workbook rels stream.

**Returns** Stream


---

#### GetWorkbookStream

**GetWorkbookStream**(): Stream

Gets the workbook stream.

**Returns** Stream


---

#### GetWorksheetStream

**GetWorksheetStream**(**sheetId**: int): Stream

Gets the worksheet stream.

**Parameters**

- **sheetId** (int) — The sheet id.  

**Returns** Stream

---

**GetWorksheetStream**(**sheetPath**: string): Stream

**Parameters**

- **sheetPath** (string)  

**Returns** Stream

