---
title: "StiDialogsProvider Class"
---

## StiDialogsProvider Class

**Namespace:** `Stimulsoft.Report.Dialogs`

This class provide base service for dialogs rendering.

### Inheritance

Inherits from: [StiService](../../Stimulsoft_Base/Services/StiService.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **GuiMode** | [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md) |  |
| **Report** | [StiReport](../root/StiReport.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CloseForm** | void |  |
| **CreateCheckBoxControl** | [IStiCheckBoxControl](IStiCheckBoxControl.md) |  |
| **CreateForm** | [IStiForm](IStiForm.md) |  |
| **CreateLabelControl** | [IStiLabelControl](IStiLabelControl.md) |  |
| **CreatePictureBoxControl** | [IStiPictureBoxControl](IStiPictureBoxControl.md) |  |
| **CreateTextBoxControl** | [IStiTextBoxControl](IStiTextBoxControl.md) |  |
| **DisposeForm** | void |  |
| **GetProvider** `static` | [StiDialogsProvider](StiDialogsProvider.md) |  |
| **InvokeButtonClick** | void |  |
| **InvokeEventFired** | void |  |
| **LoadForm** | void |  |
| **PrepareForm** | void |  |
| **Render** | bool | Render all forms in report. |
| **RenderForm** | bool |  |

---

### Method Details

#### CloseForm

**CloseForm**(): void


---

#### CreateCheckBoxControl

**CreateCheckBoxControl**(): [IStiCheckBoxControl](IStiCheckBoxControl.md)

**Returns** [IStiCheckBoxControl](IStiCheckBoxControl.md)


---

#### CreateForm

**CreateForm**(**report**: [StiReport](../root/StiReport.md)): [IStiForm](IStiForm.md)

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

**Returns** [IStiForm](IStiForm.md)


---

#### CreateLabelControl

**CreateLabelControl**(): [IStiLabelControl](IStiLabelControl.md)

**Returns** [IStiLabelControl](IStiLabelControl.md)


---

#### CreatePictureBoxControl

**CreatePictureBoxControl**(): [IStiPictureBoxControl](IStiPictureBoxControl.md)

**Returns** [IStiPictureBoxControl](IStiPictureBoxControl.md)


---

#### CreateTextBoxControl

**CreateTextBoxControl**(): [IStiTextBoxControl](IStiTextBoxControl.md)

**Returns** [IStiTextBoxControl](IStiTextBoxControl.md)


---

#### DisposeForm

**DisposeForm**(): void


---

#### GetProvider `static`

**GetProvider**(**report**: [StiReport](../root/StiReport.md)): [StiDialogsProvider](StiDialogsProvider.md)

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

**Returns** [StiDialogsProvider](StiDialogsProvider.md)


---

#### InvokeButtonClick

**InvokeButtonClick**(**sender**: object, **e**: EventArgs): void

**Parameters**

- **sender** (object)  
- **e** (EventArgs)  


---

#### InvokeEventFired

**InvokeEventFired**(**sender**: object, **e**: EventArgs): void

**Parameters**

- **sender** (object)  
- **e** (EventArgs)  


---

#### LoadForm

**LoadForm**(**formControl**: [IStiForm](IStiForm.md)): void

**Parameters**

- **formControl** ([IStiForm](IStiForm.md))  


---

#### PrepareForm

**PrepareForm**(): void


---

#### Render

**Render**(**report**: [StiReport](../root/StiReport.md), **startMode**: [StiFormStartMode](StiFormStartMode.md)): bool

Render all forms in report.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **startMode** ([StiFormStartMode](StiFormStartMode.md))  

**Returns** bool


---

#### RenderForm

**RenderForm**(**formControl**: [IStiForm](IStiForm.md)): bool

**Parameters**

- **formControl** ([IStiForm](IStiForm.md))  

**Returns** bool


### Events

| Event | Type | Description |
| --- | --- | --- |
| **ButtonClick** | EventHandler |  |
| **EventFired** | EventHandler |  |
