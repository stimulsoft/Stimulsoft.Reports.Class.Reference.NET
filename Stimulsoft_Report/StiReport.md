---
title: "StiReport Class"
---

## StiReport Class

**Namespace:** `Stimulsoft.Report`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiReport
```

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
| **ViewerControl** | [IStiViewerControl](Viewer/IStiViewerControl.md) |  |
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
| **Design** *(+3 overloads)* | DialogResult | Calls the designer for the report in the Modal window. |
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
