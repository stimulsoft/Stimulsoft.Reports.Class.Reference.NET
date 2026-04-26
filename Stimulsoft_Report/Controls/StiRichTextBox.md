---
title: "StiRichTextBox Class"
---

## StiRichTextBox Class

**Namespace:** `Stimulsoft.Report.Controls`

### Inheritance

Inherits from: RichTextBox  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRichTextBox**(bool drawTransparent) |  |

**StiRichTextBox**(**drawTransparent**: bool)

**Parameters**

- **drawTransparent** (bool)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **OnHandleCreated** | void |  |
| **SetSelectionBold** | bool |  |
| **SetSelectionFont** | bool |  |
| **SetSelectionItalic** | bool |  |
| **SetSelectionSize** | bool |  |
| **SetSelectionUnderlined** | bool |  |

---

### Method Details

#### OnHandleCreated

**OnHandleCreated**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


---

#### SetSelectionBold

**SetSelectionBold**(**bold**: bool): bool

**Parameters**

- **bold** (bool)  

**Returns** bool


---

#### SetSelectionFont

**SetSelectionFont**(**face**: string): bool

**Parameters**

- **face** (string)  

**Returns** bool


---

#### SetSelectionItalic

**SetSelectionItalic**(**italic**: bool): bool

**Parameters**

- **italic** (bool)  

**Returns** bool


---

#### SetSelectionSize

**SetSelectionSize**(**size**: int): bool

**Parameters**

- **size** (int)  

**Returns** bool


---

#### SetSelectionUnderlined

**SetSelectionUnderlined**(**underlined**: bool): bool

**Parameters**

- **underlined** (bool)  

**Returns** bool


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **bCharSet** | byte |  |
| **bLineSpacingRule** | byte |  |
| **bOutlineLevel** | byte |  |
| **bPitchAndFamily** | byte |  |
| **cTabCount** | short |  |
| **cbSize** | int |  |
| **cbSize** | int |  |
| **crTextColor** | Int32 |  |
| **dwEffects** | UInt32 |  |
| **dwMask** | uint |  |
| **dwMask** | UInt32 |  |
| **dxOffset** | int |  |
| **dxRightIndent** | int |  |
| **dxStartIndent** | int |  |
| **dyLineSpacing** | int |  |
| **dySpaceAfter** | int |  |
| **dySpaceBefore** | int |  |
| **rgxTabs** | int[] |  |
| **sStyle** | short |  |
| **szFaceName** | char[] |  |
| **wAlignment** | short |  |
| **wBorderSpace** | short |  |
| **wBorderWidth** | short |  |
| **wBorders** | short |  |
| **wNumbering** | short |  |
| **wNumberingStart** | short |  |
| **wNumberingStyle** | short |  |
| **wNumberingTab** | short |  |
| **wReserved** | short |  |
| **wShadingStyle** | short |  |
| **wShadingWeight** | short |  |
| **yHeight** | Int32 |  |
| **yOffset** | Int32 |  |
