---
title: "StiRawPrinterHelper Class"
---

## StiRawPrinterHelper Class

**Namespace:** `Stimulsoft.Report.Viewer`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **SendStringToPrinter** `static` *(+1 overloads)* | void | Sends string to printer in RAW mode. |

---

### Method Details

#### SendStringToPrinter `static`

**SendStringToPrinter**(**printerName**: string, **docName**: string, **text**: string): void

Sends string to printer in RAW mode.

**Parameters**

- **printerName** (string) — Name of printer.  
- **docName** (string) — Name of document.  
- **text** (string) — Text to print.  

---

**SendStringToPrinter**(**printerName**: string, **docName**: string, **text**: string, **encoding**: Encoding): void

Sends string to printer in RAW mode.

**Parameters**

- **printerName** (string) — Name of printer.  
- **docName** (string) — Name of document.  
- **text** (string) — Text to print.  
- **encoding** (Encoding) — Encoding of text.  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **pDataType** | string |  |
| **pDocName** | string |  |
| **pOutputFile** | string |  |
