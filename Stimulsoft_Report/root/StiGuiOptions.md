---
title: "StiGuiOptions Class"
---

## StiGuiOptions Class

**Namespace:** `Stimulsoft.Report`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ProgressGdiType** `static` | Type |  |
| **ProgressWpfType** `static` | Type |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDotMatrixViewerForm** `static` | [IStiViewerForm](../Viewer/IStiViewerForm.md) |  |
| **GetDotMatrixViewerFormWithRibbonGUI** `static` | [IStiViewerForm](../Viewer/IStiViewerForm.md) |  |
| **GetExportFormRunner** `static` | [IStiFormRunner](../Helpers/IStiFormRunner.md) |  |
| **GetProgressInformation** `static` *(+1 overloads)* | [IStiProgressInformation](IStiProgressInformation.md) |  |
| **GetViewerForm** `static` | [IStiViewerForm](../Viewer/IStiViewerForm.md) |  |
| **GetViewerFormWithRibbonGUI** `static` | [IStiViewerForm](../Viewer/IStiViewerForm.md) |  |

---

### Method Details

#### GetDotMatrixViewerForm `static`

**GetDotMatrixViewerForm**(**report**: [StiReport](StiReport.md), **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): [IStiViewerForm](../Viewer/IStiViewerForm.md)

**Parameters**

- **report** ([StiReport](StiReport.md))  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  

**Returns** [IStiViewerForm](../Viewer/IStiViewerForm.md)


---

#### GetDotMatrixViewerFormWithRibbonGUI `static`

**GetDotMatrixViewerFormWithRibbonGUI**(**report**: [StiReport](StiReport.md), **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): [IStiViewerForm](../Viewer/IStiViewerForm.md)

**Parameters**

- **report** ([StiReport](StiReport.md))  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  

**Returns** [IStiViewerForm](../Viewer/IStiViewerForm.md)


---

#### GetExportFormRunner `static`

**GetExportFormRunner**(**formName**: string, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md), **ownerWindow**: object): [IStiFormRunner](../Helpers/IStiFormRunner.md)

**Parameters**

- **formName** (string)  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  
- **ownerWindow** (object)  

**Returns** [IStiFormRunner](../Helpers/IStiFormRunner.md)


---

#### GetProgressInformation `static`

**GetProgressInformation**(**guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): [IStiProgressInformation](IStiProgressInformation.md)

**Parameters**

- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  

**Returns** [IStiProgressInformation](IStiProgressInformation.md)

---

**GetProgressInformation**(**ownerForm**: object, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): [IStiProgressInformation](IStiProgressInformation.md)

**Parameters**

- **ownerForm** (object)  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  

**Returns** [IStiProgressInformation](IStiProgressInformation.md)


---

#### GetViewerForm `static`

**GetViewerForm**(**report**: [StiReport](StiReport.md), **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): [IStiViewerForm](../Viewer/IStiViewerForm.md)

**Parameters**

- **report** ([StiReport](StiReport.md))  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  

**Returns** [IStiViewerForm](../Viewer/IStiViewerForm.md)


---

#### GetViewerFormWithRibbonGUI `static`

**GetViewerFormWithRibbonGUI**(**report**: [StiReport](StiReport.md), **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): [IStiViewerForm](../Viewer/IStiViewerForm.md)

**Parameters**

- **report** ([StiReport](StiReport.md))  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  

**Returns** [IStiViewerForm](../Viewer/IStiViewerForm.md)

