---
title: "StiOddEvenStylesHelper Class"
---

## StiOddEvenStylesHelper Class

**Namespace:** `Stimulsoft.Report.Engine`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyOddEvenStyles** `static` | StiBaseStyle | Applies OddStyle and EvenStyle to the specified container that is formed on the base of a band that realizes the IStiOddEvenStyles interface. |

---

### Method Details

#### ApplyOddEvenStyles `static`

**ApplyOddEvenStyles**(**report**: [StiReport](../root/StiReport.md), **styles**: [IStiOddEvenStyles](../Components/IStiOddEvenStyles.md), **cont**: StiContainer): StiBaseStyle

Applies OddStyle and EvenStyle to the specified container that is formed on the base of a band that realizes the IStiOddEvenStyles interface.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — The report.  
- **styles** ([IStiOddEvenStyles](../Components/IStiOddEvenStyles.md)) — A band that realizes the IStiOddEvenStyles interface that formed the specified container.  
- **cont** (StiContainer) — A container formed of the specified band.  

**Returns** StiBaseStyle

