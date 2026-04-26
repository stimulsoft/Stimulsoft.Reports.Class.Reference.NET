---
title: "StiTextChangedEventArgs Class"
---

## StiTextChangedEventArgs Class

**Namespace:** `Stimulsoft.Report.Events`

Describes an argument for the event TextChanged.

### Inheritance

Inherits from: EventArgs  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTextChangedEventArgs**(string oldValue, string newValue) | Creates a new object of the type StiTextChangedEventArgs. |

**StiTextChangedEventArgs**(**oldValue**: string, **newValue**: string)

Creates a new object of the type StiTextChangedEventArgs.

**Parameters**

- **oldValue** (string) — Old value of text.  
- **newValue** (string) — New value of text.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **NewValue** | string | Gets or sets the new value of text. |
| **OldValue** | string | Gets or sets the old value of text. |
