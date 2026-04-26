---
title: "StiWinDialogsProvider Class"
---

## StiWinDialogsProvider Class

**Namespace:** `Stimulsoft.Report.Dialogs`

This class provide forms rendering.

### Inheritance

Inherits from: [StiDialogsProvider](StiDialogsProvider.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiWinDialogsProvider**() |  |
| **StiWinDialogsProvider**([StiReport](../root/StiReport.md) report) |  |

**StiWinDialogsProvider**()

---

**StiWinDialogsProvider**(**report**: [StiReport](../root/StiReport.md))

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Form** | Form |  |
| **Report** | [StiReport](../root/StiReport.md) |  |

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

---

### Method Details

#### CloseForm

**CloseForm**(): void


---

#### ConvertButtonToReportControl

**ConvertButtonToReportControl**(**buttonControl**: [StiButtonControl](StiButtonControl.md), **button**: Control): void

**Parameters**

- **buttonControl** ([StiButtonControl](StiButtonControl.md))  
- **button** (Control)  


---

#### ConvertCheckBoxToReportControl

**ConvertCheckBoxToReportControl**(**checkBoxControl**: StiCheckBoxControl, **checkBox**: Control): void

**Parameters**

- **checkBoxControl** (StiCheckBoxControl)  
- **checkBox** (Control)  


---

#### ConvertCheckedListBoxToReportControl

**ConvertCheckedListBoxToReportControl**(**checkedListBoxControl**: [StiCheckedListBoxControl](StiCheckedListBoxControl.md), **checkedListBox**: CheckedListBox): void

**Parameters**

- **checkedListBoxControl** ([StiCheckedListBoxControl](StiCheckedListBoxControl.md))  
- **checkedListBox** (CheckedListBox)  


---

#### ConvertComboBoxToReportControl

**ConvertComboBoxToReportControl**(**comboBoxControl**: [StiComboBoxControl](StiComboBoxControl.md), **comboBox**: ComboBox): void

**Parameters**

- **comboBoxControl** ([StiComboBoxControl](StiComboBoxControl.md))  
- **comboBox** (ComboBox)  


---

#### ConvertControlToReportControl

**ConvertControlToReportControl**(**reportControl**: StiReportControl, **control**: Control): void

**Parameters**

- **reportControl** (StiReportControl)  
- **control** (Control)  


---

#### ConvertControlsToDialogs

**ConvertControlsToDialogs**(**parentControl**: Control, **control**: StiReportControl): void

**Parameters**

- **parentControl** (Control)  
- **control** (StiReportControl)  


---

#### ConvertDateTimePickerToReportControl

**ConvertDateTimePickerToReportControl**(**dateTimePickerControl**: StiDateTimePickerControl, **dateTimePicker**: DateTimePicker): void

**Parameters**

- **dateTimePickerControl** (StiDateTimePickerControl)  
- **dateTimePicker** (DateTimePicker)  


---

#### ConvertDialogsToControls

**ConvertDialogsToControls**(**parentControl**: Control, **control**: StiReportControl, **tabIndex**: int): void

**Parameters**

- **parentControl** (Control)  
- **control** (StiReportControl)  
- **tabIndex** (int)  


---

#### ConvertGridToReportControl

**ConvertGridToReportControl**(**gridControl**: StiGridControl, **grid**: Control): void

**Parameters**

- **gridControl** (StiGridControl)  
- **grid** (Control)  


---

#### ConvertGroupBoxToReportControl

**ConvertGroupBoxToReportControl**(**groupBoxControl**: [StiGroupBoxControl](StiGroupBoxControl.md), **groupBox**: Control): void

**Parameters**

- **groupBoxControl** ([StiGroupBoxControl](StiGroupBoxControl.md))  
- **groupBox** (Control)  


---

#### ConvertLabelToReportControl

**ConvertLabelToReportControl**(**labelControl**: StiLabelControl, **label**: Control): void

**Parameters**

- **labelControl** (StiLabelControl)  
- **label** (Control)  


---

#### ConvertListBoxToReportControl

**ConvertListBoxToReportControl**(**listBoxControl**: [StiListBoxControl](StiListBoxControl.md), **listBox**: ListBox): void

**Parameters**

- **listBoxControl** ([StiListBoxControl](StiListBoxControl.md))  
- **listBox** (ListBox)  


---

#### ConvertListViewToReportControl

**ConvertListViewToReportControl**(**listViewControl**: [StiListViewControl](StiListViewControl.md), **listView**: ListView): void

**Parameters**

- **listViewControl** ([StiListViewControl](StiListViewControl.md))  
- **listView** (ListView)  


---

#### ConvertLookUpBoxToReportControl

**ConvertLookUpBoxToReportControl**(**lookUpBoxControl**: [StiLookUpBoxControl](StiLookUpBoxControl.md), **lookUpBox**: [StiDialogLookUpBox](../Controls/StiDialogLookUpBox.md)): void

**Parameters**

- **lookUpBoxControl** ([StiLookUpBoxControl](StiLookUpBoxControl.md))  
- **lookUpBox** ([StiDialogLookUpBox](../Controls/StiDialogLookUpBox.md))  


---

#### ConvertNumericUpDownToReportControl

**ConvertNumericUpDownToReportControl**(**numericUpDownControl**: [StiNumericUpDownControl](StiNumericUpDownControl.md), **numericUpDown**: NumericUpDown): void

**Parameters**

- **numericUpDownControl** ([StiNumericUpDownControl](StiNumericUpDownControl.md))  
- **numericUpDown** (NumericUpDown)  


---

#### ConvertPanelToReportControl

**ConvertPanelToReportControl**(**panelControl**: [StiPanelControl](StiPanelControl.md), **panel**: Control): void

**Parameters**

- **panelControl** ([StiPanelControl](StiPanelControl.md))  
- **panel** (Control)  


---

#### ConvertPictureBoxToReportControl

**ConvertPictureBoxToReportControl**(**pictureBoxControl**: StiPictureBoxControl, **pictureBox**: Control): void

**Parameters**

- **pictureBoxControl** (StiPictureBoxControl)  
- **pictureBox** (Control)  


---

#### ConvertRadioButtonToReportControl

**ConvertRadioButtonToReportControl**(**radioButtonControl**: [StiRadioButtonControl](StiRadioButtonControl.md), **radioButton**: Control): void

**Parameters**

- **radioButtonControl** ([StiRadioButtonControl](StiRadioButtonControl.md))  
- **radioButton** (Control)  


---

#### ConvertReportControlToButton

**ConvertReportControlToButton**(**buttonControl**: [StiButtonControl](StiButtonControl.md)): Control

**Parameters**

- **buttonControl** ([StiButtonControl](StiButtonControl.md))  

**Returns** Control


---

#### ConvertReportControlToCheckBox

**ConvertReportControlToCheckBox**(**checkBoxControl**: StiCheckBoxControl): Control

**Parameters**

- **checkBoxControl** (StiCheckBoxControl)  

**Returns** Control


---

#### ConvertReportControlToCheckedListBox

**ConvertReportControlToCheckedListBox**(**checkedListBoxControl**: [StiCheckedListBoxControl](StiCheckedListBoxControl.md)): Control

**Parameters**

- **checkedListBoxControl** ([StiCheckedListBoxControl](StiCheckedListBoxControl.md))  

**Returns** Control


---

#### ConvertReportControlToComboBox

**ConvertReportControlToComboBox**(**comboBoxControl**: [StiComboBoxControl](StiComboBoxControl.md)): Control

**Parameters**

- **comboBoxControl** ([StiComboBoxControl](StiComboBoxControl.md))  

**Returns** Control


---

#### ConvertReportControlToControl

**ConvertReportControlToControl**(**control**: Control, **reportControl**: StiReportControl): void

**Parameters**

- **control** (Control)  
- **reportControl** (StiReportControl)  


---

#### ConvertReportControlToCustomControl

**ConvertReportControlToCustomControl**(**customControl**: StiCustomControl): Control

**Parameters**

- **customControl** (StiCustomControl)  

**Returns** Control


---

#### ConvertReportControlToDateTimePicker

**ConvertReportControlToDateTimePicker**(**dateTimePickerControl**: StiDateTimePickerControl): Control

**Parameters**

- **dateTimePickerControl** (StiDateTimePickerControl)  

**Returns** Control


---

#### ConvertReportControlToForm

**ConvertReportControlToForm**(**formControl**: StiForm): void

**Parameters**

- **formControl** (StiForm)  


---

#### ConvertReportControlToGrid

**ConvertReportControlToGrid**(**gridControl**: StiGridControl): Control

**Parameters**

- **gridControl** (StiGridControl)  

**Returns** Control


---

#### ConvertReportControlToGroupBox

**ConvertReportControlToGroupBox**(**groupBoxControl**: [StiGroupBoxControl](StiGroupBoxControl.md)): Control

**Parameters**

- **groupBoxControl** ([StiGroupBoxControl](StiGroupBoxControl.md))  

**Returns** Control


---

#### ConvertReportControlToLabel

**ConvertReportControlToLabel**(**labelControl**: StiLabelControl): Control

**Parameters**

- **labelControl** (StiLabelControl)  

**Returns** Control


---

#### ConvertReportControlToListBox

**ConvertReportControlToListBox**(**listBoxControl**: [StiListBoxControl](StiListBoxControl.md)): Control

**Parameters**

- **listBoxControl** ([StiListBoxControl](StiListBoxControl.md))  

**Returns** Control


---

#### ConvertReportControlToListView

**ConvertReportControlToListView**(**listViewControl**: [StiListViewControl](StiListViewControl.md)): Control

**Parameters**

- **listViewControl** ([StiListViewControl](StiListViewControl.md))  

**Returns** Control


---

#### ConvertReportControlToLookUpBox

**ConvertReportControlToLookUpBox**(**lookUpBoxControl**: [StiLookUpBoxControl](StiLookUpBoxControl.md)): Control

**Parameters**

- **lookUpBoxControl** ([StiLookUpBoxControl](StiLookUpBoxControl.md))  

**Returns** Control


---

#### ConvertReportControlToNumericUpDown

**ConvertReportControlToNumericUpDown**(**numericUpDownControl**: [StiNumericUpDownControl](StiNumericUpDownControl.md)): Control

**Parameters**

- **numericUpDownControl** ([StiNumericUpDownControl](StiNumericUpDownControl.md))  

**Returns** Control


---

#### ConvertReportControlToPanel

**ConvertReportControlToPanel**(**panelControl**: [StiPanelControl](StiPanelControl.md)): Control

**Parameters**

- **panelControl** ([StiPanelControl](StiPanelControl.md))  

**Returns** Control


---

#### ConvertReportControlToPictureBox

**ConvertReportControlToPictureBox**(**pictureBoxControl**: StiPictureBoxControl): Control

**Parameters**

- **pictureBoxControl** (StiPictureBoxControl)  

**Returns** Control


---

#### ConvertReportControlToRadioButton

**ConvertReportControlToRadioButton**(**radioButtonControl**: [StiRadioButtonControl](StiRadioButtonControl.md)): Control

**Parameters**

- **radioButtonControl** ([StiRadioButtonControl](StiRadioButtonControl.md))  

**Returns** Control


---

#### ConvertReportControlToRichTextBox

**ConvertReportControlToRichTextBox**(**textBoxControl**: StiRichTextBoxControl): Control

**Parameters**

- **textBoxControl** (StiRichTextBoxControl)  

**Returns** Control


---

#### ConvertReportControlToTextBox

**ConvertReportControlToTextBox**(**textBoxControl**: StiTextBoxControl): Control

**Parameters**

- **textBoxControl** (StiTextBoxControl)  

**Returns** Control


---

#### ConvertReportControlToTreeView

**ConvertReportControlToTreeView**(**treeViewControl**: [StiTreeViewControl](StiTreeViewControl.md)): Control

**Parameters**

- **treeViewControl** ([StiTreeViewControl](StiTreeViewControl.md))  

**Returns** Control


---

#### ConvertRichTextBoxToReportControl

**ConvertRichTextBoxToReportControl**(**textBoxControl**: StiRichTextBoxControl, **textBox**: Control): void

**Parameters**

- **textBoxControl** (StiRichTextBoxControl)  
- **textBox** (Control)  


---

#### ConvertTextBoxToReportControl

**ConvertTextBoxToReportControl**(**textBoxControl**: StiTextBoxControl, **textBox**: Control): void

**Parameters**

- **textBoxControl** (StiTextBoxControl)  
- **textBox** (Control)  


---

#### ConvertTreeViewToReportControl

**ConvertTreeViewToReportControl**(**treeViewControl**: [StiTreeViewControl](StiTreeViewControl.md), **treeView**: TreeView): void

**Parameters**

- **treeViewControl** ([StiTreeViewControl](StiTreeViewControl.md))  
- **treeView** (TreeView)  


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

#### FormToReportControl

**FormToReportControl**(**formControl**: StiForm): void

**Parameters**

- **formControl** (StiForm)  


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

Render form.

**Parameters**

- **formControl** ([IStiForm](IStiForm.md))  

**Returns** bool

