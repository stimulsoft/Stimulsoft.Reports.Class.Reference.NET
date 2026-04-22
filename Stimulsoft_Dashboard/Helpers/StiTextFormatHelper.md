---
title: "StiTextFormatHelper Class"
---

## StiTextFormatHelper Class

**Namespace:** `Stimulsoft.Dashboard.Helpers`  
**Assembly:** `Stimulsoft.Dashboard`

This class help in working with text formatting in the table element.

```csharp
public static class StiTextFormatHelper
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DefaultCurrencyFormat** `static` | [StiCurrencyFormatService](../../Stimulsoft_Report/Components/TextFormats/StiCurrencyFormatService.md) |  |
| **DefaultGeneralFormat** `static` | [StiGeneralFormatService](../../Stimulsoft_Report/Components/TextFormats/StiGeneralFormatService.md) |  |
| **DefaultPercentageFormat** `static` | [StiPercentageFormatService](../../Stimulsoft_Report/Components/TextFormats/StiPercentageFormatService.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Format** `static` | string | Returns a string with format based on the specified StiFormatService object and a value. |
| **FormatAsPercentage** `static` *(+1 overloads)* | string | Returns a string with percentage format based on a value. |
| **FormatBasedOnColumnType** `static` *(+1 overloads)* | string | Creates a string with a formatting related to the specified table column. |
