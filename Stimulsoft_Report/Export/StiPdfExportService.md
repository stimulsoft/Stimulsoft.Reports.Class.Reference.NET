---
title: "StiPdfExportService Class"
---

## StiPdfExportService Class

**Namespace:** `Stimulsoft.Report.Export`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiPdfExportService
```

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CompatibleMode160** `static` | bool | Compatibility with version 1.60 |
| **Data** | [StiMapData](../Maps/StiMapData.md) |  |
| **Fill** | Color |  |
| **PrintScaling** `static` | bool | PrintScaling property shows, how Acrobat Reader must to use margins of the printer. if true, then default settings of the Acrobat Reader will be used (usually "Fit to printer margin") else PrintScaling parameter of the pdf file will be set to None. |
| **ShadowFill** | Color |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ClearFontsCache** | void |  |
| **Clone** | StiPdfData |  |
| **Export** | void | Exports rendered report to a pdf file. Also file may be sent via e-mail. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **GetCreatorString** | string |  |
| **GetFilter** | string | Returns a filter for the pdf files. |
| **GetHatchNumber** *(+1 overloads)* | int | Returns number of hatch in table of hatches. |
| **GetShadingFunctionNumber** | int | Returns number of shadingFunctionArray in table of shadingFunctions. |
| **InitPdfFonts** | void |  |
| **OnSplitTextIntoLines** | string |  |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **SplitTextIntoLinesEvent** | Events.StiSplitTextIntoLinesEventHandler |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Alignment** | [StiTextHorAlignment](../../Stimulsoft_Base/Drawing/StiTextHorAlignment.md) |  |
| **Angle** | double |  |
| **Colors** | Color[] |  |
| **Component** | StiComponent | Component. |
| **Component** | StiComponent |  |
| **Content** | byte[] |  |
| **Content2** | byte[] |  |
| **Count** | int |  |
| **DestPage** | int |  |
| **DestY** | double |  |
| **First** | int |  |
| **FontAscF** | double |  |
| **FontColor** | Color |  |
| **FontDescF** | double |  |
| **FontLineHeight** | double |  |
| **FontLineHeightWithoutLineSpacing** | double |  |
| **FontNumber** | int |  |
| **FontSize** | double |  |
| **FunctionIndex** | int |  |
| **Guid** | string |  |
| **Height** | double | Height of the border. |
| **Height** | int |  |
| **Height** | double |  |
| **Height** | double |  |
| **Height** | double |  |
| **ImageFormat** | [StiImageFormat](StiImageFormat.md) |  |
| **Last** | int |  |
| **Link** | string |  |
| **Matrix1** | [Matrix](../../Stimulsoft_Drawing/Drawing2D/Matrix.md) |  |
| **Multiline** | bool |  |
| **Name** | string |  |
| **NeedWidthAlign** | bool |  |
| **Next** | int |  |
| **Page** | int |  |
| **Page** | int |  |
| **Page** | int |  |
| **Page** | int |  |
| **Parent** | int |  |
| **Prev** | int |  |
| **SizeInPt** | double |  |
| **Text** | string |  |
| **TextFont** | [IStiFont](../Components/IStiFont.md) |  |
| **TextH** | double |  |
| **TextHorAlign** | [IStiTextHorAlignment](../Components/IStiTextHorAlignment.md) |  |
| **TextLinesList** | List<string> |  |
| **TextOpt** | [IStiTextOptions](../Components/IStiTextOptions.md) |  |
| **TextQualityOffset** | double |  |
| **TextW** | double |  |
| **TextX** | double |  |
| **TextY** | double |  |
| **Title** | string |  |
| **TrimCountLines** | int |  |
| **UseUnicode** | bool |  |
| **UseWysiwyg** | bool |  |
| **Used** | bool |  |
| **Width** | double | Width of the border. |
| **Width** | int |  |
| **Width** | double |  |
| **Width** | double |  |
| **Width** | double |  |
| **X** | double | Coordinate of the border. |
| **X** | double |  |
| **X** | double |  |
| **X** | double |  |
| **Y** | double | Y coordinate of the border. |
| **Y** | double |  |
| **Y** | double |  |
| **Y** | double |  |
| **Y** | double |  |
