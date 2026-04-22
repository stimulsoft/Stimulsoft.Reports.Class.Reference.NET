---
title: "StiWinDialogsProvider Class"
---

## StiWinDialogsProvider Class

**Namespace:** `Stimulsoft.Report.Dialogs`  
**Assembly:** `Stimulsoft.Report`

This class provide forms rendering.

```csharp
public class StiWinDialogsProvider
```

### Inheritance

Inherits from: [StiDialogsProvider](StiDialogsProvider.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiWinDialogsProvider**() |  |
| **StiWinDialogsProvider**([StiReport](../StiReport.md) report) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Form** | Form |  |
| **Report** | [StiReport](../StiReport.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CloseForm** | void |  |
| **ConvertButtonToReportControl** | void |  |
| **ConvertCheckBoxToReportControl** | void |  |
| **ConvertCheckedListBoxToReportControl** | void |  |
| **ConvertComboBoxToReportControl** | void |  |
| **ConvertControlToReportControl** | void |  |
| **ConvertControlsToDialogs** | void |  |
| **ConvertDateTimePickerToReportControl** | void |  |
| **ConvertDialogsToControls** | void |  |
| **ConvertGridToReportControl** | void |  |
| **ConvertGroupBoxToReportControl** | void |  |
| **ConvertLabelToReportControl** | void |  |
| **ConvertListBoxToReportControl** | void |  |
| **ConvertListViewToReportControl** | void |  |
| **ConvertLookUpBoxToReportControl** | void |  |
| **ConvertNumericUpDownToReportControl** | void |  |
| **ConvertPanelToReportControl** | void |  |
| **ConvertPictureBoxToReportControl** | void |  |
| **ConvertRadioButtonToReportControl** | void |  |
| **ConvertReportControlToButton** | Control |  |
| **ConvertReportControlToCheckBox** | Control |  |
| **ConvertReportControlToCheckedListBox** | Control |  |
| **ConvertReportControlToComboBox** | Control |  |
| **ConvertReportControlToControl** | void |  |
| **ConvertReportControlToCustomControl** | Control |  |
| **ConvertReportControlToDateTimePicker** | Control |  |
| **ConvertReportControlToForm** | void |  |
| **ConvertReportControlToGrid** | Control |  |
| **ConvertReportControlToGroupBox** | Control |  |
| **ConvertReportControlToLabel** | Control |  |
| **ConvertReportControlToListBox** | Control |  |
| **ConvertReportControlToListView** | Control |  |
| **ConvertReportControlToLookUpBox** | Control |  |
| **ConvertReportControlToNumericUpDown** | Control |  |
| **ConvertReportControlToPanel** | Control |  |
| **ConvertReportControlToPictureBox** | Control |  |
| **ConvertReportControlToRadioButton** | Control |  |
| **ConvertReportControlToRichTextBox** | Control |  |
| **ConvertReportControlToTextBox** | Control |  |
| **ConvertReportControlToTreeView** | Control |  |
| **ConvertRichTextBoxToReportControl** | void |  |
| **ConvertTextBoxToReportControl** | void |  |
| **ConvertTreeViewToReportControl** | void |  |
| **CreateCheckBoxControl** | [IStiCheckBoxControl](IStiCheckBoxControl.md) |  |
| **CreateForm** | [IStiForm](IStiForm.md) |  |
| **CreateLabelControl** | [IStiLabelControl](IStiLabelControl.md) |  |
| **CreatePictureBoxControl** | [IStiPictureBoxControl](IStiPictureBoxControl.md) |  |
| **CreateTextBoxControl** | [IStiTextBoxControl](IStiTextBoxControl.md) |  |
| **DisposeForm** | void |  |
| **FormToReportControl** | void |  |
| **LoadForm** | void |  |
| **PrepareForm** | void |  |
| **Render** | bool | Render all forms in report. |
| **RenderForm** | bool | Render form. |
