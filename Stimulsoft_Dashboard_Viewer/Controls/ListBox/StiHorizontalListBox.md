---
title: "StiHorizontalListBox Class"
---

## StiHorizontalListBox Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Controls.ListBox`  
**Assembly:** `Stimulsoft.Dashboard.Viewer`

```csharp
public class StiHorizontalListBox
```

### Inheritance

Inherits from: Panel  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiHorizontalListBox()` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **IsTransparent** | bool |  |
| **Items** | List<[StiListBoxItem](../../../Stimulsoft_Dashboard/Components/ListBox/StiListBoxItem.md)> |  |
| **MultiSelection** | bool |  |
| **NegativeInRed** | bool |  |
| **ScrollBar** | HScrollBar |  |
| **ShowRadioButtons** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **OnMouseDown** | void |  |
| **OnMouseHover** | void |  |
| **OnMouseLeave** | void |  |
| **OnMouseMove** | void |  |
| **OnPaint** | void |  |
| **OnSizeChanged** | void |  |
| **RefreshUI** | void |  |
| **ResetAllItemsSelection** | void |  |
| **ResetAllItemsSelectionAndSelectFirstOnly** | void |  |
| **SelectAllItems** | void |  |
| **SelectFirstItemOnly** | void |  |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **ItemSelectionChanged** | StiListBoxItemSelectionChangedEventHandler |  |
| **TrackingIndexChanged** | StiListBoxTrackingIndexChangedEventHandler |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **SelectedIndex** | int |  |
| **SelectedItem** | [StiListBoxItem](../../../Stimulsoft_Dashboard/Components/ListBox/StiListBoxItem.md) |  |
| **SelectedValue** | object |  |
