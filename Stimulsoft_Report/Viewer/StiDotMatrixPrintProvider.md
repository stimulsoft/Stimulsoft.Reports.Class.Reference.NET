---
title: "StiDotMatrixPrintProvider Class"
---

## StiDotMatrixPrintProvider Class

**Namespace:** `Stimulsoft.Report.Viewer`

This class provide print service.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **PrintToDotMatrixPrinter** `static` *(+3 overloads)* | void | Prints a report to default dot-matrix printer in the RAW mode in ASCII encoding. |

---

### Method Details

#### PrintToDotMatrixPrinter `static`

**PrintToDotMatrixPrinter**(**report**: [StiReport](../root/StiReport.md)): void

Prints a report to default dot-matrix printer in the RAW mode in ASCII encoding.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

---

**PrintToDotMatrixPrinter**(**report**: [StiReport](../root/StiReport.md), **printerName**: string): void

Prints a report to dot-matrix printer in the RAW mode in ASCII encoding.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **printerName** (string) — A name of a printer.  

---

**PrintToDotMatrixPrinter**(**report**: [StiReport](../root/StiReport.md), **printerName**: string, **encoding**: Encoding): void

Prints report to dot-matrix printer in the RAW mode.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **printerName** (string) — A name of a printer.  
- **encoding** (Encoding) — A parameter which sets text encoding.  

---

**PrintToDotMatrixPrinter**(**report**: [StiReport](../root/StiReport.md), **printerName**: string, **encoding**: Encoding, **fromPage**: int, **toPage**: int): void

Prints a report to dot-matrix printer in the RAW mode.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **printerName** (string) — A name of a printer.  
- **encoding** (Encoding) — A parameter which sets text encoding.  
- **fromPage** (int) — A number of the first page to print.  
- **toPage** (int) — A number of the last page to print.  

