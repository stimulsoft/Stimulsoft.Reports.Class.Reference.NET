---
title: "StiMathHelper Class"
---

## StiMathHelper Class

**Namespace:** `Stimulsoft.Base.Helpers`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **TryToLoadAssembly** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetMatmML** `static` | string |  |
| **GetSvg** `static` | string |  |

---

### Method Details

#### GetMatmML `static`

**GetMatmML**(**latextContent**: string): string

**Parameters**

- **latextContent** (string)  

**Returns** string


---

#### GetSvg `static`

**GetSvg**(**matmMLContent**: string, **fontSize**: float, **colorHex**: string): string

**Parameters**

- **matmMLContent** (string)  
- **fontSize** (float)  
- **colorHex** (string)  

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **AssemblyName** | string |  |
| **AssemblyVersion** | string |  |
| **IsMathAssemblyLoaded** | bool |  |
