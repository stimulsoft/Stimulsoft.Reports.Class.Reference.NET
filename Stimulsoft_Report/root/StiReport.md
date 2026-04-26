---
title: "StiReport Class"
---

## StiReport Class

**Namespace:** `Stimulsoft.Report`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AutoLocalizeReportOnRun** | bool |  |
| **Column** | int |  |
| **CompiledReport** | [StiReport](StiReport.md) |  |
| **CompilerResults** | CompilerResults |  |
| **CurrentPage** | int |  |
| **CurrentPrintPage** | int |  |
| **GlobalizationManager** | [IStiGlobalizationManager](IStiGlobalizationManager.md) |  |
| **Line** | int |  |
| **LineThrough** | int |  |
| **NeedsCompiling** | bool |  |
| **PageCopyNumber** | int |  |
| **PageNofMLocalizationString** | string |  |
| **ReportFile** | string |  |
| **ViewerControl** | [IStiViewerControl](../Viewer/IStiViewerControl.md) |  |
| **ViewerForm** | Type |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CheckNeedForceInterpretationMode** `static` | bool |  |
| **Compile** *(+5 overloads)* | [StiReport](StiReport.md) | Compiles a report. |
| **CompileAsync** *(+5 overloads)* | Task<[StiReport](StiReport.md)> | Compiles a report. |
| **CompileReportsToAssembly** *(+1 overloads)* | CompilerResults |  |
| **CompileReportsToAssemblyAsync** *(+1 overloads)* | Task<[StiReport](StiReport.md)> |  |
| **CompileStandaloneReport** | [StiReport](StiReport.md) | Compiles a standalone report and locates it in the specified path. |
| **CompileStandaloneReportAsync** | Task<[StiReport](StiReport.md)> | Compiles a standalone report and locates it in the specified path. |
| **CreateInstance** | [StiReport](StiReport.md) |  |
| **CreateNewDashboard** `static` | [StiReport](StiReport.md) |  |
| **CreateNewForm** `static` | [StiReport](StiReport.md) |  |
| **CreateNewReport** `static` | [StiReport](StiReport.md) |  |
| **CreateNewScreen** `static` | [StiReport](StiReport.md) |  |
| **Design** *(+5 overloads)* | DialogResult | Calls the designer for the report in the Modal window. |
| **DesignV2WithWpf** *(+3 overloads)* | bool | Calls the designer for the report in the Modal window with using WPF technology. |
| **DesignWithWpf** *(+2 overloads)* | bool | Calls the designer for the report in the Modal window with using WPF technology. |
| **Div** `static` *(+5 overloads)* | long |  |
| **ExportDocument** *(+6 overloads)* | [StiReport](StiReport.md) | Exports a rendered report into a file with dialog using the provider. |
| **ExportDocumentAsync** *(+5 overloads)* | Task<[StiReport](StiReport.md)> | Exports a rendered report into a file with dialog using the provider. |
| **Format** | string |  |
| **GetFontResourceName** | string |  |
| **GetLabel** | string |  |
| **GetParam** | object |  |
| **GetReportFromAssembly** `static` *(+4 overloads)* | [StiReport](StiReport.md) | Returns a created report from assembly. |
| **GetReportsFromAssembly** `static` | [StiReport](StiReport.md)[] | Returns the array of rendered reports from assembly. |
| **GetResourceFontName** | string |  |
| **GetResourceFontNames** | List<string> |  |
| **IIF** | object |  |
| **IsEncryptedFile** `static` *(+2 overloads)* | bool | Returns true if specified stream contains encrypted report. |
| **IsJsonFile** `static` *(+1 overloads)* | bool | Returns a value indicating whether the specified file contains a JSON report. |
| **IsNull** | bool |  |
| **IsPackedFile** `static` *(+2 overloads)* | bool | Returns a value indicating whether the specified file contains a packed report. |
| **LastOnPage** | object |  |
| **Load** *(+5 overloads)* | Assembly |  |
| **LoadAsync** *(+4 overloads)* | Task<[StiReport](StiReport.md)> | Loads asynchronously a report template from the stream. |
| **LoadDocument** *(+4 overloads)* | [StiReport](StiReport.md) | Loads a rendered report from the byte array. |
| **LoadDocumentAsync** *(+4 overloads)* | Task<[StiReport](StiReport.md)> | Loads asynchronously a rendered report from the byte array. |
| **LoadDocumentFonts** | [StiReport](StiReport.md) |  |
| **LoadDocumentFromJson** *(+1 overloads)* | [StiReport](StiReport.md) | Loads a rendered report from the string. |
| **LoadDocumentFromJsonAsync** *(+1 overloads)* | Task<[StiReport](StiReport.md)> | Loads asynchronously a rendered report from the JSON string. |
| **LoadDocumentFromString** | [StiReport](StiReport.md) | Loads a rendered report from the string. |
| **LoadDocumentFromStringAsync** | Task<[StiReport](StiReport.md)> | Loads asynchronously a rendered report from the string. |
| **LoadDocumentFromUrl** | [StiReport](StiReport.md) | Loads a rendered report template from specified url. |
| **LoadDocumentFromUrlAsync** | Task<[StiReport](StiReport.md)> | Loads asynchronously a rendered report template from specified url. |
| **LoadEditableFields** *(+1 overloads)* | [StiReport](StiReport.md) | Loads the editable fields of rendered report from the stream. |
| **LoadEncryptedDocument** *(+2 overloads)* | [StiReport](StiReport.md) | Loads an encrypted rendered report from the stream. |
| **LoadEncryptedDocumentAsync** *(+2 overloads)* | Task<[StiReport](StiReport.md)> | Loads asynchronously an encrypted rendered report from the stream. |
| **LoadEncryptedDocumentFromString** | [StiReport](StiReport.md) | Loads an encrypted rendered report from the string. |
| **LoadEncryptedDocumentFromStringAsync** | Task<[StiReport](StiReport.md)> | Loads asynchronously an encrypted rendered report from the string. |
| **LoadEncryptedReport** *(+2 overloads)* | [StiReport](StiReport.md) | Loads an encrypted report template from the stream. |
| **LoadEncryptedReportAsync** *(+2 overloads)* | Task<[StiReport](StiReport.md)> | Loads asynchronously an encrypted report template from the stream. |
| **LoadEncryptedReportFromString** | [StiReport](StiReport.md) | Loads an encrypted report template from the string. |
| **LoadEncryptedReportFromStringAsync** | Task<[StiReport](StiReport.md)> | Loads asynchronously an encrypted report template from the string. |
| **LoadFonts** | [StiReport](StiReport.md) |  |
| **LoadFromJson** *(+1 overloads)* | [StiReport](StiReport.md) | Loads a report template from the string. |
| **LoadFromJsonAsync** *(+1 overloads)* | Task<[StiReport](StiReport.md)> | Loads asynchronously a report template from the string. |
| **LoadFromString** | [StiReport](StiReport.md) | Loads a report template from the string. |
| **LoadFromStringAsync** | Task<[StiReport](StiReport.md)> | Loads asynchronously a report template from the string. |
| **LoadFromUrl** | [StiReport](StiReport.md) | Loads a report template from specified url. |
| **LoadFromUrlAsync** | Task<[StiReport](StiReport.md)> | Loads asynchronously a report template from specified url. |
| **LoadPackedDocument** *(+2 overloads)* | [StiReport](StiReport.md) | Loads a packed rendered report from the stream. |
| **LoadPackedDocumentAsync** *(+2 overloads)* | Task<[StiReport](StiReport.md)> | Loads asynchronously a packed rendered report from the stream. |
| **LoadPackedDocumentFromString** | [StiReport](StiReport.md) | Loads a packed rendered report from the string. |
| **LoadPackedDocumentFromStringAsync** | Task<[StiReport](StiReport.md)> | Loads asynchronously a packed rendered report from the string. |
| **LoadPackedReport** *(+2 overloads)* | [StiReport](StiReport.md) | Loads a packed report template from the stream. |
| **LoadPackedReportAsync** *(+2 overloads)* | Task<[StiReport](StiReport.md)> | Loads asynchronously a packed report template from the stream. |
| **LoadPackedReportFromString** | [StiReport](StiReport.md) | Loads a packed report template from the string. |
| **LoadPackedReportFromStringAsync** | Task<[StiReport](StiReport.md)> | Loads asynchronously a packed report template from the string. |
| **LoadReportFromResource** *(+1 overloads)* | [StiReport](StiReport.md) | Loads a report template from the resource. |
| **LoadReportFromResourceAsync** *(+1 overloads)* | Task<[StiReport](StiReport.md)> | Loads asynchronously a report template from the resource. |
| **LocalizeReport** *(+1 overloads)* | [StiReport](StiReport.md) | Localize a report to the specified culture name. The culture definition must be placed in GlobalizationStrings. |
| **MergeDocument** | void | Merge a document to the current document. |
| **NextIsNull** | bool |  |
| **PreviousIsNull** | bool |  |
| **Print** *(+7 overloads)* | [StiReport](StiReport.md) | Prints the rendered report without print dialog. If the report is not rendered then its rendering starts. |
| **PrintAsync** *(+4 overloads)* | Task<[StiReport](StiReport.md)> | Prints the rendered report. If the report is not rendered then its rendering starts. |
| **PrintReports** `static` *(+2 overloads)* | void | Prints the collection of reports. If the report from collection is not rendered then its rendering starts. |
| **PrintReportsAsync** *(+2 overloads)* | Task<[StiReport](StiReport.md)> | Prints the collection of reports. If the report from collection is not rendered then its rendering starts. |
| **PrintToDotMatrixPrinter** *(+3 overloads)* | [StiReport](StiReport.md) | Prints a report to default dot-matrix printer in the RAW mode in ASCII encoding. |
| **PrintWithWpf** *(+10 overloads)* | [StiReport](StiReport.md) | Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly. |
| **PrintWithWpfAsync** *(+7 overloads)* | Task<[StiReport](StiReport.md)> | Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly. |
| **PrintWithXbap** *(+10 overloads)* | [StiReport](StiReport.md) |  |
| **RecalculateRenderedPagesSegments** | [StiReport](StiReport.md) | Recalculate segments in all rendered pages |
| **RegBusinessObject** *(+3 overloads)* | [StiReport](StiReport.md) | Registers the business object in the report. |
| **RegBusinessObjectAsync** *(+1 overloads)* | Task<[StiReport](StiReport.md)> | Asynchronously registers the business object in the report. |
| **RegCsvData** | StiDatabase | Registers a new connection to the CSV data file. |
| **RegCsvDataAsync** | Task<StiDatabase> | Asynchronously registers a new connection to the CSV data file. |
| **RegCsvFile** | StiDatabase | Registers a new connection to the CSV data file. |
| **RegCsvFileAsync** | Task<StiDatabase> | Registers a new connection to the CSV data file. |
| **RegData** *(+17 overloads)* | [StiReport](StiReport.md) | Registers an object in the Data Store. |
| **RegDataAsync** *(+17 overloads)* | Task<[StiReport](StiReport.md)> | Asynchronously registers an object in the Data Store. |
| **RegDbfData** | StiDatabase | Registers a new connection to the DBF data file. |
| **RegDbfDataAsync** | Task<StiDatabase> | Asynchronously registers a new connection to the DBF data file. |
| **RegDbfFile** | StiDatabase | Registers a new connection to the DBF data file. |
| **RegDbfFileAsync** | Task<StiDatabase> | Registers a new connection to the DBF data file. |
| **RegExcelData** | StiDatabase | Registers a new connection to the EXCEL data file. |
| **RegExcelDataAsync** | Task<StiDatabase> | Asynchronously registers a new connection to the EXCEL data file. |
| **RegExcelFile** | StiDatabase | Registers a new connection to the EXCEL data file. |
| **RegExcelFileAsync** | Task<StiDatabase> | Registers a new connection to the EXCEL data file. |
| **RegFirebirdConnection** | StiDatabase | Registers a Firebird connection. |
| **RegFirebirdConnectionAsync** | Task<StiDatabase> | Asynchronously registers a Firebird connection. |
| **RegJsonData** | StiDatabase | Registers a new connection to the JSON data file. |
| **RegJsonDataAsync** | Task<StiDatabase> | Asynchronously registers a new connection to the JSON data file. |
| **RegJsonFile** | StiDatabase | Registers a new connection to the JSON data file. |
| **RegJsonFileAsync** | Task<StiDatabase> | Registers a new connection to the JSON data file. |
| **RegMySqlConnection** | StiDatabase | Registers a MySQL connection. |
| **RegMySqlConnectionAsync** | Task<StiDatabase> | Asynchronously registers a MySQL connection. |
| **RegOdbcConnection** | StiDatabase | Registers an ODBC connection. |
| **RegOdbcConnectionAsync** | Task<StiDatabase> | Asynchronously registers an ODBC connection. |
| **RegOleDbConnection** | StiDatabase | Registers an OLEDB connection. |
| **RegOleDbConnectionAsync** | Task<StiDatabase> | Asynchronously registers an OLEDB connection. |
| **RegOracleConnection** | StiDatabase | Registers an Oracle connection. |
| **RegOracleConnectionAsync** | Task<StiDatabase> | Asynchronously registers an Oracle connection. |
| **RegPostgreSqlConnection** | StiDatabase | Registers a PostgreSQL connection. |
| **RegPostgreSqlConnectionAsync** | Task<StiDatabase> | Asynchronously registers a PostgreSQL connection. |
| **RegReportDataSources** | [StiReport](StiReport.md) | Internal use only. Registers datasources from ReportDataSources property in report dictionary. |
| **RegSqlServerConnection** | StiDatabase | Registers a SQL Server connection. |
| **RegSqlServerConnectionAsync** | Task<StiDatabase> | Asynchronously registers a SQL Server connection. |
| **RegXmlData** *(+1 overloads)* | StiDatabase | Registers a new connection to the XML data file. |
| **RegXmlDataAsync** *(+1 overloads)* | Task<StiDatabase> | Asynchronously registers a new connection to the XML data file. |
| **RegXmlFile** | StiDatabase | Registers a new connection to the XML data file. |
| **RegXmlFileAsync** | Task<StiDatabase> | Registers a new connection to the XML data file. |
| **Render** *(+3 overloads)* | [StiReport](StiReport.md) | Renders a report. |
| **RenderAsync** *(+2 overloads)* | Task<[StiReport](StiReport.md)> | Renders a report. |
| **RenderWithWpf** *(+3 overloads)* | [StiReport](StiReport.md) | Renders a report with using WPF technology. |
| **ResetAggregateFunctions** | [StiReport](StiReport.md) | Resets states of aggregate functions in compiled report. |
| **ResetRenderedState** | [StiReport](StiReport.md) | Resets a rendered states. |
| **Save** *(+3 overloads)* | [StiReport](StiReport.md) | Saves a report template in the stream. |
| **SaveAsync** *(+3 overloads)* | Task<[StiReport](StiReport.md)> | Saves asynchronously a report template in the stream. |
| **SaveDocument** *(+3 overloads)* | [StiReport](StiReport.md) | Saves a rendered report in the stream. |
| **SaveDocumentAsync** *(+3 overloads)* | Task<[StiReport](StiReport.md)> | Saves asynchronously a rendered report in the stream. |
| **SaveDocumentJsonToString** | string | Saves a rendered report to the string. |
| **SaveDocumentJsonToStringAsync** | Task<string> | Saves asynchronously a rendered report to the string. |
| **SaveDocumentToByteArray** | byte[] | Saves a rendered report to the byte array. |
| **SaveDocumentToByteArrayAsync** | Task<byte[]> | Saves asynchronously a rendered report to the byte array. |
| **SaveDocumentToString** | string | Saves a rendered report to the string. |
| **SaveDocumentToStringAsync** | Task<string> | Saves asynchronously a rendered report to the string. |
| **SaveEditableFields** *(+1 overloads)* | [StiReport](StiReport.md) | Saves the editable fields of rendered report to the stream. |
| **SaveEncryptedDocument** *(+1 overloads)* | [StiReport](StiReport.md) | Saves an encrypted rendered report to the stream. |
| **SaveEncryptedDocumentAsync** *(+1 overloads)* | Task<[StiReport](StiReport.md)> | Saves asynchronously an encrypted rendered report to the stream. |
| **SaveEncryptedDocumentToByteArray** | byte[] | Saves an encrypted rendered report to the byte array. |
| **SaveEncryptedDocumentToByteArrayAsync** | Task<byte[]> | Saves asynchronously an encrypted rendered report to the byte array. |
| **SaveEncryptedDocumentToString** | string | Saves an encrypted rendered report to the string. |
| **SaveEncryptedDocumentToStringAsync** | Task<string> | Saves an encrypted rendered report to the string. |
| **SaveEncryptedReport** *(+1 overloads)* | [StiReport](StiReport.md) | Saves an encrypted report template in the stream. |
| **SaveEncryptedReportAsync** *(+1 overloads)* | Task<[StiReport](StiReport.md)> | Saves asynchronously an encrypted report template in the stream. |
| **SaveEncryptedReportToByteArray** | byte[] | Saves an encrypted report template in the byte array. |
| **SaveEncryptedReportToByteArrayAsync** | Task<byte[]> | Saves asynchronously an encrypted report template in the byte array. |
| **SaveEncryptedReportToString** | string | Saves an encrypted report template to the string. |
| **SaveEncryptedReportToStringAsync** | Task<string> | Saves asynchronously an encrypted report template to the string. |
| **SavePackedDocument** *(+1 overloads)* | [StiReport](StiReport.md) | Saves a packed rendered report to the stream. |
| **SavePackedDocumentAsync** *(+1 overloads)* | Task<[StiReport](StiReport.md)> | Saves asynchronously a packed rendered report to the stream. |
| **SavePackedDocumentToByteArray** | byte[] | Saves a packed rendered report to the byte array. |
| **SavePackedDocumentToByteArrayAsync** | Task<byte[]> | Saves asynchronously a packed rendered report to the byte array. |
| **SavePackedDocumentToString** | string | Saves a packed rendered report to the string. |
| **SavePackedDocumentToStringAsync** | Task<string> | Saves asynchronously a packed rendered report to the string. |
| **SavePackedReport** *(+1 overloads)* | [StiReport](StiReport.md) | Saves a packed report template in the stream. |
| **SavePackedReportAsync** *(+1 overloads)* | Task<[StiReport](StiReport.md)> | Saves asynchronously a packed report template in the stream. |
| **SavePackedReportToByteArray** | byte[] | Saves a packed report template in the byte array. |
| **SavePackedReportToByteArrayAsync** | Task<byte[]> | Saves asynchronously a packed report template in the byte array. |
| **SavePackedReportToString** | string | Saves a packed report template to the string. |
| **SavePackedReportToStringAsync** | Task<string> | Saves a packed report template to the string. |
| **SaveReportSourceCode** *(+5 overloads)* | string | Saves the report source code to the string. |
| **SaveSnapshot** *(+1 overloads)* | [StiReport](StiReport.md) | Saves a report template with embedded data |
| **SaveSnapshotAsync** *(+1 overloads)* | Task<[StiReport](StiReport.md)> | Saves asynchronously a report template with embedded data. |
| **SaveSnapshotToByteArray** | byte[] | Saves a report template with embedded data to a byte array. |
| **SaveSnapshotToByteArrayAsync** | Task<byte[]> | Saves asynchronously a report template with embedded data to a byte array. |
| **SaveToByteArray** | byte[] | Saves a report template in the byte array. |
| **SaveToByteArrayAsync** | Task<byte[]> | Saves asynchronously a report template in the byte array. |
| **SaveToJson** | [StiReport](StiReport.md) | Saves a report template in the file. |
| **SaveToJsonAsync** | Task<[StiReport](StiReport.md)> | Saves asynchronously a report template in the file. |
| **SaveToJsonString** | string | Saves a report template to the string. |
| **SaveToJsonStringAsync** | Task<string> | Saves asynchronously a report template to the string. |
| **SaveToString** | string | Saves a report template to the string. |
| **SaveToStringAsync** | Task<string> | Saves asynchronously a report template to the string. |
| **Show** *(+4 overloads)* | [StiReport](StiReport.md) | Shows a rendered report. If the report is not rendered then its rendering starts. |
| **ShowDotMatrix** *(+4 overloads)* | [StiReport](StiReport.md) | Shows a rendered report in DotMatrix mode. If the report is not rendered then its rendering starts. |
| **ShowDotMatrixWithRibbonGUI** *(+4 overloads)* | [StiReport](StiReport.md) |  |
| **ShowDotMatrixWithWpf** *(+1 overloads)* | [StiReport](StiReport.md) | Shows a rendered report in DotMatrix mode with using WPF technology. If the report is not rendered then its rendering starts. |
| **ShowWithRibbonGUI** *(+4 overloads)* | [StiReport](StiReport.md) | Shows a rendered report in viewer with Ribbon GUI. If the report is not rendered then its rendering starts. |
| **ShowWithWpf** *(+3 overloads)* | [StiReport](StiReport.md) | Shows the rendered report with using WPF technology. If the report is not rendered then its rendering starts. |
| **ShowWithWpfRibbonGUI** *(+3 overloads)* | [StiReport](StiReport.md) | Shows the rendered report with using WPF Ribbon GUI technology. If the report is not rendered then its rendering starts. |

---

### Method Details

#### CheckNeedForceInterpretationMode `static`

**CheckNeedForceInterpretationMode**(): bool

**Returns** bool


---

#### Compile

**Compile**(**outputType**: [StiOutputType](../../Stimulsoft_Base/root/StiOutputType.md)): [StiReport](StiReport.md)

Compiles a report.

**Parameters**

- **outputType** ([StiOutputType](../../Stimulsoft_Base/root/StiOutputType.md)) — A parameter which sets a type of the output object.  

**Returns** [StiReport](StiReport.md)

---

**Compile**(**path**: string): [StiReport](StiReport.md)

Compiles a report.

**Parameters**

- **path** (string) — A path for the report location.  

**Returns** [StiReport](StiReport.md)

---

**Compile**(): [StiReport](StiReport.md)

Compiles a report.

**Returns** [StiReport](StiReport.md)

---

**Compile**(**path**: string, **outputType**: [StiOutputType](../../Stimulsoft_Base/root/StiOutputType.md)): [StiReport](StiReport.md)

Compiles a report and locates it to the specified path.

**Parameters**

- **path** (string) — A path for the report location.  
- **outputType** ([StiOutputType](../../Stimulsoft_Base/root/StiOutputType.md)) — A parameter which sets the type of the output object.  

**Returns** [StiReport](StiReport.md)

---

**Compile**(**stream**: Stream): [StiReport](StiReport.md)

Compiles a report and locates it in the specified stream.

**Parameters**

- **stream** (Stream) — A stream for the report location.  

**Returns** [StiReport](StiReport.md)

---

**Compile**(**path**: string, **outputType**: [StiOutputType](../../Stimulsoft_Base/root/StiOutputType.md), **autoCreate**: bool, **leaveScript**: bool): [StiReport](StiReport.md)

Compiles a report and locates it in the specified path.

**Parameters**

- **path** (string) — A parameter which sets the location of the compiled report.  
- **outputType** ([StiOutputType](../../Stimulsoft_Base/root/StiOutputType.md)) — A parameter which sets the type of the output object.  
- **autoCreate** (bool) — If true then the compiled report will be created.  
- **leaveScript** (bool)  

**Returns** [StiReport](StiReport.md)


---

#### CompileAsync

**CompileAsync**(**outputType**: [StiOutputType](../../Stimulsoft_Base/root/StiOutputType.md)): Task<[StiReport](StiReport.md)>

Compiles a report.

**Parameters**

- **outputType** ([StiOutputType](../../Stimulsoft_Base/root/StiOutputType.md)) — A parameter which sets a type of the output object.  

**Returns** Task<[StiReport](StiReport.md)>

---

**CompileAsync**(**path**: string): Task<[StiReport](StiReport.md)>

Compiles a report.

**Parameters**

- **path** (string) — A path for the report location.  

**Returns** Task<[StiReport](StiReport.md)>

---

**CompileAsync**(): Task<[StiReport](StiReport.md)>

Compiles a report.

**Returns** Task<[StiReport](StiReport.md)>

---

**CompileAsync**(**path**: string, **outputType**: [StiOutputType](../../Stimulsoft_Base/root/StiOutputType.md)): Task<[StiReport](StiReport.md)>

Compiles a report and locates it to the specified path.

**Parameters**

- **path** (string) — A path for the report location.  
- **outputType** ([StiOutputType](../../Stimulsoft_Base/root/StiOutputType.md)) — A parameter which sets the type of the output object.  

**Returns** Task<[StiReport](StiReport.md)>

---

**CompileAsync**(**stream**: Stream): Task<[StiReport](StiReport.md)>

Compiles a report and locates it in the specified stream.

**Parameters**

- **stream** (Stream) — A stream for the report location.  

**Returns** Task<[StiReport](StiReport.md)>

---

**CompileAsync**(**path**: string, **outputType**: [StiOutputType](../../Stimulsoft_Base/root/StiOutputType.md), **autoCreate**: bool): Task<[StiReport](StiReport.md)>

Compiles a report and locates it in the specified path.

**Parameters**

- **path** (string) — A parameter which sets the location of the compiled report.  
- **outputType** ([StiOutputType](../../Stimulsoft_Base/root/StiOutputType.md)) — A parameter which sets the type of the output object.  
- **autoCreate** (bool) — If true then the compiled report will be created.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### CompileReportsToAssembly

**CompileReportsToAssembly**(**assemblyPath**: string, ****: StiReportreports): CompilerResults

**Parameters**

- **assemblyPath** (string)  
- **** (StiReportreports)  

**Returns** CompilerResults

---

**CompileReportsToAssembly**(**assemblyPath**: string, ****: StiReportreports, **languageType**: [StiReportLanguageType](StiReportLanguageType.md)): CompilerResults

**Parameters**

- **assemblyPath** (string)  
- **** (StiReportreports)  
- **languageType** ([StiReportLanguageType](StiReportLanguageType.md))  

**Returns** CompilerResults


---

#### CompileReportsToAssemblyAsync

**CompileReportsToAssemblyAsync**(**assemblyPath**: string, ****: StiReportreports): Task<[StiReport](StiReport.md)>

**Parameters**

- **assemblyPath** (string)  
- **** (StiReportreports)  

**Returns** Task<[StiReport](StiReport.md)>

---

**CompileReportsToAssemblyAsync**(**assemblyPath**: string, ****: StiReportreports, **languageType**: [StiReportLanguageType](StiReportLanguageType.md)): Task<[StiReport](StiReport.md)>

**Parameters**

- **assemblyPath** (string)  
- **** (StiReportreports)  
- **languageType** ([StiReportLanguageType](StiReportLanguageType.md))  

**Returns** Task<[StiReport](StiReport.md)>


---

#### CompileStandaloneReport

**CompileStandaloneReport**(**path**: string, **standaloneReportType**: [StiStandaloneReportType](StiStandaloneReportType.md)): [StiReport](StiReport.md)

Compiles a standalone report and locates it in the specified path.

**Parameters**

- **path** (string) — Path for the report location.  
- **standaloneReportType** ([StiStandaloneReportType](StiStandaloneReportType.md))  

**Returns** [StiReport](StiReport.md)


---

#### CompileStandaloneReportAsync

**CompileStandaloneReportAsync**(**path**: string, **standaloneReportType**: [StiStandaloneReportType](StiStandaloneReportType.md)): Task<[StiReport](StiReport.md)>

Compiles a standalone report and locates it in the specified path.

**Parameters**

- **path** (string) — Path for the report location.  
- **standaloneReportType** ([StiStandaloneReportType](StiStandaloneReportType.md))  

**Returns** Task<[StiReport](StiReport.md)>


---

#### CreateInstance

**CreateInstance**(**path**: string): [StiReport](StiReport.md)

**Parameters**

- **path** (string)  

**Returns** [StiReport](StiReport.md)


---

#### CreateNewDashboard `static`

**CreateNewDashboard**(): [StiReport](StiReport.md)

**Returns** [StiReport](StiReport.md)


---

#### CreateNewForm `static`

**CreateNewForm**(): [StiReport](StiReport.md)

**Returns** [StiReport](StiReport.md)


---

#### CreateNewReport `static`

**CreateNewReport**(): [StiReport](StiReport.md)

**Returns** [StiReport](StiReport.md)


---

#### CreateNewScreen `static`

**CreateNewScreen**(): [StiReport](StiReport.md)

**Returns** [StiReport](StiReport.md)


---

#### Design

**Design**(): DialogResult

Calls the designer for the report in the Modal window.

**Returns** DialogResult

---

**Design**(**dialogForm**: bool): DialogResult

Calls the designer for the report.

**Parameters**

- **dialogForm** (bool) — Is this window a dialog box or not.  

**Returns** DialogResult

---

**Design**(**dialogForm**: bool, **win32Window**: IWin32Window): DialogResult

Calls the designer for the report.

**Parameters**

- **dialogForm** (bool) — Is this window a dialog box or not.  
- **win32Window** (IWin32Window) — Provides an interface to expose parent Win32 HWND handle.  

**Returns** DialogResult

---

**Design**(**parentForm**: Form): DialogResult

Calls the designer for the report in the Parent Form.

**Parameters**

- **parentForm** (Form) — Parent Form.  

**Returns** DialogResult

---

**Design**(**owner**: IWin32Window): DialogResult

Calls the designer for the report.

**Parameters**

- **owner** (IWin32Window) — Provides an interface to expose parent Win32 HWND handle.  

**Returns** DialogResult

---

**Design**(**owner**: IWin32Window, **dialogForm**: bool): DialogResult

Calls the designer for the report.

**Parameters**

- **owner** (IWin32Window) — Provides an interface to expose parent Win32 HWND handle.  
- **dialogForm** (bool) — Is this window a dialog box or not.  

**Returns** DialogResult


---

#### DesignV2WithWpf

**DesignV2WithWpf**(): bool

Calls the designer for the report in the Modal window with using WPF technology.

**Returns** bool

---

**DesignV2WithWpf**(**ownerWindow**: object): bool

Calls the designer for the report in the Modal window with using WPF technology.

**Parameters**

- **ownerWindow** (object)  

**Returns** bool

---

**DesignV2WithWpf**(**dialogWindow**: bool): bool

Calls the designer for the report in the Modal window with using WPF technology.

**Parameters**

- **dialogWindow** (bool)  

**Returns** bool

---

**DesignV2WithWpf**(**ownerWindow**: object, **dialogWindow**: bool): bool

Calls the designer for the report in the Modal window with using WPF technology.

**Parameters**

- **ownerWindow** (object)  
- **dialogWindow** (bool)  

**Returns** bool


---

#### DesignWithWpf

**DesignWithWpf**(): bool

Calls the designer for the report in the Modal window with using WPF technology.

**Returns** bool

---

**DesignWithWpf**(**dialogWindow**: bool): bool

**Parameters**

- **dialogWindow** (bool)  

**Returns** bool

---

**DesignWithWpf**(**ownerWindow**: object, **dialogWindow**: bool): bool

**Parameters**

- **ownerWindow** (object)  
- **dialogWindow** (bool)  

**Returns** bool


---

#### Div `static`

**Div**(**value1**: long, **value2**: long): long

**Parameters**

- **value1** (long)  
- **value2** (long)  

**Returns** long

---

**Div**(**value1**: long, **value2**: long, **zeroResult**: long): long

**Parameters**

- **value1** (long)  
- **value2** (long)  
- **zeroResult** (long)  

**Returns** long

---

**Div**(**value1**: double, **value2**: double): double

**Parameters**

- **value1** (double)  
- **value2** (double)  

**Returns** double

---

**Div**(**value1**: double, **value2**: double, **zeroResult**: double): double

**Parameters**

- **value1** (double)  
- **value2** (double)  
- **zeroResult** (double)  

**Returns** double

---

**Div**(**value1**: decimal, **value2**: decimal): decimal

**Parameters**

- **value1** (decimal)  
- **value2** (decimal)  

**Returns** decimal

---

**Div**(**value1**: decimal, **value2**: decimal, **zeroResult**: decimal): decimal

**Parameters**

- **value1** (decimal)  
- **value2** (decimal)  
- **zeroResult** (decimal)  

**Returns** decimal


---

#### ExportDocument

**ExportDocument**(**service**: [StiExportService](../Export/StiExportService.md), **path**: string): [StiReport](StiReport.md)

Exports a rendered report into a file with dialog using the provider.

**Parameters**

- **service** ([StiExportService](../Export/StiExportService.md)) — A provider that exports a rendered report.  
- **path** (string) — A file to export the rendered report.  

**Returns** [StiReport](StiReport.md)

---

**ExportDocument**(**service**: [StiExportService](../Export/StiExportService.md), **path**: string, **sendEMail**: bool): [StiReport](StiReport.md)

Exports a rendered report into a file with dialog using the provider.

**Parameters**

- **service** ([StiExportService](../Export/StiExportService.md)) — A provider that exports a rendered report.  
- **path** (string) — A file to export the rendered report.  
- **sendEMail** (bool) — If this parameter is true then the exported report will be sent via email.  

**Returns** [StiReport](StiReport.md)

---

**ExportDocument**(**exportFormat**: [StiExportFormat](StiExportFormat.md), **file**: string): [StiReport](StiReport.md)

Exports a rendered report into the file without dialog using the provider.

**Parameters**

- **exportFormat** ([StiExportFormat](StiExportFormat.md)) — A format for the document which will be exported to.  
- **file** (string) — A file to export the rendered report.  

**Returns** [StiReport](StiReport.md)

---

**ExportDocument**(**exportFormat**: [StiExportFormat](StiExportFormat.md), **file**: string, **settings**: [StiExportSettings](../Export/StiExportSettings.md)): [StiReport](StiReport.md)

Exports a rendered report into the file without dialog using the provider.

**Parameters**

- **exportFormat** ([StiExportFormat](StiExportFormat.md)) — A format for the document which will be exported to.  
- **file** (string) — A file to export the rendered report.  
- **settings** ([StiExportSettings](../Export/StiExportSettings.md))  

**Returns** [StiReport](StiReport.md)

---

**ExportDocument**(**exportFormat**: [StiExportFormat](StiExportFormat.md), **stream**: Stream): [StiReport](StiReport.md)

Exports a rendered report into the stream without dialog using the provider.

**Parameters**

- **exportFormat** ([StiExportFormat](StiExportFormat.md)) — A format for the document which will be exported to.  
- **stream** (Stream) — A file to export the rendered report.  

**Returns** [StiReport](StiReport.md)

---

**ExportDocument**(**exportFormat**: [StiExportFormat](StiExportFormat.md), **stream**: Stream, **settings**: [StiExportSettings](../Export/StiExportSettings.md)): [StiReport](StiReport.md)

Exports a rendered report into the stream without dialog using the provider.

**Parameters**

- **exportFormat** ([StiExportFormat](StiExportFormat.md)) — A format for the document which will be exported to.  
- **stream** (Stream) — A file to export the rendered report.  
- **settings** ([StiExportSettings](../Export/StiExportSettings.md))  

**Returns** [StiReport](StiReport.md)

---

**ExportDocument**(**exportFormat**: [StiExportFormat](StiExportFormat.md), **exportService**: [StiExportService](../Export/StiExportService.md), **stream**: Stream, **settings**: [StiExportSettings](../Export/StiExportSettings.md)): [StiReport](StiReport.md)

Internal use only.

**Parameters**

- **exportFormat** ([StiExportFormat](StiExportFormat.md))  
- **exportService** ([StiExportService](../Export/StiExportService.md))  
- **stream** (Stream)  
- **settings** ([StiExportSettings](../Export/StiExportSettings.md))  

**Returns** [StiReport](StiReport.md)


---

#### ExportDocumentAsync

**ExportDocumentAsync**(**service**: [StiExportService](../Export/StiExportService.md), **path**: string): Task<[StiReport](StiReport.md)>

Exports a rendered report into a file with dialog using the provider.

**Parameters**

- **service** ([StiExportService](../Export/StiExportService.md)) — A provider that exports a rendered report.  
- **path** (string) — A file to export the rendered report.  

**Returns** Task<[StiReport](StiReport.md)>

---

**ExportDocumentAsync**(**service**: [StiExportService](../Export/StiExportService.md), **path**: string, **sendEMail**: bool): Task<[StiReport](StiReport.md)>

Exports a rendered report into a file with dialog using the provider.

**Parameters**

- **service** ([StiExportService](../Export/StiExportService.md)) — A provider that exports a rendered report.  
- **path** (string) — A file to export the rendered report.  
- **sendEMail** (bool) — If this parameter is true then the exported report will be sent via email.  

**Returns** Task<[StiReport](StiReport.md)>

---

**ExportDocumentAsync**(**exportFormat**: [StiExportFormat](StiExportFormat.md), **file**: string): Task<[StiReport](StiReport.md)>

Exports a rendered report into the file without dialog using the provider.

**Parameters**

- **exportFormat** ([StiExportFormat](StiExportFormat.md)) — A format for the document which will be exported to.  
- **file** (string) — A file to export the rendered report.  

**Returns** Task<[StiReport](StiReport.md)>

---

**ExportDocumentAsync**(**exportFormat**: [StiExportFormat](StiExportFormat.md), **file**: string, **settings**: [StiExportSettings](../Export/StiExportSettings.md)): Task<[StiReport](StiReport.md)>

Exports a rendered report into the file without dialog using the provider.

**Parameters**

- **exportFormat** ([StiExportFormat](StiExportFormat.md)) — A format for the document which will be exported to.  
- **file** (string) — A file to export the rendered report.  
- **settings** ([StiExportSettings](../Export/StiExportSettings.md))  

**Returns** Task<[StiReport](StiReport.md)>

---

**ExportDocumentAsync**(**exportFormat**: [StiExportFormat](StiExportFormat.md), **stream**: Stream): Task<[StiReport](StiReport.md)>

Exports a rendered report into the stream without dialog using the provider.

**Parameters**

- **exportFormat** ([StiExportFormat](StiExportFormat.md)) — A format for the document which will be exported to.  
- **stream** (Stream) — A file to export the rendered report.  

**Returns** Task<[StiReport](StiReport.md)>

---

**ExportDocumentAsync**(**exportFormat**: [StiExportFormat](StiExportFormat.md), **stream**: Stream, **settings**: [StiExportSettings](../Export/StiExportSettings.md)): Task<[StiReport](StiReport.md)>

Exports a rendered report into the stream without dialog using the provider.

**Parameters**

- **exportFormat** ([StiExportFormat](StiExportFormat.md)) — A format for the document which will be exported to.  
- **stream** (Stream) — A file to export the rendered report.  
- **settings** ([StiExportSettings](../Export/StiExportSettings.md))  

**Returns** Task<[StiReport](StiReport.md)>


---

#### Format

**Format**(**format**: string, **arg**: object): string

**Parameters**

- **format** (string)  
- **arg** (object)  

**Returns** string


---

#### GetFontResourceName

**GetFontResourceName**(**fontName**: string): string

**Parameters**

- **fontName** (string)  

**Returns** string


---

#### GetLabel

**GetLabel**(**variableName**: string): string

**Parameters**

- **variableName** (string)  

**Returns** string


---

#### GetParam

**GetParam**(**paramName**: string): object

**Parameters**

- **paramName** (string)  

**Returns** object


---

#### GetReportFromAssembly `static`

**GetReportFromAssembly**(**assembly**: Assembly): [StiReport](StiReport.md)

Returns a created report from assembly.

**Parameters**

- **assembly** (Assembly) — Assembly with a report.  

**Returns** [StiReport](StiReport.md) — Created report.

---

**GetReportFromAssembly**(**assemblyFile**: string): [StiReport](StiReport.md)

Returns a created report from assembly.

**Parameters**

- **assemblyFile** (string) — The path to assembly.  

**Returns** [StiReport](StiReport.md) — Created report.

---

**GetReportFromAssembly**(**assemblyFile**: string, **lockFile**: bool): [StiReport](StiReport.md)

Returns a created report from assembly.

**Parameters**

- **assemblyFile** (string) — The path to assembly.  
- **lockFile** (bool) — If true then file with assembly is locked but assembly is loaded to memory only once.  

**Returns** [StiReport](StiReport.md) — Created report.

---

**GetReportFromAssembly**(**assemblyStream**: Stream): [StiReport](StiReport.md)

Returns a created report from assembly.

**Parameters**

- **assemblyStream** (Stream) — The stream with assembly.  

**Returns** [StiReport](StiReport.md) — Created report.

---

**GetReportFromAssembly**(****: bytebytes): [StiReport](StiReport.md)

Returns a created report from the byte array.

**Parameters**

- **** (bytebytes)  

**Returns** [StiReport](StiReport.md) — Created report.


---

#### GetReportsFromAssembly `static`

**GetReportsFromAssembly**(**assembly**: Assembly): [StiReport](StiReport.md)[]

Returns the array of rendered reports from assembly.

**Parameters**

- **assembly** (Assembly) — Assembly with reports.  

**Returns** [StiReport](StiReport.md)[] — The array of created reports.


---

#### GetResourceFontName

**GetResourceFontName**(**resourceName**: string): string

**Parameters**

- **resourceName** (string)  

**Returns** string


---

#### GetResourceFontNames

**GetResourceFontNames**(**resourceName**: string): List<string>

**Parameters**

- **resourceName** (string)  

**Returns** List<string>


---

#### IIF

**IIF**(**condition**: bool, **value1**: object, **value2**: object): object

**Parameters**

- **condition** (bool)  
- **value1** (object)  
- **value2** (object)  

**Returns** object


---

#### IsEncryptedFile `static`

**IsEncryptedFile**(**stream**: Stream): bool

Returns true if specified stream contains encrypted report.

**Parameters**

- **stream** (Stream)  

**Returns** bool

---

**IsEncryptedFile**(**fileName**: string): bool

Returns true if a file with the specified name contains encrypted report.

**Parameters**

- **fileName** (string)  

**Returns** bool

---

**IsEncryptedFile**(****: bytebytes): bool

**Parameters**

- **** (bytebytes)  

**Returns** bool


---

#### IsJsonFile `static`

**IsJsonFile**(**fileName**: string): bool

Returns a value indicating whether the specified file contains a JSON report.

**Parameters**

- **fileName** (string)  

**Returns** bool

---

**IsJsonFile**(**stream**: Stream): bool

Returns true if specified stream contains JSON report.

**Parameters**

- **stream** (Stream)  

**Returns** bool


---

#### IsNull

**IsNull**(**dataSource**: object, **dataColumn**: string): bool

**Parameters**

- **dataSource** (object)  
- **dataColumn** (string)  

**Returns** bool


---

#### IsPackedFile `static`

**IsPackedFile**(**fileName**: string): bool

Returns a value indicating whether the specified file contains a packed report.

**Parameters**

- **fileName** (string)  

**Returns** bool

---

**IsPackedFile**(**stream**: Stream): bool

Returns true if specified stream contains packed report.

**Parameters**

- **stream** (Stream)  

**Returns** bool

---

**IsPackedFile**(****: bytebytes): bool

Returns a value indicating whether the specified byte array contains a packed report.

**Parameters**

- **** (bytebytes)  

**Returns** bool


---

#### LastOnPage

**LastOnPage**(**dataSource**: object, **dataColumn**: string): object

**Parameters**

- **dataSource** (object)  
- **dataColumn** (string)  

**Returns** object


---

#### Load

**Load**(**name**: AssemblyName): Assembly

**Parameters**

- **name** (AssemblyName)  

**Returns** Assembly

---

**Load**(**stream**: Stream): [StiReport](StiReport.md)

Loads a report template from the stream.

**Parameters**

- **stream** (Stream) — A stream for loading a report template.  

**Returns** [StiReport](StiReport.md)

---

**Load**(****: bytebytes): [StiReport](StiReport.md)

Loads a report template from the byte array.

**Parameters**

- **** (bytebytes)  

**Returns** [StiReport](StiReport.md)

---

**Load**(**path**: string): [StiReport](StiReport.md)

Loads a report template from the file.

**Parameters**

- **path** (string) — A file which contains the report template.  

**Returns** [StiReport](StiReport.md)

---

**Load**(**service**: [StiReportSLService](../SaveLoad/StiReportSLService.md), **stream**: Stream): [StiReport](StiReport.md)

Loads a report template from the stream using provider.

**Parameters**

- **service** ([StiReportSLService](../SaveLoad/StiReportSLService.md)) — A provider which loads a report template.  
- **stream** (Stream) — A stream for loading a report template.  

**Returns** [StiReport](StiReport.md)

---

**Load**(**service**: [StiReportSLService](../SaveLoad/StiReportSLService.md), **path**: string): [StiReport](StiReport.md)

Loads a report template from the file using the provider.

**Parameters**

- **service** ([StiReportSLService](../SaveLoad/StiReportSLService.md)) — A provider which loads a report template.  
- **path** (string) — A file for loading a report template.  

**Returns** [StiReport](StiReport.md)


---

#### LoadAsync

**LoadAsync**(**stream**: Stream): Task<[StiReport](StiReport.md)>

Loads asynchronously a report template from the stream.

**Parameters**

- **stream** (Stream) — A stream for loading a report template.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadAsync**(****: bytebytes): Task<[StiReport](StiReport.md)>

Loads asynchronously a report template from the byte array.

**Parameters**

- **** (bytebytes)  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadAsync**(**path**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously a report template from the file.

**Parameters**

- **path** (string) — A file which contains the report template.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadAsync**(**service**: [StiReportSLService](../SaveLoad/StiReportSLService.md), **stream**: Stream): Task<[StiReport](StiReport.md)>

Loads asynchronously a report template from the stream using provider.

**Parameters**

- **service** ([StiReportSLService](../SaveLoad/StiReportSLService.md)) — A provider which loads a report template.  
- **stream** (Stream) — A stream for loading a report template.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadAsync**(**service**: [StiReportSLService](../SaveLoad/StiReportSLService.md), **path**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously a report template from the file using the provider.

**Parameters**

- **service** ([StiReportSLService](../SaveLoad/StiReportSLService.md)) — A provider which loads a report template.  
- **path** (string) — A file for loading a report template.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LoadDocument

**LoadDocument**(****: bytebytes): [StiReport](StiReport.md)

Loads a rendered report from the byte array.

**Parameters**

- **** (bytebytes)  

**Returns** [StiReport](StiReport.md)

---

**LoadDocument**(**stream**: Stream): [StiReport](StiReport.md)

Loads a rendered report from the stream.

**Parameters**

- **stream** (Stream) — A stream for loading a rendered report.  

**Returns** [StiReport](StiReport.md)

---

**LoadDocument**(**path**: string): [StiReport](StiReport.md)

Loads a rendered report from the file.

**Parameters**

- **path** (string) — A file which contains a rendered report.  

**Returns** [StiReport](StiReport.md)

---

**LoadDocument**(**service**: [StiDocumentSLService](../SaveLoad/StiDocumentSLService.md), **stream**: Stream): [StiReport](StiReport.md)

Loads a rendered report from the stream using the provider.

**Parameters**

- **service** ([StiDocumentSLService](../SaveLoad/StiDocumentSLService.md)) — A provider for loading a rendered report.  
- **stream** (Stream) — A stream for loading a rendered report.  

**Returns** [StiReport](StiReport.md)

---

**LoadDocument**(**service**: [StiDocumentSLService](../SaveLoad/StiDocumentSLService.md), **path**: string): [StiReport](StiReport.md)

Loads a rendered report from the file using the provider.

**Parameters**

- **service** ([StiDocumentSLService](../SaveLoad/StiDocumentSLService.md)) — A provider for loading a rendered report.  
- **path** (string) — A file for loading a rendered report.  

**Returns** [StiReport](StiReport.md)


---

#### LoadDocumentAsync

**LoadDocumentAsync**(****: bytebytes): Task<[StiReport](StiReport.md)>

Loads asynchronously a rendered report from the byte array.

**Parameters**

- **** (bytebytes)  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadDocumentAsync**(**stream**: Stream): Task<[StiReport](StiReport.md)>

Loads asynchronously a rendered report from the stream.

**Parameters**

- **stream** (Stream) — A stream for loading a rendered report.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadDocumentAsync**(**path**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously a rendered report from the file.

**Parameters**

- **path** (string) — A file which contains a rendered report.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadDocumentAsync**(**service**: [StiDocumentSLService](../SaveLoad/StiDocumentSLService.md), **stream**: Stream): Task<[StiReport](StiReport.md)>

Loads asynchronously a rendered report from the stream using the provider.

**Parameters**

- **service** ([StiDocumentSLService](../SaveLoad/StiDocumentSLService.md)) — A provider for loading a rendered report.  
- **stream** (Stream) — A stream for loading a rendered report.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadDocumentAsync**(**service**: [StiDocumentSLService](../SaveLoad/StiDocumentSLService.md), **path**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously a rendered report from the file using the provider.

**Parameters**

- **service** ([StiDocumentSLService](../SaveLoad/StiDocumentSLService.md)) — A provider for loading a rendered report.  
- **path** (string) — A file for loading a rendered report.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LoadDocumentFonts

**LoadDocumentFonts**(): [StiReport](StiReport.md)

**Returns** [StiReport](StiReport.md)


---

#### LoadDocumentFromJson

**LoadDocumentFromJson**(**json**: string): [StiReport](StiReport.md)

Loads a rendered report from the string.

**Parameters**

- **json** (string) — A string for loading a report from it.  

**Returns** [StiReport](StiReport.md)

---

**LoadDocumentFromJson**(**stream**: Stream): [StiReport](StiReport.md)

Loads a rendered report from the stream.

**Parameters**

- **stream** (Stream) — A stream for loading a report template.  

**Returns** [StiReport](StiReport.md)


---

#### LoadDocumentFromJsonAsync

**LoadDocumentFromJsonAsync**(**json**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously a rendered report from the JSON string.

**Parameters**

- **json** (string) — A string for loading a report from it.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadDocumentFromJsonAsync**(**stream**: Stream): Task<[StiReport](StiReport.md)>

Loads asynchronously a JSON rendered report from the stream.

**Parameters**

- **stream** (Stream) — A stream for loading a report template.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LoadDocumentFromString

**LoadDocumentFromString**(**reportStr**: string): [StiReport](StiReport.md)

Loads a rendered report from the string.

**Parameters**

- **reportStr** (string) — A string for loading a report from it.  

**Returns** [StiReport](StiReport.md)


---

#### LoadDocumentFromStringAsync

**LoadDocumentFromStringAsync**(**reportStr**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously a rendered report from the string.

**Parameters**

- **reportStr** (string) — A string for loading a report from it.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LoadDocumentFromUrl

**LoadDocumentFromUrl**(**url**: string, **headers**: NameValueCollection): [StiReport](StiReport.md)

Loads a rendered report template from specified url.

**Parameters**

- **url** (string) — Url which will be used for report loading.  
- **headers** (NameValueCollection)  

**Returns** [StiReport](StiReport.md)


---

#### LoadDocumentFromUrlAsync

**LoadDocumentFromUrlAsync**(**url**: string, **headers**: NameValueCollection): Task<[StiReport](StiReport.md)>

Loads asynchronously a rendered report template from specified url.

**Parameters**

- **url** (string) — Url which will be used for report loading.  
- **headers** (NameValueCollection)  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LoadEditableFields

**LoadEditableFields**(**path**: string): [StiReport](StiReport.md)

Loads the editable fields of rendered report from the stream.

**Parameters**

- **path** (string)  

**Returns** [StiReport](StiReport.md)

---

**LoadEditableFields**(**stream**: Stream): [StiReport](StiReport.md)

Loads the editable fields of rendered report from the stream.

**Parameters**

- **stream** (Stream) — Stream for loading the editable fields.  

**Returns** [StiReport](StiReport.md)


---

#### LoadEncryptedDocument

**LoadEncryptedDocument**(**stream**: Stream, **key**: string): [StiReport](StiReport.md)

Loads an encrypted rendered report from the stream.

**Parameters**

- **stream** (Stream) — The stream to load an encrypted rendered report.  
- **key** (string) — The key for encryption.  

**Returns** [StiReport](StiReport.md)

---

**LoadEncryptedDocument**(**path**: string, **key**: string): [StiReport](StiReport.md)

Loads an encrypted rendered report from the file.

**Parameters**

- **path** (string) — The file which contains an encrypted rendered report.  
- **key** (string) — The key for encryption.  

**Returns** [StiReport](StiReport.md)

---

**LoadEncryptedDocument**(****: bytebytes, **key**: string): [StiReport](StiReport.md)

Loads an encrypted rendered report from the byte array.

**Parameters**

- **** (bytebytes)  
- **key** (string) — The key for encryption.  

**Returns** [StiReport](StiReport.md)


---

#### LoadEncryptedDocumentAsync

**LoadEncryptedDocumentAsync**(**stream**: Stream, **key**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously an encrypted rendered report from the stream.

**Parameters**

- **stream** (Stream) — The stream to load an encrypted rendered report.  
- **key** (string) — The key for encryption.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadEncryptedDocumentAsync**(**path**: string, **key**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously an encrypted rendered report from the file.

**Parameters**

- **path** (string) — The file which contains an encrypted rendered report.  
- **key** (string) — The key for encryption.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadEncryptedDocumentAsync**(****: bytebytes, **key**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously an encrypted rendered report from the byte array.

**Parameters**

- **** (bytebytes)  
- **key** (string) — The key for encryption.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LoadEncryptedDocumentFromString

**LoadEncryptedDocumentFromString**(**reportStr**: string, **key**: string): [StiReport](StiReport.md)

Loads an encrypted rendered report from the string.

**Parameters**

- **reportStr** (string) — A string from which the encrypted rendered report will be loaded from.  
- **key** (string) — The key for encryption.  

**Returns** [StiReport](StiReport.md)


---

#### LoadEncryptedDocumentFromStringAsync

**LoadEncryptedDocumentFromStringAsync**(**reportStr**: string, **key**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously an encrypted rendered report from the string.

**Parameters**

- **reportStr** (string) — A string from which the encrypted rendered report will be loaded from.  
- **key** (string) — The key for encryption.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LoadEncryptedReport

**LoadEncryptedReport**(**stream**: Stream, **key**: string): [StiReport](StiReport.md)

Loads an encrypted report template from the stream.

**Parameters**

- **stream** (Stream) — A stream to load an encrypted report template.  
- **key** (string) — The key for encryption.  

**Returns** [StiReport](StiReport.md)

---

**LoadEncryptedReport**(**path**: string, **key**: string): [StiReport](StiReport.md)

Loads an encrypted report template from the file.

**Parameters**

- **path** (string) — A file which contains an encrypted report template.  
- **key** (string) — The key for encryption.  

**Returns** [StiReport](StiReport.md)

---

**LoadEncryptedReport**(****: bytebytes, **key**: string): [StiReport](StiReport.md)

Loads an encrypted report template from the byte array.

**Parameters**

- **** (bytebytes)  
- **key** (string) — The key for encryption.  

**Returns** [StiReport](StiReport.md)


---

#### LoadEncryptedReportAsync

**LoadEncryptedReportAsync**(**stream**: Stream, **key**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously an encrypted report template from the stream.

**Parameters**

- **stream** (Stream) — A stream to load an encrypted report template.  
- **key** (string) — The key for encryption.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadEncryptedReportAsync**(**path**: string, **key**: string): Task<[StiReport](StiReport.md)>

Loads asynchronically an encrypted report template from the file.

**Parameters**

- **path** (string) — A file which contains an encrypted report template.  
- **key** (string) — The key for encryption.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadEncryptedReportAsync**(****: bytebytes, **key**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously an encrypted report template from the byte array.

**Parameters**

- **** (bytebytes)  
- **key** (string) — The key for encryption.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LoadEncryptedReportFromString

**LoadEncryptedReportFromString**(**reportStr**: string, **key**: string): [StiReport](StiReport.md)

Loads an encrypted report template from the string.

**Parameters**

- **reportStr** (string) — A string which contains the encrypted template.  
- **key** (string) — The key for encryption.  

**Returns** [StiReport](StiReport.md)


---

#### LoadEncryptedReportFromStringAsync

**LoadEncryptedReportFromStringAsync**(**reportStr**: string, **key**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously an encrypted report template from the string.

**Parameters**

- **reportStr** (string) — A string which contains the encrypted template.  
- **key** (string) — The key for encryption.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LoadFonts

**LoadFonts**(): [StiReport](StiReport.md)

**Returns** [StiReport](StiReport.md)


---

#### LoadFromJson

**LoadFromJson**(**json**: string): [StiReport](StiReport.md)

Loads a report template from the string.

**Parameters**

- **json** (string) — A string which contains the report template.  

**Returns** [StiReport](StiReport.md)

---

**LoadFromJson**(**stream**: Stream): [StiReport](StiReport.md)

Loads a report template from the stream.

**Parameters**

- **stream** (Stream) — A stream for loading a report template.  

**Returns** [StiReport](StiReport.md)


---

#### LoadFromJsonAsync

**LoadFromJsonAsync**(**json**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously a report template from the string.

**Parameters**

- **json** (string) — A string which contains the report template.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadFromJsonAsync**(**stream**: Stream): Task<[StiReport](StiReport.md)>

Loads asynchronously a report template from the stream.

**Parameters**

- **stream** (Stream) — A stream for loading a report template.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LoadFromString

**LoadFromString**(**reportStr**: string): [StiReport](StiReport.md)

Loads a report template from the string.

**Parameters**

- **reportStr** (string) — A string which contains the report template.  

**Returns** [StiReport](StiReport.md)


---

#### LoadFromStringAsync

**LoadFromStringAsync**(**reportStr**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously a report template from the string.

**Parameters**

- **reportStr** (string) — A string which contains the report template.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LoadFromUrl

**LoadFromUrl**(**url**: string, **headers**: NameValueCollection): [StiReport](StiReport.md)

Loads a report template from specified url.

**Parameters**

- **url** (string) — Url which will be used for report loading.  
- **headers** (NameValueCollection)  

**Returns** [StiReport](StiReport.md)


---

#### LoadFromUrlAsync

**LoadFromUrlAsync**(**url**: string, **headers**: NameValueCollection): Task<[StiReport](StiReport.md)>

Loads asynchronously a report template from specified url.

**Parameters**

- **url** (string) — Url which will be used for report loading.  
- **headers** (NameValueCollection)  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LoadPackedDocument

**LoadPackedDocument**(**stream**: Stream): [StiReport](StiReport.md)

Loads a packed rendered report from the stream.

**Parameters**

- **stream** (Stream) — The stream to load a packed rendered report.  

**Returns** [StiReport](StiReport.md)

---

**LoadPackedDocument**(**path**: string): [StiReport](StiReport.md)

Loads a packed rendered report from the file.

**Parameters**

- **path** (string) — The file which contains a packed rendered report.  

**Returns** [StiReport](StiReport.md)

---

**LoadPackedDocument**(****: bytebytes): [StiReport](StiReport.md)

Loads a packed rendered report from the byte array.

**Parameters**

- **** (bytebytes)  

**Returns** [StiReport](StiReport.md)


---

#### LoadPackedDocumentAsync

**LoadPackedDocumentAsync**(**stream**: Stream): Task<[StiReport](StiReport.md)>

Loads asynchronously a packed rendered report from the stream.

**Parameters**

- **stream** (Stream) — The stream to load a packed rendered report.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadPackedDocumentAsync**(**path**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously a packed rendered report from the file.

**Parameters**

- **path** (string) — The file which contains a packed rendered report.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadPackedDocumentAsync**(****: bytebytes): Task<[StiReport](StiReport.md)>

Loads asynchronously a packed rendered report from the byte array.

**Parameters**

- **** (bytebytes)  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LoadPackedDocumentFromString

**LoadPackedDocumentFromString**(**reportStr**: string): [StiReport](StiReport.md)

Loads a packed rendered report from the string.

**Parameters**

- **reportStr** (string) — A string from which the packed rendered report will be loaded from.  

**Returns** [StiReport](StiReport.md)


---

#### LoadPackedDocumentFromStringAsync

**LoadPackedDocumentFromStringAsync**(**reportStr**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously a packed rendered report from the string.

**Parameters**

- **reportStr** (string) — A string from which the packed rendered report will be loaded from.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LoadPackedReport

**LoadPackedReport**(**stream**: Stream): [StiReport](StiReport.md)

Loads a packed report template from the stream.

**Parameters**

- **stream** (Stream) — A stream to load a packed report template.  

**Returns** [StiReport](StiReport.md)

---

**LoadPackedReport**(**path**: string): [StiReport](StiReport.md)

Loads a packed report template from the file.

**Parameters**

- **path** (string) — A file which contains a packed report template.  

**Returns** [StiReport](StiReport.md)

---

**LoadPackedReport**(****: bytebytes): [StiReport](StiReport.md)

Loads a packed report template from the byte array.

**Parameters**

- **** (bytebytes)  

**Returns** [StiReport](StiReport.md)


---

#### LoadPackedReportAsync

**LoadPackedReportAsync**(**stream**: Stream): Task<[StiReport](StiReport.md)>

Loads asynchronously a packed report template from the stream.

**Parameters**

- **stream** (Stream) — A stream to load a packed report template.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadPackedReportAsync**(**path**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously a packed report template from the file.

**Parameters**

- **path** (string) — A file which contains a packed report template.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadPackedReportAsync**(****: bytebytes): Task<[StiReport](StiReport.md)>

Loads asynchronously a packed report template from the byte array.

**Parameters**

- **** (bytebytes)  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LoadPackedReportFromString

**LoadPackedReportFromString**(**reportStr**: string): [StiReport](StiReport.md)

Loads a packed report template from the string.

**Parameters**

- **reportStr** (string) — A string which contains the report template.  

**Returns** [StiReport](StiReport.md)


---

#### LoadPackedReportFromStringAsync

**LoadPackedReportFromStringAsync**(**reportStr**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously a packed report template from the string.

**Parameters**

- **reportStr** (string) — A string which contains the report template.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LoadReportFromResource

**LoadReportFromResource**(**reportAssembly**: Assembly, **reportResource**: string): [StiReport](StiReport.md)

Loads a report template from the resource.

**Parameters**

- **reportAssembly** (Assembly) — Assembly in which is the report is placed.  
- **reportResource** (string) — A name of resources which contains a report template.  

**Returns** [StiReport](StiReport.md)

---

**LoadReportFromResource**(**assemblyName**: string, **reportResource**: string): [StiReport](StiReport.md)

Loads a report template from the resource.

**Parameters**

- **assemblyName** (string) — The name of assembly in which the report is placed.  
- **reportResource** (string) — A name of resources which contains a report template.  

**Returns** [StiReport](StiReport.md)


---

#### LoadReportFromResourceAsync

**LoadReportFromResourceAsync**(**reportAssembly**: Assembly, **reportResource**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously a report template from the resource.

**Parameters**

- **reportAssembly** (Assembly) — Assembly in which is the report is placed.  
- **reportResource** (string) — A name of resources which contains a report template.  

**Returns** Task<[StiReport](StiReport.md)>

---

**LoadReportFromResourceAsync**(**assemblyName**: string, **reportResource**: string): Task<[StiReport](StiReport.md)>

Loads asynchronously a report template from the resource.

**Parameters**

- **assemblyName** (string) — The name of assembly in which the report is placed.  
- **reportResource** (string) — A name of resources which contains a report template.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### LocalizeReport

**LocalizeReport**(**cultureName**: string): [StiReport](StiReport.md)

Localize a report to the specified culture name. The culture definition must be placed in GlobalizationStrings.

**Parameters**

- **cultureName** (string)  

**Returns** [StiReport](StiReport.md)

---

**LocalizeReport**(**info**: CultureInfo): [StiReport](StiReport.md)

Localize a report to the specified culture. The culture definition must be placed in GlobalizationStrings.

**Parameters**

- **info** (CultureInfo)  

**Returns** [StiReport](StiReport.md)


---

#### MergeDocument

**MergeDocument**(**report**: [StiReport](StiReport.md), **needRendering**: bool): void

Merge a document to the current document.

**Parameters**

- **report** ([StiReport](StiReport.md))  
- **needRendering** (bool)  


---

#### NextIsNull

**NextIsNull**(**dataSource**: object, **dataColumn**: string): bool

**Parameters**

- **dataSource** (object)  
- **dataColumn** (string)  

**Returns** bool


---

#### PreviousIsNull

**PreviousIsNull**(**dataSource**: object, **dataColumn**: string): bool

**Parameters**

- **dataSource** (object)  
- **dataColumn** (string)  

**Returns** bool


---

#### Print

**Print**(**printerSettings**: PrinterSettings): [StiReport](StiReport.md)

Prints the rendered report without print dialog. If the report is not rendered then its rendering starts.

**Parameters**

- **printerSettings** (PrinterSettings) — Specifies information about how a document is printed, including the printer that prints it.  

**Returns** [StiReport](StiReport.md)

---

**Print**(**showPrintDialog**: bool, **printerSettings**: PrinterSettings): [StiReport](StiReport.md)

Prints the rendered report. If the report is not rendered then its rendering starts.

**Parameters**

- **showPrintDialog** (bool) — If a parameter is true then the print dialog will be shown.  
- **printerSettings** (PrinterSettings) — Specifies information about how a document is printed, including the printer that prints it.  

**Returns** [StiReport](StiReport.md)

---

**Print**(): [StiReport](StiReport.md)

Prints the rendered report. If the report is not rendered then its rendering starts.

**Returns** [StiReport](StiReport.md)

---

**Print**(**fromPage**: int, **toPage**: int, **copies**: short): [StiReport](StiReport.md)

Prints the rendered report with the print dialog. If the report is not rendered then its rendering starts.

**Parameters**

- **fromPage** (int) — A number of the first page to print.  
- **toPage** (int) — A number of the last page to print.  
- **copies** (short) — A number of copies to print.  

**Returns** [StiReport](StiReport.md)

---

**Print**(**showPrintDialog**: bool, **copies**: short): [StiReport](StiReport.md)

Prints a rendered report. If the report is not rendered then its rendering starts.

**Parameters**

- **showPrintDialog** (bool) — If a parameter is true then the print dialog will be shown.  
- **copies** (short) — A number of copies to print.  

**Returns** [StiReport](StiReport.md)

---

**Print**(**showPrintDialog**: bool): [StiReport](StiReport.md)

Prints the rendered report. If the report is not rendered then its rendering starts.

**Parameters**

- **showPrintDialog** (bool) — If a parameter is true then the print dialog will be shown.  

**Returns** [StiReport](StiReport.md)

---

**Print**(**showPrintDialog**: bool, **fromPage**: int, **toPage**: int, **copies**: short): [StiReport](StiReport.md)

Prints the rendered report. If the report is not rendered then its rendering starts.

**Parameters**

- **showPrintDialog** (bool) — If a parameter is true then the print dialog will be shown.  
- **fromPage** (int) — A number of the first page to print.  
- **toPage** (int) — A number of the last page to print.  
- **copies** (short) — A number of copies to print.  

**Returns** [StiReport](StiReport.md)

---

**Print**(**showPrintDialog**: bool, **fromPage**: int, **toPage**: int, **copies**: short, **printerSettings**: PrinterSettings, **printProvider**: [StiPrintProvider](../Print/StiPrintProvider.md)): [StiReport](StiReport.md)

Prints the rendered report. If the report is not rendered then its rendering starts.

**Parameters**

- **showPrintDialog** (bool) — If a parameter is true then the print dialog will be shown.  
- **fromPage** (int) — A number of the first page to print.  
- **toPage** (int) — A number of the last page to print.  
- **copies** (short) — A number of copies to print.  
- **printerSettings** (PrinterSettings) — Specifies information about how a document is printed, including the printer that prints it.  
- **printProvider** ([StiPrintProvider](../Print/StiPrintProvider.md))  

**Returns** [StiReport](StiReport.md)


---

#### PrintAsync

**PrintAsync**(**printerSettings**: PrinterSettings): Task<[StiReport](StiReport.md)>

Prints the rendered report. If the report is not rendered then its rendering starts.

**Parameters**

- **printerSettings** (PrinterSettings) — Specifies information about how a document is printed, including the printer that prints it.  

**Returns** Task<[StiReport](StiReport.md)>

---

**PrintAsync**(**copies**: short): Task<[StiReport](StiReport.md)>

Prints the rendered report. If the report is not rendered then its rendering starts.

**Parameters**

- **copies** (short) — A number of copies to print.  

**Returns** Task<[StiReport](StiReport.md)>

---

**PrintAsync**(): Task<[StiReport](StiReport.md)>

Prints the rendered report. If the report is not rendered then its rendering starts.

**Returns** Task<[StiReport](StiReport.md)>

---

**PrintAsync**(**fromPage**: int, **toPage**: int, **copies**: short): Task<[StiReport](StiReport.md)>

Prints the rendered report. If the report is not rendered then its rendering starts.

**Parameters**

- **fromPage** (int) — A number of the first page to print.  
- **toPage** (int) — A number of the last page to print.  
- **copies** (short) — A number of copies to print.  

**Returns** Task<[StiReport](StiReport.md)>

---

**PrintAsync**(**fromPage**: int, **toPage**: int, **copies**: short, **printerSettings**: PrinterSettings): Task<[StiReport](StiReport.md)>

Prints the rendered report. If the report is not rendered then its rendering starts.

**Parameters**

- **fromPage** (int) — A number of the first page to print.  
- **toPage** (int) — A number of the last page to print.  
- **copies** (short) — A number of copies to print.  
- **printerSettings** (PrinterSettings) — Specifies information about how a document is printed, including the printer that prints it.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### PrintReports `static`

**PrintReports**(**reports**: List<[StiReport](StiReport.md)>): void

Prints the collection of reports. If the report from collection is not rendered then its rendering starts.

**Parameters**

- **reports** (List<[StiReport](StiReport.md)>) — Collection of reports to print.  

---

**PrintReports**(**reports**: List<[StiReport](StiReport.md)>, **showPrintDialog**: bool, **copies**: short): void

Prints the collection of reports. If the report from collection is not rendered then its rendering starts.

**Parameters**

- **reports** (List<[StiReport](StiReport.md)>) — Collection of reports to print.  
- **showPrintDialog** (bool) — If a parameter is true then the print dialog will be shown.  
- **copies** (short) — A number of copies to print.  

---

**PrintReports**(**reports**: List<[StiReport](StiReport.md)>, **showPrintDialog**: bool, **copies**: short, **printerSettings**: PrinterSettings): void

Prints the collection of reports. If the report from collection is not rendered then its rendering starts.

**Parameters**

- **reports** (List<[StiReport](StiReport.md)>) — Collection of reports to print.  
- **showPrintDialog** (bool) — If a parameter is true then the print dialog will be shown.  
- **copies** (short) — A number of copies to print.  
- **printerSettings** (PrinterSettings) — Specifies information about how a document is printed, including the printer that prints it.  


---

#### PrintReportsAsync

**PrintReportsAsync**(**reports**: List<[StiReport](StiReport.md)>): Task<[StiReport](StiReport.md)>

Prints the collection of reports. If the report from collection is not rendered then its rendering starts.

**Parameters**

- **reports** (List<[StiReport](StiReport.md)>) — Collection of reports to print.  

**Returns** Task<[StiReport](StiReport.md)>

---

**PrintReportsAsync**(**reports**: List<[StiReport](StiReport.md)>, **copies**: short): Task<[StiReport](StiReport.md)>

Prints the collection of reports. If the report from collection is not rendered then its rendering starts.

**Parameters**

- **reports** (List<[StiReport](StiReport.md)>) — Collection of reports to print.  
- **copies** (short) — A number of copies to print.  

**Returns** Task<[StiReport](StiReport.md)>

---

**PrintReportsAsync**(**reports**: List<[StiReport](StiReport.md)>, **copies**: short, **printerSettings**: PrinterSettings): Task<[StiReport](StiReport.md)>

Prints the collection of reports. If the report from collection is not rendered then its rendering starts.

**Parameters**

- **reports** (List<[StiReport](StiReport.md)>) — Collection of reports to print.  
- **copies** (short) — A number of copies to print.  
- **printerSettings** (PrinterSettings) — Specifies information about how a document is printed, including the printer that prints it.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### PrintToDotMatrixPrinter

**PrintToDotMatrixPrinter**(): [StiReport](StiReport.md)

Prints a report to default dot-matrix printer in the RAW mode in ASCII encoding.

**Returns** [StiReport](StiReport.md)

---

**PrintToDotMatrixPrinter**(**printerName**: string): [StiReport](StiReport.md)

Prints a report to dot-matrix printer in the RAW mode in ASCII encoding.

**Parameters**

- **printerName** (string) — A name of a printer.  

**Returns** [StiReport](StiReport.md)

---

**PrintToDotMatrixPrinter**(**printerName**: string, **encoding**: Encoding): [StiReport](StiReport.md)

Prints report to dot-matrix printer in the RAW mode.

**Parameters**

- **printerName** (string) — A name of a printer.  
- **encoding** (Encoding) — A parameter which sets text encoding.  

**Returns** [StiReport](StiReport.md)

---

**PrintToDotMatrixPrinter**(**printerName**: string, **encoding**: Encoding, **fromPage**: int, **toPage**: int): [StiReport](StiReport.md)

Prints a report to dot-matrix printer in the RAW mode.

**Parameters**

- **printerName** (string) — A name of a printer.  
- **encoding** (Encoding) — A parameter which sets text encoding.  
- **fromPage** (int) — A number of the first page to print.  
- **toPage** (int) — A number of the last page to print.  

**Returns** [StiReport](StiReport.md)


---

#### PrintWithWpf

**PrintWithWpf**(): [StiReport](StiReport.md)

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Returns** [StiReport](StiReport.md)

---

**PrintWithWpf**(**printerName**: string): [StiReport](StiReport.md)

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **printerName** (string) — A name of a printer that will be used for printing.  

**Returns** [StiReport](StiReport.md)

---

**PrintWithWpf**(**printTicket**: object): [StiReport](StiReport.md)

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **printTicket** (object) — Specifies information about how a document is printed.  

**Returns** [StiReport](StiReport.md)

---

**PrintWithWpf**(**showPrintDialog**: bool): [StiReport](StiReport.md)

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **showPrintDialog** (bool) — Show the print dialog or no.  

**Returns** [StiReport](StiReport.md)

---

**PrintWithWpf**(**printTicket**: object, **showPrintDialog**: bool): [StiReport](StiReport.md)

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **printTicket** (object) — Specifies information about how a document is printed.  
- **showPrintDialog** (bool) — Show the print dialog or no.  

**Returns** [StiReport](StiReport.md)

---

**PrintWithWpf**(**copies**: int): [StiReport](StiReport.md)

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **copies** (int) — Number of copies to print.  

**Returns** [StiReport](StiReport.md)

---

**PrintWithWpf**(**showPrintDialog**: bool, **copies**: int): [StiReport](StiReport.md)

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **showPrintDialog** (bool) — Show the print dialog or no.  
- **copies** (int) — Number of copies to print.  

**Returns** [StiReport](StiReport.md)

---

**PrintWithWpf**(**showPrintDialog**: bool, **copies**: int, **printerName**: string): [StiReport](StiReport.md)

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **showPrintDialog** (bool) — Show the print dialog or no.  
- **copies** (int) — Number of copies to print.  
- **printerName** (string) — A name of a printer that will be used for printing.  

**Returns** [StiReport](StiReport.md)

---

**PrintWithWpf**(**showPrintDialog**: bool, **fromPage**: int, **toPage**: int, **copies**: int): [StiReport](StiReport.md)

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **showPrintDialog** (bool) — Show the print dialog or no.  
- **fromPage** (int) — Number of the first page to print. Starts from 1.  
- **toPage** (int) — Number of the last page to print. Starts from 1.  
- **copies** (int) — Number of copies to print.  

**Returns** [StiReport](StiReport.md)

---

**PrintWithWpf**(**showPrintDialog**: bool, **fromPage**: int, **toPage**: int, **copies**: int, **printerName**: string): [StiReport](StiReport.md)

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **showPrintDialog** (bool) — Show the print dialog or no.  
- **fromPage** (int) — Number of the first page to print. Starts from 1.  
- **toPage** (int) — Number of the last page to print. Starts from 1.  
- **copies** (int) — Number of copies to print.  
- **printerName** (string) — A name of a printer that will be used for printing.  

**Returns** [StiReport](StiReport.md)

---

**PrintWithWpf**(**printTicket**: object, **showPrintDialog**: bool, **fromPage**: int, **toPage**: int, **copies**: int, **printerName**: string): [StiReport](StiReport.md)

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **printTicket** (object) — Specifies information about how a document is printed.  
- **showPrintDialog** (bool) — Show the print dialog or no.  
- **fromPage** (int) — Number of the first page to print. Starts from 1.  
- **toPage** (int) — Number of the last page to print. Starts from 1.  
- **copies** (int) — Number of copies to print.  
- **printerName** (string) — A name of a printer that will be used for printing.  

**Returns** [StiReport](StiReport.md)


---

#### PrintWithWpfAsync

**PrintWithWpfAsync**(): Task<[StiReport](StiReport.md)>

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Returns** Task<[StiReport](StiReport.md)>

---

**PrintWithWpfAsync**(**printerName**: string): Task<[StiReport](StiReport.md)>

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **printerName** (string) — A name of a printer that will be used for printing.  

**Returns** Task<[StiReport](StiReport.md)>

---

**PrintWithWpfAsync**(**printTicket**: object): Task<[StiReport](StiReport.md)>

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **printTicket** (object) — Specifies information about how a document is printed.  

**Returns** Task<[StiReport](StiReport.md)>

---

**PrintWithWpfAsync**(**copies**: int): Task<[StiReport](StiReport.md)>

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **copies** (int) — Number of copies to print.  

**Returns** Task<[StiReport](StiReport.md)>

---

**PrintWithWpfAsync**(**copies**: int, **printerName**: string): Task<[StiReport](StiReport.md)>

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **copies** (int) — Number of copies to print.  
- **printerName** (string) — A name of a printer that will be used for printing.  

**Returns** Task<[StiReport](StiReport.md)>

---

**PrintWithWpfAsync**(**fromPage**: int, **toPage**: int, **copies**: int): Task<[StiReport](StiReport.md)>

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **fromPage** (int) — Number of the first page to print. Starts from 1.  
- **toPage** (int) — Number of the last page to print. Starts from 1.  
- **copies** (int) — Number of copies to print.  

**Returns** Task<[StiReport](StiReport.md)>

---

**PrintWithWpfAsync**(**fromPage**: int, **toPage**: int, **copies**: int, **printerName**: string): Task<[StiReport](StiReport.md)>

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **fromPage** (int) — Number of the first page to print. Starts from 1.  
- **toPage** (int) — Number of the last page to print. Starts from 1.  
- **copies** (int) — Number of copies to print.  
- **printerName** (string) — A name of a printer that will be used for printing.  

**Returns** Task<[StiReport](StiReport.md)>

---

**PrintWithWpfAsync**(**printTicket**: object, **fromPage**: int, **toPage**: int, **copies**: int, **printerName**: string): Task<[StiReport](StiReport.md)>

Prints the rendered report with using WPF technology. If the report is not rendered then its rendering starts. This method require Stimulsoft.Report.Wpf assembly.

**Parameters**

- **printTicket** (object) — Specifies information about how a document is printed.  
- **fromPage** (int) — Number of the first page to print. Starts from 1.  
- **toPage** (int) — Number of the last page to print. Starts from 1.  
- **copies** (int) — Number of copies to print.  
- **printerName** (string) — A name of a printer that will be used for printing.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### PrintWithXbap

**PrintWithXbap**(): [StiReport](StiReport.md)

**Returns** [StiReport](StiReport.md)

---

**PrintWithXbap**(**printerName**: string): [StiReport](StiReport.md)

**Parameters**

- **printerName** (string)  

**Returns** [StiReport](StiReport.md)

---

**PrintWithXbap**(**printTicket**: object): [StiReport](StiReport.md)

**Parameters**

- **printTicket** (object)  

**Returns** [StiReport](StiReport.md)

---

**PrintWithXbap**(**showPrintDialog**: bool): [StiReport](StiReport.md)

**Parameters**

- **showPrintDialog** (bool)  

**Returns** [StiReport](StiReport.md)

---

**PrintWithXbap**(**printTicket**: object, **showPrintDialog**: bool): [StiReport](StiReport.md)

**Parameters**

- **printTicket** (object)  
- **showPrintDialog** (bool)  

**Returns** [StiReport](StiReport.md)

---

**PrintWithXbap**(**copies**: int): [StiReport](StiReport.md)

**Parameters**

- **copies** (int)  

**Returns** [StiReport](StiReport.md)

---

**PrintWithXbap**(**showPrintDialog**: bool, **copies**: int): [StiReport](StiReport.md)

**Parameters**

- **showPrintDialog** (bool)  
- **copies** (int)  

**Returns** [StiReport](StiReport.md)

---

**PrintWithXbap**(**showPrintDialog**: bool, **copies**: int, **printerName**: string): [StiReport](StiReport.md)

**Parameters**

- **showPrintDialog** (bool)  
- **copies** (int)  
- **printerName** (string)  

**Returns** [StiReport](StiReport.md)

---

**PrintWithXbap**(**showPrintDialog**: bool, **fromPage**: int, **toPage**: int, **copies**: int): [StiReport](StiReport.md)

**Parameters**

- **showPrintDialog** (bool)  
- **fromPage** (int)  
- **toPage** (int)  
- **copies** (int)  

**Returns** [StiReport](StiReport.md)

---

**PrintWithXbap**(**showPrintDialog**: bool, **fromPage**: int, **toPage**: int, **copies**: int, **printerName**: string): [StiReport](StiReport.md)

**Parameters**

- **showPrintDialog** (bool)  
- **fromPage** (int)  
- **toPage** (int)  
- **copies** (int)  
- **printerName** (string)  

**Returns** [StiReport](StiReport.md)

---

**PrintWithXbap**(**printTicket**: object, **showPrintDialog**: bool, **fromPage**: int, **toPage**: int, **copies**: int, **printerName**: string): [StiReport](StiReport.md)

**Parameters**

- **printTicket** (object)  
- **showPrintDialog** (bool)  
- **fromPage** (int)  
- **toPage** (int)  
- **copies** (int)  
- **printerName** (string)  

**Returns** [StiReport](StiReport.md)


---

#### RecalculateRenderedPagesSegments

**RecalculateRenderedPagesSegments**(): [StiReport](StiReport.md)

Recalculate segments in all rendered pages

**Returns** [StiReport](StiReport.md)


---

#### RegBusinessObject

**RegBusinessObject**(**name**: string, **value**: object, **synchronize**: bool): [StiReport](StiReport.md)

Registers the business object in the report.

**Parameters**

- **name** (string) — Name of the registered business object.  
- **value** (object) — Business object.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegBusinessObject**(**category**: string, **name**: string, **value**: object, **synchronize**: bool): [StiReport](StiReport.md)

Registers the business object in the report.

**Parameters**

- **category** (string) — Name of the category in which registered business object will be placed in report dictionary.  
- **name** (string) — Name of the registered business object.  
- **value** (object) — Business object.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegBusinessObject**(**category**: string, **name**: string, **alias**: string, **value**: object, **synchronize**: bool): [StiReport](StiReport.md)

Registers the business object in the report.

**Parameters**

- **category** (string) — Name of the category in which registered business object will be placed in report dictionary.  
- **name** (string) — Name of the registered business object.  
- **alias** (string) — Alias of the registered business object.  
- **value** (object) — Business object.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegBusinessObject**(**businessObjects**: List<[StiBusinessObjectData](../Dictionary/StiBusinessObjectData.md)>, **synchronize**: bool): [StiReport](StiReport.md)

Registers list of business objects in business objects store of specified report.

**Parameters**

- **businessObjects** (List<[StiBusinessObjectData](../Dictionary/StiBusinessObjectData.md)>) — List of business objects.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)


---

#### RegBusinessObjectAsync

**RegBusinessObjectAsync**(**category**: string, **name**: string, **alias**: string, **value**: object, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers the business object in the report.

**Parameters**

- **category** (string) — Name of the category in which registered business object will be placed in report dictionary.  
- **name** (string) — Name of the registered business object.  
- **alias** (string) — Alias of the registered business object.  
- **value** (object) — Business object.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegBusinessObjectAsync**(**businessObjects**: List<[StiBusinessObjectData](../Dictionary/StiBusinessObjectData.md)>, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers list of business objects in business objects store of specified report.

**Parameters**

- **businessObjects** (List<[StiBusinessObjectData](../Dictionary/StiBusinessObjectData.md)>) — List of business objects.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### RegCsvData

**RegCsvData**(**name**: string, ****: bytedata, **synchronize**: bool): StiDatabase

Registers a new connection to the CSV data file.

**Parameters**

- **name** (string) — A name of the CSV connection in the dictionary.  
- **** (bytedata)  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the CSV data file will be created or updated in the Dictionary.  

**Returns** StiDatabase — The created connection in the dictionary.


---

#### RegCsvDataAsync

**RegCsvDataAsync**(**name**: string, ****: bytedata, **synchronize**: bool): Task<StiDatabase>

Asynchronously registers a new connection to the CSV data file.

**Parameters**

- **name** (string) — A name of the CSV connection in the dictionary.  
- **** (bytedata)  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the CSV data file will be created or updated in the Dictionary.  

**Returns** Task<StiDatabase> — The created connection in the dictionary.


---

#### RegCsvFile

**RegCsvFile**(**name**: string, **fileName**: string, **synchronize**: bool): StiDatabase

Registers a new connection to the CSV data file.

**Parameters**

- **name** (string) — A name of the CSV connection in the dictionary.  
- **fileName** (string) — A file path to the CSV data file.  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the CSV data file will be created or updated in the Dictionary.  

**Returns** StiDatabase — The created connection in the dictionary.


---

#### RegCsvFileAsync

**RegCsvFileAsync**(**name**: string, **fileName**: string, **synchronize**: bool): Task<StiDatabase>

Registers a new connection to the CSV data file.

**Parameters**

- **name** (string) — A name of the CSV connection in the dictionary.  
- **fileName** (string) — A file path to the CSV data file.  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the CSV data file will be created or updated in the Dictionary.  

**Returns** Task<StiDatabase> — The created connection in the dictionary.


---

#### RegData

**RegData**(**name**: string, **data**: object, **synchronize**: bool): [StiReport](StiReport.md)

Registers an object in the Data Store.

**Parameters**

- **name** (string) — A data name in the Data Store.  
- **data** (object) — The object for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**name**: string, **dataTable**: DataTable, **synchronize**: bool): [StiReport](StiReport.md)

Registers an object in the Data Store.

**Parameters**

- **name** (string) — DataTable name in the Data Store.  
- **dataTable** (DataTable) — DataTable for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**dataTable**: DataTable, **synchronize**: bool): [StiReport](StiReport.md)

Registers the DataTable in the Data Store.

**Parameters**

- **dataTable** (DataTable) — The DataTable for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**name**: string, **dataSet**: DataSet, **synchronize**: bool): [StiReport](StiReport.md)

Registers all Data-Tables and Data-Relations which are in the specified DataSet in the report.

**Parameters**

- **name** (string) — A name for the DataSet registration.  
- **dataSet** (DataSet) — The DataSet for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**dataSet**: DataSet, **synchronize**: bool): [StiReport](StiReport.md)

Registers all DataTable and DataRelation which are in the specified DataSet in the Data Store.

**Parameters**

- **dataSet** (DataSet) — DataSet for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**name**: string, **dataView**: DataView, **synchronize**: bool): [StiReport](StiReport.md)

Registers DataView in the Data Store.

**Parameters**

- **name** (string) — DataView name in the Data Store.  
- **dataView** (DataView) — DataView for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**dataView**: DataView, **synchronize**: bool): [StiReport](StiReport.md)

Registers DataView in the Data Store.

**Parameters**

- **dataView** (DataView) — DataView for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**name**: string, **connection**: SqlConnection, **synchronize**: bool): [StiReport](StiReport.md)

Registers SqlConnection in the Data Store.

**Parameters**

- **name** (string) — SqlConnection name in the Data Store.  
- **connection** (SqlConnection) — SqlConnection for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**name**: string, **connection**: OleDbConnection, **synchronize**: bool): [StiReport](StiReport.md)

Registers OleDbConnection in the Data Store.

**Parameters**

- **name** (string) — OleDbConnection name in the Data Store.  
- **connection** (OleDbConnection) — OleDbConnection for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**name**: string, **connection**: OdbcConnection, **synchronize**: bool): [StiReport](StiReport.md)

Registers OdbcConnection in the Data Store.

**Parameters**

- **name** (string) — OdbcConnection name in the Data Store.  
- **connection** (OdbcConnection) — OdbcConnection for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**name**: string, **alias**: string, **data**: object, **synchronize**: bool): [StiReport](StiReport.md)

Registers an object in the Data Store.

**Parameters**

- **name** (string) — A data name in the Data Store.  
- **alias** (string) — A data alias in the Data Store.  
- **data** (object) — The object for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**name**: string, **alias**: string, **dataTable**: DataTable, **synchronize**: bool): [StiReport](StiReport.md)

Registers an object in the Data Store.

**Parameters**

- **name** (string) — A data name in the Data Store.  
- **alias** (string) — A data alias in the Data Store.  
- **dataTable** (DataTable) — DataTable for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**name**: string, **alias**: string, **dataSet**: DataSet, **synchronize**: bool): [StiReport](StiReport.md)

Registers all DataTables and DataRelations which are in the specified DataSet in the Data Store.

**Parameters**

- **name** (string) — A data name in the Data Store.  
- **alias** (string) — A data alias in the Data Store.  
- **dataSet** (DataSet) — DataSet for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**name**: string, **alias**: string, **dataView**: DataView, **synchronize**: bool): [StiReport](StiReport.md)

Registers DataView in the Data Store.

**Parameters**

- **name** (string) — A data name in the Data Store.  
- **alias** (string) — A data alias in the Data Store.  
- **dataView** (DataView) — DataView for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**name**: string, **alias**: string, **connection**: SqlConnection, **synchronize**: bool): [StiReport](StiReport.md)

Registers SqlConnection in the Data Store.

**Parameters**

- **name** (string) — A data name in the Data Store.  
- **alias** (string) — A data alias in the Data Store.  
- **connection** (SqlConnection) — SqlConnection for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**name**: string, **alias**: string, **connection**: OleDbConnection, **synchronize**: bool): [StiReport](StiReport.md)

Registers OleDbConnection in the Data Store.

**Parameters**

- **name** (string) — A data name in the Data Store.  
- **alias** (string) — A data alias in the Data Store.  
- **connection** (OleDbConnection) — OleDbConnection for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**name**: string, **alias**: string, **connection**: OdbcConnection, **synchronize**: bool): [StiReport](StiReport.md)

Registers OdbcConnection in the Data Store.

**Parameters**

- **name** (string) — A data name in the Data Store.  
- **alias** (string) — A data alias in the Data Store.  
- **connection** (OdbcConnection) — OdbcConnection for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)

---

**RegData**(**datas**: [StiDataCollection](../Dictionary/StiDataCollection.md), **synchronize**: bool): [StiReport](StiReport.md)

Registers the DataCollection in the DataStore of the report.

**Parameters**

- **datas** ([StiDataCollection](../Dictionary/StiDataCollection.md)) — DataCollection for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** [StiReport](StiReport.md)


---

#### RegDataAsync

**RegDataAsync**(**name**: string, **data**: object, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers an object in the Data Store.

**Parameters**

- **name** (string) — A data name in the Data Store.  
- **data** (object) — The object for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**name**: string, **dataTable**: DataTable, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers an object in the Data Store.

**Parameters**

- **name** (string) — DataTable name in the Data Store.  
- **dataTable** (DataTable) — DataTable for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**dataTable**: DataTable, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers the DataTable in the Data Store.

**Parameters**

- **dataTable** (DataTable) — The DataTable for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**name**: string, **dataSet**: DataSet, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers all Data-Tables and Data-Relations which are in the specified DataSet in the report.

**Parameters**

- **name** (string) — A name for the DataSet registration.  
- **dataSet** (DataSet) — The DataSet for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**dataSet**: DataSet, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers all DataTable and DataRelation which are in the specified DataSet in the Data Store.

**Parameters**

- **dataSet** (DataSet) — DataSet for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**name**: string, **dataView**: DataView, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers DataView in the Data Store.

**Parameters**

- **name** (string) — DataView name in the Data Store.  
- **dataView** (DataView) — DataView for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**dataView**: DataView, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers DataView in the Data Store.

**Parameters**

- **dataView** (DataView) — DataView for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**name**: string, **connection**: SqlConnection, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers SqlConnection in the Data Store.

**Parameters**

- **name** (string) — SqlConnection name in the Data Store.  
- **connection** (SqlConnection) — SqlConnection for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**name**: string, **connection**: OleDbConnection, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers OleDbConnection in the Data Store.

**Parameters**

- **name** (string) — OleDbConnection name in the Data Store.  
- **connection** (OleDbConnection) — OleDbConnection for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**name**: string, **connection**: OdbcConnection, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers OdbcConnection in the Data Store.

**Parameters**

- **name** (string) — OdbcConnection name in the Data Store.  
- **connection** (OdbcConnection) — OdbcConnection for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**name**: string, **alias**: string, **data**: object, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers an object in the Data Store.

**Parameters**

- **name** (string) — A data name in the Data Store.  
- **alias** (string) — A data alias in the Data Store.  
- **data** (object) — The object for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**name**: string, **alias**: string, **dataTable**: DataTable, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers an object in the Data Store.

**Parameters**

- **name** (string) — A data name in the Data Store.  
- **alias** (string) — A data alias in the Data Store.  
- **dataTable** (DataTable) — DataTable for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**name**: string, **alias**: string, **dataSet**: DataSet, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers all DataTables and DataRelations which are in the specified DataSet in the Data Store.

**Parameters**

- **name** (string) — A data name in the Data Store.  
- **alias** (string) — A data alias in the Data Store.  
- **dataSet** (DataSet) — DataSet for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**name**: string, **alias**: string, **dataView**: DataView, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers DataView in the Data Store.

**Parameters**

- **name** (string) — A data name in the Data Store.  
- **alias** (string) — A data alias in the Data Store.  
- **dataView** (DataView) — DataView for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**name**: string, **alias**: string, **connection**: SqlConnection, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers SqlConnection in the Data Store.

**Parameters**

- **name** (string) — A data name in the Data Store.  
- **alias** (string) — A data alias in the Data Store.  
- **connection** (SqlConnection) — SqlConnection for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**name**: string, **alias**: string, **connection**: OleDbConnection, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers OleDbConnection in the Data Store.

**Parameters**

- **name** (string) — A data name in the Data Store.  
- **alias** (string) — A data alias in the Data Store.  
- **connection** (OleDbConnection) — OleDbConnection for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**name**: string, **alias**: string, **connection**: OdbcConnection, **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers OdbcConnection in the Data Store.

**Parameters**

- **name** (string) — A data name in the Data Store.  
- **alias** (string) — A data alias in the Data Store.  
- **connection** (OdbcConnection) — OdbcConnection for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RegDataAsync**(**datas**: [StiDataCollection](../Dictionary/StiDataCollection.md), **synchronize**: bool): Task<[StiReport](StiReport.md)>

Asynchronously registers the DataCollection in the DataStore of the report.

**Parameters**

- **datas** ([StiDataCollection](../Dictionary/StiDataCollection.md)) — DataCollection for registration.  
- **synchronize** (bool) — Synchronizes, if true, the content of the DataStore and Dictionary. If DataSources or Columns or Relations from the DataStore does not exists in Dictionary, then new elements will be added to the Dictionary.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### RegDbfData

**RegDbfData**(**name**: string, ****: bytedata, **synchronize**: bool): StiDatabase

Registers a new connection to the DBF data file.

**Parameters**

- **name** (string) — A name of the DBF connection in the dictionary.  
- **** (bytedata)  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the DBF data file will be created or updated in the Dictionary.  

**Returns** StiDatabase — The created connection in the dictionary.


---

#### RegDbfDataAsync

**RegDbfDataAsync**(**name**: string, ****: bytedata, **synchronize**: bool): Task<StiDatabase>

Asynchronously registers a new connection to the DBF data file.

**Parameters**

- **name** (string) — A name of the DBF connection in the dictionary.  
- **** (bytedata)  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the DBF data file will be created or updated in the Dictionary.  

**Returns** Task<StiDatabase> — The created connection in the dictionary.


---

#### RegDbfFile

**RegDbfFile**(**name**: string, **fileName**: string, **synchronize**: bool): StiDatabase

Registers a new connection to the DBF data file.

**Parameters**

- **name** (string) — A name of the DBF connection in the dictionary.  
- **fileName** (string) — A file path to the DBF data file.  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the DBF data file will be created or updated in the Dictionary.  

**Returns** StiDatabase — The created connection in the dictionary.


---

#### RegDbfFileAsync

**RegDbfFileAsync**(**name**: string, **fileName**: string, **synchronize**: bool): Task<StiDatabase>

Registers a new connection to the DBF data file.

**Parameters**

- **name** (string) — A name of the DBF connection in the dictionary.  
- **fileName** (string) — A file path to the DBF data file.  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the DBF data file will be created or updated in the Dictionary.  

**Returns** Task<StiDatabase> — The created connection in the dictionary.


---

#### RegExcelData

**RegExcelData**(**name**: string, ****: bytedata, **synchronize**: bool): StiDatabase

Registers a new connection to the EXCEL data file.

**Parameters**

- **name** (string) — A name of the EXCEL connection in the dictionary.  
- **** (bytedata)  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the EXCEL data file will be created or updated in the Dictionary.  

**Returns** StiDatabase — The created connection in the dictionary.


---

#### RegExcelDataAsync

**RegExcelDataAsync**(**name**: string, ****: bytedata, **synchronize**: bool): Task<StiDatabase>

Asynchronously registers a new connection to the EXCEL data file.

**Parameters**

- **name** (string) — A name of the EXCEL connection in the dictionary.  
- **** (bytedata)  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the EXCEL data file will be created or updated in the Dictionary.  

**Returns** Task<StiDatabase> — The created connection in the dictionary.


---

#### RegExcelFile

**RegExcelFile**(**name**: string, **fileName**: string, **synchronize**: bool): StiDatabase

Registers a new connection to the EXCEL data file.

**Parameters**

- **name** (string) — A name of the EXCEL connection in the dictionary.  
- **fileName** (string) — A file path to the EXCEL data file.  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the EXCEL data file will be created or updated in the Dictionary.  

**Returns** StiDatabase — The created connection in the dictionary.


---

#### RegExcelFileAsync

**RegExcelFileAsync**(**name**: string, **fileName**: string, **synchronize**: bool): Task<StiDatabase>

Registers a new connection to the EXCEL data file.

**Parameters**

- **name** (string) — A name of the EXCEL connection in the dictionary.  
- **fileName** (string) — A file path to the EXCEL data file.  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the EXCEL data file will be created or updated in the Dictionary.  

**Returns** Task<StiDatabase> — The created connection in the dictionary.


---

#### RegFirebirdConnection

**RegFirebirdConnection**(**name**: string, **connectionString**: string, **synchronize**: bool): StiDatabase

Registers a Firebird connection.

**Parameters**

- **name** (string) — The name of the connection.  
- **connectionString** (string) — The connection string.  
- **synchronize** (bool) — Indicates whether to synchronize the connection.  

**Returns** StiDatabase — The registered database.


---

#### RegFirebirdConnectionAsync

**RegFirebirdConnectionAsync**(**name**: string, **connectionString**: string, **synchronize**: bool): Task<StiDatabase>

Asynchronously registers a Firebird connection.

**Parameters**

- **name** (string) — The name of the connection.  
- **connectionString** (string) — The connection string.  
- **synchronize** (bool) — Indicates whether to synchronize the connection.  

**Returns** Task<StiDatabase> — A task that represents the asynchronous operation. The task result contains the registered database.


---

#### RegJsonData

**RegJsonData**(**name**: string, ****: bytedata, **synchronize**: bool): StiDatabase

Registers a new connection to the JSON data file.

**Parameters**

- **name** (string) — A name of the JSON connection in the dictionary.  
- **** (bytedata)  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the JSON data file will be created or updated in the Dictionary.  

**Returns** StiDatabase — The created connection in the dictionary.


---

#### RegJsonDataAsync

**RegJsonDataAsync**(**name**: string, ****: bytedata, **synchronize**: bool): Task<StiDatabase>

Asynchronously registers a new connection to the JSON data file.

**Parameters**

- **name** (string) — A name of the JSON connection in the dictionary.  
- **** (bytedata)  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the JSON data file will be created or updated in the Dictionary.  

**Returns** Task<StiDatabase> — The created connection in the dictionary.


---

#### RegJsonFile

**RegJsonFile**(**name**: string, **fileName**: string, **synchronize**: bool): StiDatabase

Registers a new connection to the JSON data file.

**Parameters**

- **name** (string) — A name of the JSON connection in the dictionary.  
- **fileName** (string) — A file path to the JSON data file.  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the JSON data file will be created or updated in the Dictionary.  

**Returns** StiDatabase — The created connection in the dictionary.


---

#### RegJsonFileAsync

**RegJsonFileAsync**(**name**: string, **fileName**: string, **synchronize**: bool): Task<StiDatabase>

Registers a new connection to the JSON data file.

**Parameters**

- **name** (string) — A name of the JSON connection in the dictionary.  
- **fileName** (string) — A file path to the JSON data file.  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the JSON data file will be created or updated in the Dictionary.  

**Returns** Task<StiDatabase> — The created connection in the dictionary.


---

#### RegMySqlConnection

**RegMySqlConnection**(**name**: string, **connectionString**: string, **synchronize**: bool): StiDatabase

Registers a MySQL connection.

**Parameters**

- **name** (string) — The name of the connection.  
- **connectionString** (string) — The connection string.  
- **synchronize** (bool) — Indicates whether to synchronize the connection.  

**Returns** StiDatabase — The registered database.


---

#### RegMySqlConnectionAsync

**RegMySqlConnectionAsync**(**name**: string, **connectionString**: string, **synchronize**: bool): Task<StiDatabase>

Asynchronously registers a MySQL connection.

**Parameters**

- **name** (string) — The name of the connection.  
- **connectionString** (string) — The connection string.  
- **synchronize** (bool) — Indicates whether to synchronize the connection.  

**Returns** Task<StiDatabase> — A task that represents the asynchronous operation. The task result contains the registered database.


---

#### RegOdbcConnection

**RegOdbcConnection**(**name**: string, **connectionString**: string, **synchronize**: bool): StiDatabase

Registers an ODBC connection.

**Parameters**

- **name** (string) — The name of the connection.  
- **connectionString** (string) — The connection string.  
- **synchronize** (bool) — Indicates whether to synchronize the connection.  

**Returns** StiDatabase — The registered database.


---

#### RegOdbcConnectionAsync

**RegOdbcConnectionAsync**(**name**: string, **connectionString**: string, **synchronize**: bool): Task<StiDatabase>

Asynchronously registers an ODBC connection.

**Parameters**

- **name** (string) — The name of the connection.  
- **connectionString** (string) — The connection string.  
- **synchronize** (bool) — Indicates whether to synchronize the connection.  

**Returns** Task<StiDatabase> — A task that represents the asynchronous operation. The task result contains the registered database.


---

#### RegOleDbConnection

**RegOleDbConnection**(**name**: string, **connectionString**: string, **synchronize**: bool): StiDatabase

Registers an OLEDB connection.

**Parameters**

- **name** (string) — The name of the connection.  
- **connectionString** (string) — The connection string.  
- **synchronize** (bool) — Indicates whether to synchronize the connection.  

**Returns** StiDatabase — The registered database.


---

#### RegOleDbConnectionAsync

**RegOleDbConnectionAsync**(**name**: string, **connectionString**: string, **synchronize**: bool): Task<StiDatabase>

Asynchronously registers an OLEDB connection.

**Parameters**

- **name** (string) — The name of the connection.  
- **connectionString** (string) — The connection string.  
- **synchronize** (bool) — Indicates whether to synchronize the connection.  

**Returns** Task<StiDatabase> — A task that represents the asynchronous operation. The task result contains the registered database.


---

#### RegOracleConnection

**RegOracleConnection**(**name**: string, **connectionString**: string, **synchronize**: bool): StiDatabase

Registers an Oracle connection.

**Parameters**

- **name** (string) — The name of the connection.  
- **connectionString** (string) — The connection string.  
- **synchronize** (bool) — Indicates whether to synchronize the connection.  

**Returns** StiDatabase — The registered database.


---

#### RegOracleConnectionAsync

**RegOracleConnectionAsync**(**name**: string, **connectionString**: string, **synchronize**: bool): Task<StiDatabase>

Asynchronously registers an Oracle connection.

**Parameters**

- **name** (string) — The name of the connection.  
- **connectionString** (string) — The connection string.  
- **synchronize** (bool) — Indicates whether to synchronize the connection.  

**Returns** Task<StiDatabase> — A task that represents the asynchronous operation. The task result contains the registered database.


---

#### RegPostgreSqlConnection

**RegPostgreSqlConnection**(**name**: string, **connectionString**: string, **synchronize**: bool): StiDatabase

Registers a PostgreSQL connection.

**Parameters**

- **name** (string) — The name of the connection.  
- **connectionString** (string) — The connection string.  
- **synchronize** (bool) — Indicates whether to synchronize the connection.  

**Returns** StiDatabase — The registered database.


---

#### RegPostgreSqlConnectionAsync

**RegPostgreSqlConnectionAsync**(**name**: string, **connectionString**: string, **synchronize**: bool): Task<StiDatabase>

Asynchronously registers a PostgreSQL connection.

**Parameters**

- **name** (string) — The name of the connection.  
- **connectionString** (string) — The connection string.  
- **synchronize** (bool) — Indicates whether to synchronize the connection.  

**Returns** Task<StiDatabase> — A task that represents the asynchronous operation. The task result contains the registered database.


---

#### RegReportDataSources

**RegReportDataSources**(): [StiReport](StiReport.md)

Internal use only. Registers datasources from ReportDataSources property in report dictionary.

**Returns** [StiReport](StiReport.md)


---

#### RegSqlServerConnection

**RegSqlServerConnection**(**name**: string, **connectionString**: string, **synchronize**: bool): StiDatabase

Registers a SQL Server connection.

**Parameters**

- **name** (string) — The name of the connection.  
- **connectionString** (string) — The connection string.  
- **synchronize** (bool) — Indicates whether to synchronize the connection.  

**Returns** StiDatabase — The registered database.


---

#### RegSqlServerConnectionAsync

**RegSqlServerConnectionAsync**(**name**: string, **connectionString**: string, **synchronize**: bool): Task<StiDatabase>

Asynchronously registers a SQL Server connection.

**Parameters**

- **name** (string) — The name of the connection.  
- **connectionString** (string) — The connection string.  
- **synchronize** (bool) — Indicates whether to synchronize the connection.  

**Returns** Task<StiDatabase> — A task that represents the asynchronous operation. The task result contains the registered database.


---

#### RegXmlData

**RegXmlData**(**name**: string, ****: bytedata, **synchronize**: bool): StiDatabase

Registers a new connection to the XML data file.

**Parameters**

- **name** (string) — A name of the XML connection in the dictionary.  
- **** (bytedata)  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the XML data file will be created or updated in the Dictionary.  

**Returns** StiDatabase — The created connection in the dictionary.

---

**RegXmlData**(**name**: string, ****: byteschema, ****: bytedata, **synchronize**: bool): StiDatabase

Registers a new connection to the XML data file.

**Parameters**

- **name** (string) — A name of the XML connection in the dictionary.  
- **** (byteschema)  
- **** (bytedata)  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the XML data file will be created or updated in the Dictionary.  

**Returns** StiDatabase — The created connection in the dictionary.


---

#### RegXmlDataAsync

**RegXmlDataAsync**(**name**: string, ****: bytedata, **synchronize**: bool): Task<StiDatabase>

Asynchronously registers a new connection to the XML data file.

**Parameters**

- **name** (string) — A name of the XML connection in the dictionary.  
- **** (bytedata)  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the XML data file will be created or updated in the Dictionary.  

**Returns** Task<StiDatabase> — The created connection in the dictionary.

---

**RegXmlDataAsync**(**name**: string, ****: byteschema, ****: bytedata, **synchronize**: bool): Task<StiDatabase>

Asynchronously registers a new connection to the XML data file.

**Parameters**

- **name** (string) — A name of the XML connection in the dictionary.  
- **** (byteschema)  
- **** (bytedata)  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the XML data file will be created or updated in the Dictionary.  

**Returns** Task<StiDatabase> — The created connection in the dictionary.


---

#### RegXmlFile

**RegXmlFile**(**name**: string, **fileName**: string, **synchronize**: bool): StiDatabase

Registers a new connection to the XML data file.

**Parameters**

- **name** (string) — A name of the XML connection in the dictionary.  
- **fileName** (string) — A file path to the XML data file.  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the XML data file will be created or updated in the Dictionary.  

**Returns** StiDatabase — The created connection in the dictionary.


---

#### RegXmlFileAsync

**RegXmlFileAsync**(**name**: string, **fileName**: string, **synchronize**: bool): Task<StiDatabase>

Registers a new connection to the XML data file.

**Parameters**

- **name** (string) — A name of the XML connection in the dictionary.  
- **fileName** (string) — A file path to the XML data file.  
- **synchronize** (bool) — If true, then Data Sources, Columns and Relations from the XML data file will be created or updated in the Dictionary.  

**Returns** Task<StiDatabase> — The created connection in the dictionary.


---

#### Render

**Render**(): [StiReport](StiReport.md)

Renders a report.

**Returns** [StiReport](StiReport.md)

---

**Render**(**showProgress**: bool): [StiReport](StiReport.md)

Renders a report.

**Parameters**

- **showProgress** (bool) — Whether it is necessary to show the progress of report rendering or not.  

**Returns** [StiReport](StiReport.md)

---

**Render**(**showProgress**: bool, **fromPage**: int, **toPage**: int): [StiReport](StiReport.md)

Renders a report.

**Parameters**

- **showProgress** (bool) — Whether it is necessary to show the progress of report rendering or not.  
- **fromPage** (int) — Specifies from which page the result of the report rendering should be presented into the rendered report.  
- **toPage** (int) — Specifies to which page the result of the report rendering should be presented into the rendered report.  

**Returns** [StiReport](StiReport.md)

---

**Render**(**renderState**: [StiRenderState](../Engine/StiRenderState.md)): [StiReport](StiReport.md)

Renders report.

**Parameters**

- **renderState** ([StiRenderState](../Engine/StiRenderState.md)) — Specifies a parameters for the report rendering.  

**Returns** [StiReport](StiReport.md)


---

#### RenderAsync

**RenderAsync**(): Task<[StiReport](StiReport.md)>

Renders a report.

**Returns** Task<[StiReport](StiReport.md)>

---

**RenderAsync**(**fromPage**: int, **toPage**: int): Task<[StiReport](StiReport.md)>

Renders a report.

**Parameters**

- **fromPage** (int) — Specifies from which page the result of the report rendering should be presented into the rendered report.  
- **toPage** (int) — Specifies to which page the result of the report rendering should be presented into the rendered report.  

**Returns** Task<[StiReport](StiReport.md)>

---

**RenderAsync**(**renderState**: [StiRenderState](../Engine/StiRenderState.md)): Task<[StiReport](StiReport.md)>

Renders report.

**Parameters**

- **renderState** ([StiRenderState](../Engine/StiRenderState.md)) — Specifies a parameters for the report rendering.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### RenderWithWpf

**RenderWithWpf**(): [StiReport](StiReport.md)

Renders a report with using WPF technology.

**Returns** [StiReport](StiReport.md)

---

**RenderWithWpf**(**showProgress**: bool): [StiReport](StiReport.md)

Renders a report with using WPF technology.

**Parameters**

- **showProgress** (bool) — Whether it is necessary to show the progress of report rendering or not.  

**Returns** [StiReport](StiReport.md)

---

**RenderWithWpf**(**showProgress**: bool, **fromPage**: int, **toPage**: int): [StiReport](StiReport.md)

Renders a report with using WPF technology.

**Parameters**

- **showProgress** (bool) — Whether it is necessary to show the progress of report rendering or not.  
- **fromPage** (int)  
- **toPage** (int)  

**Returns** [StiReport](StiReport.md)

---

**RenderWithWpf**(**renderState**: [StiRenderState](../Engine/StiRenderState.md)): [StiReport](StiReport.md)

Renders a report with using WPF technology.

**Parameters**

- **renderState** ([StiRenderState](../Engine/StiRenderState.md))  

**Returns** [StiReport](StiReport.md)


---

#### ResetAggregateFunctions

**ResetAggregateFunctions**(): [StiReport](StiReport.md)

Resets states of aggregate functions in compiled report.

**Returns** [StiReport](StiReport.md)


---

#### ResetRenderedState

**ResetRenderedState**(): [StiReport](StiReport.md)

Resets a rendered states.

**Returns** [StiReport](StiReport.md)


---

#### Save

**Save**(**stream**: Stream): [StiReport](StiReport.md)

Saves a report template in the stream.

**Parameters**

- **stream** (Stream) — A stream for saving a report template.  

**Returns** [StiReport](StiReport.md)

---

**Save**(**service**: [StiReportSLService](../SaveLoad/StiReportSLService.md), **stream**: Stream): [StiReport](StiReport.md)

Saves a report template in the file using the provider.

**Parameters**

- **service** ([StiReportSLService](../SaveLoad/StiReportSLService.md)) — A provider which saves the report template.  
- **stream** (Stream) — A stream for saving a report template.  

**Returns** [StiReport](StiReport.md)

---

**Save**(**service**: [StiReportSLService](../SaveLoad/StiReportSLService.md), **path**: string): [StiReport](StiReport.md)

Saves a report template in the file using the provider.

**Parameters**

- **service** ([StiReportSLService](../SaveLoad/StiReportSLService.md)) — A provider for saving a rendered report.  
- **path** (string) — A file for saving the report template.  

**Returns** [StiReport](StiReport.md)

---

**Save**(**path**: string): [StiReport](StiReport.md)

Saves a report template in the file.

**Parameters**

- **path** (string) — A file to save a report template.  

**Returns** [StiReport](StiReport.md)


---

#### SaveAsync

**SaveAsync**(**stream**: Stream): Task<[StiReport](StiReport.md)>

Saves asynchronously a report template in the stream.

**Parameters**

- **stream** (Stream) — A stream for saving a report template.  

**Returns** Task<[StiReport](StiReport.md)>

---

**SaveAsync**(**service**: [StiReportSLService](../SaveLoad/StiReportSLService.md), **stream**: Stream): Task<[StiReport](StiReport.md)>

Saves asynchronously a report template in the file using the provider.

**Parameters**

- **service** ([StiReportSLService](../SaveLoad/StiReportSLService.md)) — A provider which saves the report template.  
- **stream** (Stream) — A stream for saving a report template.  

**Returns** Task<[StiReport](StiReport.md)>

---

**SaveAsync**(**service**: [StiReportSLService](../SaveLoad/StiReportSLService.md), **path**: string): Task<[StiReport](StiReport.md)>

Saves asynchronously a report template in the file using the provider.

**Parameters**

- **service** ([StiReportSLService](../SaveLoad/StiReportSLService.md)) — A provider for saving a rendered report.  
- **path** (string) — A file for saving the report template.  

**Returns** Task<[StiReport](StiReport.md)>

---

**SaveAsync**(**path**: string): Task<[StiReport](StiReport.md)>

Saves asynchronously a report template in the file.

**Parameters**

- **path** (string) — A file to save a report template.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### SaveDocument

**SaveDocument**(**stream**: Stream): [StiReport](StiReport.md)

Saves a rendered report in the stream.

**Parameters**

- **stream** (Stream) — A stream to save a rendered report.  

**Returns** [StiReport](StiReport.md)

---

**SaveDocument**(**service**: [StiDocumentSLService](../SaveLoad/StiDocumentSLService.md), **stream**: Stream): [StiReport](StiReport.md)

Saves a rendered report to the stream.

**Parameters**

- **service** ([StiDocumentSLService](../SaveLoad/StiDocumentSLService.md)) — A provider which saves a rendered report.  
- **stream** (Stream) — A stream to save a rendered report.  

**Returns** [StiReport](StiReport.md)

---

**SaveDocument**(**service**: [StiDocumentSLService](../SaveLoad/StiDocumentSLService.md), **path**: string): [StiReport](StiReport.md)

Saves a rendered report using the provider in the file.

**Parameters**

- **service** ([StiDocumentSLService](../SaveLoad/StiDocumentSLService.md)) — A provider that saves a rendered report.  
- **path** (string) — A file to save a rendered report.  

**Returns** [StiReport](StiReport.md)

---

**SaveDocument**(**path**: string): [StiReport](StiReport.md)

Saves a rendered report in the file.

**Parameters**

- **path** (string) — A file to save a rendered report.  

**Returns** [StiReport](StiReport.md)


---

#### SaveDocumentAsync

**SaveDocumentAsync**(**stream**: Stream): Task<[StiReport](StiReport.md)>

Saves asynchronously a rendered report in the stream.

**Parameters**

- **stream** (Stream) — A stream to save a rendered report.  

**Returns** Task<[StiReport](StiReport.md)>

---

**SaveDocumentAsync**(**service**: [StiDocumentSLService](../SaveLoad/StiDocumentSLService.md), **stream**: Stream): Task<[StiReport](StiReport.md)>

Saves asynchronously a rendered report to the stream.

**Parameters**

- **service** ([StiDocumentSLService](../SaveLoad/StiDocumentSLService.md)) — A provider which saves a rendered report.  
- **stream** (Stream) — A stream to save a rendered report.  

**Returns** Task<[StiReport](StiReport.md)>

---

**SaveDocumentAsync**(**service**: [StiDocumentSLService](../SaveLoad/StiDocumentSLService.md), **path**: string): Task<[StiReport](StiReport.md)>

Saves asynchronously a rendered report using the provider in the file.

**Parameters**

- **service** ([StiDocumentSLService](../SaveLoad/StiDocumentSLService.md)) — A provider that saves a rendered report.  
- **path** (string) — A file to save a rendered report.  

**Returns** Task<[StiReport](StiReport.md)>

---

**SaveDocumentAsync**(**path**: string): Task<[StiReport](StiReport.md)>

Saves asynchronously a rendered report in the file.

**Parameters**

- **path** (string) — A file to save a rendered report.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### SaveDocumentJsonToString

**SaveDocumentJsonToString**(): string

Saves a rendered report to the string.

**Returns** string — A string which contains the report template.


---

#### SaveDocumentJsonToStringAsync

**SaveDocumentJsonToStringAsync**(): Task<string>

Saves asynchronously a rendered report to the string.

**Returns** Task<string> — A string which contains the report template.


---

#### SaveDocumentToByteArray

**SaveDocumentToByteArray**(): byte[]

Saves a rendered report to the byte array.

**Returns** byte[] — Returns a byte array which contains a rendered report.


---

#### SaveDocumentToByteArrayAsync

**SaveDocumentToByteArrayAsync**(): Task<byte[]>

Saves asynchronously a rendered report to the byte array.

**Returns** Task<byte[]> — Returns a byte array which contains a rendered report.


---

#### SaveDocumentToString

**SaveDocumentToString**(): string

Saves a rendered report to the string.

**Returns** string — A string which contains the report template.


---

#### SaveDocumentToStringAsync

**SaveDocumentToStringAsync**(): Task<string>

Saves asynchronously a rendered report to the string.

**Returns** Task<string> — A string which contains the report template.


---

#### SaveEditableFields

**SaveEditableFields**(**path**: string): [StiReport](StiReport.md)

Saves the editable fields of rendered report to the stream.

**Parameters**

- **path** (string)  

**Returns** [StiReport](StiReport.md)

---

**SaveEditableFields**(**stream**: Stream): [StiReport](StiReport.md)

Saves the editable fields of rendered report to the stream.

**Parameters**

- **stream** (Stream) — Stream for saving the editable fields.  

**Returns** [StiReport](StiReport.md)


---

#### SaveEncryptedDocument

**SaveEncryptedDocument**(**stream**: Stream, **key**: string): [StiReport](StiReport.md)

Saves an encrypted rendered report to the stream.

**Parameters**

- **stream** (Stream) — A stream to save an encrypted rendered report.  
- **key** (string) — The key for encryption.  

**Returns** [StiReport](StiReport.md)

---

**SaveEncryptedDocument**(**path**: string, **key**: string): [StiReport](StiReport.md)

Saves a packed rendered report in the file.

**Parameters**

- **path** (string) — A file for saving a packed rendered report.  
- **key** (string)  

**Returns** [StiReport](StiReport.md)


---

#### SaveEncryptedDocumentAsync

**SaveEncryptedDocumentAsync**(**stream**: Stream, **key**: string): Task<[StiReport](StiReport.md)>

Saves asynchronously an encrypted rendered report to the stream.

**Parameters**

- **stream** (Stream) — A stream to save an encrypted rendered report.  
- **key** (string) — The key for encryption.  

**Returns** Task<[StiReport](StiReport.md)>

---

**SaveEncryptedDocumentAsync**(**path**: string, **key**: string): Task<[StiReport](StiReport.md)>

Saves asynchronously a packed rendered report in the file.

**Parameters**

- **path** (string) — A file for saving a packed rendered report.  
- **key** (string)  

**Returns** Task<[StiReport](StiReport.md)>


---

#### SaveEncryptedDocumentToByteArray

**SaveEncryptedDocumentToByteArray**(**key**: string): byte[]

Saves an encrypted rendered report to the byte array.

**Parameters**

- **key** (string)  

**Returns** byte[] — A byte array which contains an encrypted rendered report.


---

#### SaveEncryptedDocumentToByteArrayAsync

**SaveEncryptedDocumentToByteArrayAsync**(**key**: string): Task<byte[]>

Saves asynchronously an encrypted rendered report to the byte array.

**Parameters**

- **key** (string)  

**Returns** Task<byte[]> — A byte array which contains an encrypted rendered report.


---

#### SaveEncryptedDocumentToString

**SaveEncryptedDocumentToString**(**key**: string): string

Saves an encrypted rendered report to the string.

**Parameters**

- **key** (string)  

**Returns** string — A string which contains an encrypted rendered report.


---

#### SaveEncryptedDocumentToStringAsync

**SaveEncryptedDocumentToStringAsync**(**key**: string): Task<string>

Saves an encrypted rendered report to the string.

**Parameters**

- **key** (string)  

**Returns** Task<string> — A string which contains an encrypted rendered report.


---

#### SaveEncryptedReport

**SaveEncryptedReport**(**stream**: Stream, **key**: string): [StiReport](StiReport.md)

Saves an encrypted report template in the stream.

**Parameters**

- **stream** (Stream) — A stream to save an encrypted report template.  
- **key** (string)  

**Returns** [StiReport](StiReport.md)

---

**SaveEncryptedReport**(**path**: string, **key**: string): [StiReport](StiReport.md)

Saves an encrypted report template in the file.

**Parameters**

- **path** (string) — A file to save an encrypted report template.  
- **key** (string)  

**Returns** [StiReport](StiReport.md)


---

#### SaveEncryptedReportAsync

**SaveEncryptedReportAsync**(**stream**: Stream, **key**: string): Task<[StiReport](StiReport.md)>

Saves asynchronously an encrypted report template in the stream.

**Parameters**

- **stream** (Stream) — A stream to save an encrypted report template.  
- **key** (string)  

**Returns** Task<[StiReport](StiReport.md)>

---

**SaveEncryptedReportAsync**(**path**: string, **key**: string): Task<[StiReport](StiReport.md)>

Saves asynchronously an encrypted report template in the file.

**Parameters**

- **path** (string) — A file to save an encrypted report template.  
- **key** (string)  

**Returns** Task<[StiReport](StiReport.md)>


---

#### SaveEncryptedReportToByteArray

**SaveEncryptedReportToByteArray**(**key**: string): byte[]

Saves an encrypted report template in the byte array.

**Parameters**

- **key** (string)  

**Returns** byte[] — A new byte array containing the encrypted report template.


---

#### SaveEncryptedReportToByteArrayAsync

**SaveEncryptedReportToByteArrayAsync**(**key**: string): Task<byte[]>

Saves asynchronously an encrypted report template in the byte array.

**Parameters**

- **key** (string)  

**Returns** Task<byte[]> — A new byte array containing the encrypted report template.


---

#### SaveEncryptedReportToString

**SaveEncryptedReportToString**(**key**: string): string

Saves an encrypted report template to the string.

**Parameters**

- **key** (string)  

**Returns** string — A string which contains an encrypted report template.


---

#### SaveEncryptedReportToStringAsync

**SaveEncryptedReportToStringAsync**(**key**: string): Task<string>

Saves asynchronously an encrypted report template to the string.

**Parameters**

- **key** (string)  

**Returns** Task<string> — A string which contains an encrypted report template.


---

#### SavePackedDocument

**SavePackedDocument**(**stream**: Stream): [StiReport](StiReport.md)

Saves a packed rendered report to the stream.

**Parameters**

- **stream** (Stream) — A stream to save a packed rendered report.  

**Returns** [StiReport](StiReport.md)

---

**SavePackedDocument**(**path**: string): [StiReport](StiReport.md)

Saves a packed rendered report in the file.

**Parameters**

- **path** (string) — A file for saving a packed rendered report.  

**Returns** [StiReport](StiReport.md)


---

#### SavePackedDocumentAsync

**SavePackedDocumentAsync**(**stream**: Stream): Task<[StiReport](StiReport.md)>

Saves asynchronously a packed rendered report to the stream.

**Parameters**

- **stream** (Stream) — A stream to save a packed rendered report.  

**Returns** Task<[StiReport](StiReport.md)>

---

**SavePackedDocumentAsync**(**path**: string): Task<[StiReport](StiReport.md)>

Saves asynchronously a packed rendered report in the file.

**Parameters**

- **path** (string) — A file for saving a packed rendered report.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### SavePackedDocumentToByteArray

**SavePackedDocumentToByteArray**(): byte[]

Saves a packed rendered report to the byte array.

**Returns** byte[] — A byte array which contains a packed rendered report.


---

#### SavePackedDocumentToByteArrayAsync

**SavePackedDocumentToByteArrayAsync**(): Task<byte[]>

Saves asynchronously a packed rendered report to the byte array.

**Returns** Task<byte[]> — A byte array which contains a packed rendered report.


---

#### SavePackedDocumentToString

**SavePackedDocumentToString**(): string

Saves a packed rendered report to the string.

**Returns** string — A string which contains a packed rendered report.


---

#### SavePackedDocumentToStringAsync

**SavePackedDocumentToStringAsync**(): Task<string>

Saves asynchronously a packed rendered report to the string.

**Returns** Task<string> — A string which contains a packed rendered report.


---

#### SavePackedReport

**SavePackedReport**(**stream**: Stream): [StiReport](StiReport.md)

Saves a packed report template in the stream.

**Parameters**

- **stream** (Stream) — A stream to save a packed report template.  

**Returns** [StiReport](StiReport.md)

---

**SavePackedReport**(**path**: string): [StiReport](StiReport.md)

Saves a packed report template in the file.

**Parameters**

- **path** (string) — A file to save a packed report template.  

**Returns** [StiReport](StiReport.md)


---

#### SavePackedReportAsync

**SavePackedReportAsync**(**stream**: Stream): Task<[StiReport](StiReport.md)>

Saves asynchronously a packed report template in the stream.

**Parameters**

- **stream** (Stream) — A stream to save a packed report template.  

**Returns** Task<[StiReport](StiReport.md)>

---

**SavePackedReportAsync**(**path**: string): Task<[StiReport](StiReport.md)>

Saves asynchronously a packed report template in the file.

**Parameters**

- **path** (string) — A file to save a packed report template.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### SavePackedReportToByteArray

**SavePackedReportToByteArray**(): byte[]

Saves a packed report template in the byte array.

**Returns** byte[] — A new byte array containing the packed report template.


---

#### SavePackedReportToByteArrayAsync

**SavePackedReportToByteArrayAsync**(): Task<byte[]>

Saves asynchronously a packed report template in the byte array.

**Returns** Task<byte[]> — A new byte array containing the packed report template.


---

#### SavePackedReportToString

**SavePackedReportToString**(): string

Saves a packed report template to the string.

**Returns** string — A string which contains a packed report template.


---

#### SavePackedReportToStringAsync

**SavePackedReportToStringAsync**(): Task<string>

Saves a packed report template to the string.

**Returns** Task<string> — A string which contains a packed report template.


---

#### SaveReportSourceCode

**SaveReportSourceCode**(): string

Saves the report source code to the string.

**Returns** string

---

**SaveReportSourceCode**(**saveForInheritedReports**: bool): string

Saves the report source code to the string.

**Parameters**

- **saveForInheritedReports** (bool)  

**Returns** string

---

**SaveReportSourceCode**(**stream**: Stream): [StiReport](StiReport.md)

Saves the report source code to the stream.

**Parameters**

- **stream** (Stream) — Stream for saving the source code.  

**Returns** [StiReport](StiReport.md)

---

**SaveReportSourceCode**(**stream**: Stream, **saveForInheritedReports**: bool): [StiReport](StiReport.md)

Saves the report source code to the stream.

**Parameters**

- **stream** (Stream) — Stream for saving the source code.  
- **saveForInheritedReports** (bool)  

**Returns** [StiReport](StiReport.md)

---

**SaveReportSourceCode**(**path**: string): [StiReport](StiReport.md)

Saves the report source code to the file.

**Parameters**

- **path** (string) — Parameter specifies a path to the file the report is exported to.  

**Returns** [StiReport](StiReport.md)

---

**SaveReportSourceCode**(**path**: string, **saveForInheritedReports**: bool): [StiReport](StiReport.md)

Saves the report source code to the file.

**Parameters**

- **path** (string) — Parameter specifies a path to the file the report is exported to.  
- **saveForInheritedReports** (bool)  

**Returns** [StiReport](StiReport.md)


---

#### SaveSnapshot

**SaveSnapshot**(**path**: string): [StiReport](StiReport.md)

Saves a report template with embedded data

**Parameters**

- **path** (string) — A file to save a report template with embedded data.  

**Returns** [StiReport](StiReport.md)

---

**SaveSnapshot**(**stream**: Stream): [StiReport](StiReport.md)

Saves a report template with embedded data to the stream.

**Parameters**

- **stream** (Stream) — A stream to save a report template with embedded data.  

**Returns** [StiReport](StiReport.md)


---

#### SaveSnapshotAsync

**SaveSnapshotAsync**(**path**: string): Task<[StiReport](StiReport.md)>

Saves asynchronously a report template with embedded data.

**Parameters**

- **path** (string) — A file to save a report template with embedded data.  

**Returns** Task<[StiReport](StiReport.md)>

---

**SaveSnapshotAsync**(**stream**: Stream): Task<[StiReport](StiReport.md)>

Saves asynchronously a report template with embedded data to the stream.

**Parameters**

- **stream** (Stream) — A stream to save a report template with embedded data.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### SaveSnapshotToByteArray

**SaveSnapshotToByteArray**(): byte[]

Saves a report template with embedded data to a byte array.

**Returns** byte[] — The new byte array containing a report snapshot.


---

#### SaveSnapshotToByteArrayAsync

**SaveSnapshotToByteArrayAsync**(): Task<byte[]>

Saves asynchronously a report template with embedded data to a byte array.

**Returns** Task<byte[]> — The new byte array containing a report snapshot.


---

#### SaveToByteArray

**SaveToByteArray**(): byte[]

Saves a report template in the byte array.

**Returns** byte[] — A byte array which contains the report template.


---

#### SaveToByteArrayAsync

**SaveToByteArrayAsync**(): Task<byte[]>

Saves asynchronously a report template in the byte array.

**Returns** Task<byte[]> — A byte array which contains the report template.


---

#### SaveToJson

**SaveToJson**(**path**: string): [StiReport](StiReport.md)

Saves a report template in the file.

**Parameters**

- **path** (string) — A file to save a report template.  

**Returns** [StiReport](StiReport.md)


---

#### SaveToJsonAsync

**SaveToJsonAsync**(**path**: string): Task<[StiReport](StiReport.md)>

Saves asynchronously a report template in the file.

**Parameters**

- **path** (string) — A file to save a report template.  

**Returns** Task<[StiReport](StiReport.md)>


---

#### SaveToJsonString

**SaveToJsonString**(): string

Saves a report template to the string.

**Returns** string — A string which contains the report template.


---

#### SaveToJsonStringAsync

**SaveToJsonStringAsync**(): Task<string>

Saves asynchronously a report template to the string.

**Returns** Task<string> — A string which contains the report template.


---

#### SaveToString

**SaveToString**(): string

Saves a report template to the string.

**Returns** string — A string which contains the report template.


---

#### SaveToStringAsync

**SaveToStringAsync**(): Task<string>

Saves asynchronously a report template to the string.

**Returns** Task<string> — A string which contains the report template.


---

#### Show

**Show**(): [StiReport](StiReport.md)

Shows a rendered report. If the report is not rendered then its rendering starts.

**Returns** [StiReport](StiReport.md)

---

**Show**(**dialogForm**: bool): [StiReport](StiReport.md)

Shows the rendered report as a dialog form or not. If the report is not rendered then its rendering starts.

**Parameters**

- **dialogForm** (bool) — If this parameter is true then the report will be rendered as a dialog form.  

**Returns** [StiReport](StiReport.md)

---

**Show**(**parentForm**: Form): [StiReport](StiReport.md)

Shows the rendered report as MDI child window. If the report is not rendered then its rendering starts.

**Parameters**

- **parentForm** (Form) — A parent form in the MDI application.  

**Returns** [StiReport](StiReport.md)

---

**Show**(**owner**: IWin32Window): [StiReport](StiReport.md)

Shows the rendered report as MDI child window. If the report is not rendered then its rendering starts.

**Parameters**

- **owner** (IWin32Window) — Provides an interface to expose parent Win32 HWND handle.  

**Returns** [StiReport](StiReport.md)

---

**Show**(**owner**: IWin32Window, **dialogForm**: bool): [StiReport](StiReport.md)

Shows the rendered report as MDI child window. If the report is not rendered then its rendering starts.

**Parameters**

- **owner** (IWin32Window) — Provides an interface to expose parent Win32 HWND handle.  
- **dialogForm** (bool) — If this parameter is true then the report will be shown as a dialog form.  

**Returns** [StiReport](StiReport.md)


---

#### ShowDotMatrix

**ShowDotMatrix**(): [StiReport](StiReport.md)

Shows a rendered report in DotMatrix mode. If the report is not rendered then its rendering starts.

**Returns** [StiReport](StiReport.md)

---

**ShowDotMatrix**(**dialogForm**: bool): [StiReport](StiReport.md)

Shows the rendered report in DotMatrix mode as a dialog form or not. If the report is not rendered then its rendering starts.

**Parameters**

- **dialogForm** (bool) — If this parameter is true then the report will be rendered as a dialog form.  

**Returns** [StiReport](StiReport.md)

---

**ShowDotMatrix**(**parentForm**: Form): [StiReport](StiReport.md)

Shows the rendered report in DotMatrix mode as MDI child window. If the report is not rendered then its rendering starts.

**Parameters**

- **parentForm** (Form) — A parent form in the MDI application.  

**Returns** [StiReport](StiReport.md)

---

**ShowDotMatrix**(**owner**: IWin32Window): [StiReport](StiReport.md)

Shows the rendered report in DotMatrix mode as MDI child window. If the report is not rendered then its rendering starts.

**Parameters**

- **owner** (IWin32Window) — Provides an interface to expose parent Win32 HWND handle.  

**Returns** [StiReport](StiReport.md)

---

**ShowDotMatrix**(**owner**: IWin32Window, **dialogForm**: bool): [StiReport](StiReport.md)

Shows the rendered report in DotMatrix mode as MDI child window. If the report is not rendered then its rendering starts.

**Parameters**

- **owner** (IWin32Window) — Provides an interface to expose parent Win32 HWND handle.  
- **dialogForm** (bool) — If this parameter is true then the report will be shown as a dialog form.  

**Returns** [StiReport](StiReport.md)


---

#### ShowDotMatrixWithRibbonGUI

**ShowDotMatrixWithRibbonGUI**(): [StiReport](StiReport.md)

**Returns** [StiReport](StiReport.md)

---

**ShowDotMatrixWithRibbonGUI**(**dialogForm**: bool): [StiReport](StiReport.md)

**Parameters**

- **dialogForm** (bool)  

**Returns** [StiReport](StiReport.md)

---

**ShowDotMatrixWithRibbonGUI**(**parentForm**: Form): [StiReport](StiReport.md)

**Parameters**

- **parentForm** (Form)  

**Returns** [StiReport](StiReport.md)

---

**ShowDotMatrixWithRibbonGUI**(**owner**: IWin32Window): [StiReport](StiReport.md)

**Parameters**

- **owner** (IWin32Window)  

**Returns** [StiReport](StiReport.md)

---

**ShowDotMatrixWithRibbonGUI**(**owner**: IWin32Window, **dialogForm**: bool): [StiReport](StiReport.md)

**Parameters**

- **owner** (IWin32Window)  
- **dialogForm** (bool)  

**Returns** [StiReport](StiReport.md)


---

#### ShowDotMatrixWithWpf

**ShowDotMatrixWithWpf**(): [StiReport](StiReport.md)

Shows a rendered report in DotMatrix mode with using WPF technology. If the report is not rendered then its rendering starts.

**Returns** [StiReport](StiReport.md)

---

**ShowDotMatrixWithWpf**(**dialogWindow**: bool): [StiReport](StiReport.md)

Shows the rendered report in DotMatrix mode as a dialog form or not with using WPF technology. If the report is not rendered then its rendering starts.

**Parameters**

- **dialogWindow** (bool) — If this parameter is true then the report will be rendered as a dialog window.  

**Returns** [StiReport](StiReport.md)


---

#### ShowWithRibbonGUI

**ShowWithRibbonGUI**(): [StiReport](StiReport.md)

Shows a rendered report in viewer with Ribbon GUI. If the report is not rendered then its rendering starts.

**Returns** [StiReport](StiReport.md)

---

**ShowWithRibbonGUI**(**dialogForm**: bool): [StiReport](StiReport.md)

Shows the rendered report as a dialog form or not with Ribbon GUI. If the report is not rendered then its rendering starts.

**Parameters**

- **dialogForm** (bool) — If this parameter is true then the report will be rendered as a dialog form.  

**Returns** [StiReport](StiReport.md)

---

**ShowWithRibbonGUI**(**parentForm**: Form): [StiReport](StiReport.md)

Shows the rendered report as MDI child window with Ribbon GUI. If the report is not rendered then its rendering starts.

**Parameters**

- **parentForm** (Form) — A parent form in the MDI application.  

**Returns** [StiReport](StiReport.md)

---

**ShowWithRibbonGUI**(**owner**: IWin32Window): [StiReport](StiReport.md)

Shows the rendered report as MDI child window with Ribbon GUI. If the report is not rendered then its rendering starts.

**Parameters**

- **owner** (IWin32Window) — Provides an interface to expose parent Win32 HWND handle.  

**Returns** [StiReport](StiReport.md)

---

**ShowWithRibbonGUI**(**owner**: IWin32Window, **dialogForm**: bool): [StiReport](StiReport.md)

Shows the rendered report as MDI child window with Ribbon GUI. If the report is not rendered then its rendering starts.

**Parameters**

- **owner** (IWin32Window) — Provides an interface to expose parent Win32 HWND handle.  
- **dialogForm** (bool) — If this parameter is true then the report will be shown as a dialog form.  

**Returns** [StiReport](StiReport.md)


---

#### ShowWithWpf

**ShowWithWpf**(): [StiReport](StiReport.md)

Shows the rendered report with using WPF technology. If the report is not rendered then its rendering starts.

**Returns** [StiReport](StiReport.md)

---

**ShowWithWpf**(**dialogWindow**: bool): [StiReport](StiReport.md)

Shows the rendered report with using WPF technology. If the report is not rendered then its rendering starts.

**Parameters**

- **dialogWindow** (bool) — If this parameter is true then the report will be shown as a dialog window.  

**Returns** [StiReport](StiReport.md)

---

**ShowWithWpf**(**ownerWindow**: object): [StiReport](StiReport.md)

Shows the rendered report with using WPF technology. If the report is not rendered then its rendering starts.

**Parameters**

- **ownerWindow** (object) — A parent form.  

**Returns** [StiReport](StiReport.md)

---

**ShowWithWpf**(**ownerWindow**: object, **dialogWindow**: bool): [StiReport](StiReport.md)

Shows the rendered report with using WPF technology. If the report is not rendered then its rendering starts.

**Parameters**

- **ownerWindow** (object) — A parent form.  
- **dialogWindow** (bool) — If this parameter is true then the report will be shown as a dialog window.  

**Returns** [StiReport](StiReport.md)


---

#### ShowWithWpfRibbonGUI

**ShowWithWpfRibbonGUI**(): [StiReport](StiReport.md)

Shows the rendered report with using WPF Ribbon GUI technology. If the report is not rendered then its rendering starts.

**Returns** [StiReport](StiReport.md)

---

**ShowWithWpfRibbonGUI**(**dialogWindow**: bool): [StiReport](StiReport.md)

Shows the rendered report with using WPF Ribbon GUI technology. If the report is not rendered then its rendering starts.

**Parameters**

- **dialogWindow** (bool) — If this parameter is true then the report will be shown as a dialog window.  

**Returns** [StiReport](StiReport.md)

---

**ShowWithWpfRibbonGUI**(**ownerWindow**: object): [StiReport](StiReport.md)

Shows the rendered report with using WPF Ribbon GUI technology. If the report is not rendered then its rendering starts.

**Parameters**

- **ownerWindow** (object) — A parent form.  

**Returns** [StiReport](StiReport.md)

---

**ShowWithWpfRibbonGUI**(**ownerWindow**: object, **dialogWindow**: bool): [StiReport](StiReport.md)

Shows the rendered report with using WPF Ribbon GUI technology. If the report is not rendered then its rendering starts.

**Parameters**

- **ownerWindow** (object) — A parent form.  
- **dialogWindow** (bool) — If this parameter is true then the report will be shown as a dialog window.  

**Returns** [StiReport](StiReport.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Date** | DateTime |  |
| **Date** | DateTime |  |
| **GlobalizationStrings** | StiGlobalizationContainerCollection |  |
| **IsFirstPage** | bool |  |
| **IsFirstPageThrough** | bool |  |
| **IsFirstPass** | bool |  |
| **IsLastPage** | bool |  |
| **IsLastPageThrough** | bool |  |
| **IsSecondPass** | bool |  |
| **LineABC** | string |  |
| **LineRoman** | string |  |
| **PageNofM** | string |  |
| **Time** | DateTime |  |
| **Time** | DateTime |  |
| **Today** | DateTime |  |
| **Today** | DateTime |  |
