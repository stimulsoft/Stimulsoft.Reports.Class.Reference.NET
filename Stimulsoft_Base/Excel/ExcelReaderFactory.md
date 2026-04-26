---
title: "ExcelReaderFactory Class"
---

## ExcelReaderFactory Class

**Namespace:** `Stimulsoft.Base.Excel`

The ExcelReader Factory

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateBinaryReader** `static` | [IExcelDataReader](IExcelDataReader.md) | Creates an instance of ExcelBinaryReader |
| **CreateOpenXmlReader** `static` | [IExcelDataReader](IExcelDataReader.md) | Creates an instance of ExcelOpenXmlReader |

---

### Method Details

#### CreateBinaryReader `static`

**CreateBinaryReader**(**fileStream**: Stream): [IExcelDataReader](IExcelDataReader.md)

Creates an instance of ExcelBinaryReader

**Parameters**

- **fileStream** (Stream) — The file stream.  

**Returns** [IExcelDataReader](IExcelDataReader.md)


---

#### CreateOpenXmlReader `static`

**CreateOpenXmlReader**(**fileStream**: Stream): [IExcelDataReader](IExcelDataReader.md)

Creates an instance of ExcelOpenXmlReader

**Parameters**

- **fileStream** (Stream) — The file stream.  

**Returns** [IExcelDataReader](IExcelDataReader.md)

