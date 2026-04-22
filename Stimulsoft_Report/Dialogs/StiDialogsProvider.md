---
title: "StiDialogsProvider Class"
---

## StiDialogsProvider Class

**Namespace:** `Stimulsoft.Report.Dialogs`  
**Assembly:** `Stimulsoft.Report`

This class provide base service for dialogs rendering.

```csharp
public abstract class StiDialogsProvider
```

### Inheritance

Inherits from: [StiService](../../Stimulsoft_Base/Services/StiService.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **GuiMode** | [StiGuiMode](../../Stimulsoft_Base/StiGuiMode.md) |  |
| **Report** | [StiReport](../StiReport.md) |  |

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

### Events

| Event | Type | Description |
| --- | --- | --- |
| **ButtonClick** | EventHandler |  |
| **EventFired** | EventHandler |  |
