---
title: "StiTextFormatHelper Class"
---

## StiTextFormatHelper Class

**Namespace:** `Stimulsoft.Dashboard.Helpers`

This class help in working with text formatting in the table element.

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

---

### Method Details

#### Format `static`

**Format**(**report**: [StiReport](../../Stimulsoft_Report/root/StiReport.md), **format**: StiFormatService, **value**: object): string

Returns a string with format based on the specified StiFormatService object and a value.

**Parameters**

- **report** ([StiReport](../../Stimulsoft_Report/root/StiReport.md))  
- **format** (StiFormatService)  
- **value** (object)  

**Returns** string


---

#### FormatAsPercentage `static`

**FormatAsPercentage**(**report**: [StiReport](../../Stimulsoft_Report/root/StiReport.md), **value**: object): string

Returns a string with percentage format based on a value.

**Parameters**

- **report** ([StiReport](../../Stimulsoft_Report/root/StiReport.md))  
- **value** (object)  

**Returns** string

---

**FormatAsPercentage**(**report**: [StiReport](../../Stimulsoft_Report/root/StiReport.md), **format**: StiFormatService, **value**: object): string

Returns a string with percentage format based on the specified StiFormatService object and a value.

**Parameters**

- **report** ([StiReport](../../Stimulsoft_Report/root/StiReport.md))  
- **format** (StiFormatService)  
- **value** (object)  

**Returns** string


---

#### FormatBasedOnColumnType `static`

**FormatBasedOnColumnType**(**component**: StiComponent, **column**: StiTableColumn, **value**: object): string

Creates a string with a formatting related to the specified table column.

**Parameters**

- **component** (StiComponent)  
- **column** (StiTableColumn)  
- **value** (object)  

**Returns** string

---

**FormatBasedOnColumnType**(**component**: StiComponent, **formatService**: StiFormatService, **column**: [IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md), **value**: object): string

**Parameters**

- **component** (StiComponent)  
- **formatService** (StiFormatService)  
- **column** ([IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md))  
- **value** (object)  

**Returns** string

