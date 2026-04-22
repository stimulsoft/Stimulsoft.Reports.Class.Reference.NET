---
title: "StiPagePaintEventArgs Class"
---

## StiPagePaintEventArgs Class

**Namespace:** `Stimulsoft.Report.Events`  
**Assembly:** `Stimulsoft.Report`

Describes an argument for the events PagePainting and PagePainted.

```csharp
public class StiPagePaintEventArgs
```

### Inheritance

Inherits from: EventArgs  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ClientRectangle** | Rectangle | Gets client rectangle. |
| **ClipRectangle** | Rectangle | Gets clip rectangle. |
| **FullRectangle** | Rectangle | Gets full rectangle. |
| **Graphics** | [Graphics](../../Stimulsoft_Drawing/Graphics.md) | Gets page graphics. |
| **IsDesigning** | bool | Gets value which indicates page is designing. |
| **IsPrinting** | bool | Gets value which indicates page is printing. |
