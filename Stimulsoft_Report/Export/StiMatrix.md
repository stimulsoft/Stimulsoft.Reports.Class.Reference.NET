---
title: "StiMatrix Class"
---

## StiMatrix Class

**Namespace:** `Stimulsoft.Report.Export`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMatrix**([StiPagesCollection](../Components/StiPagesCollection.md) pages, [StiExportService](StiExportService.md) service) |  |
| **StiMatrix**([StiPagesCollection](../Components/StiPagesCollection.md) pages, bool checkForExcel, [StiExportService](StiExportService.md) service) |  |
| **StiMatrix**([StiPagesCollection](../Components/StiPagesCollection.md) pages, [StiExportService](StiExportService.md) service, ArrayList styles) |  |
| **StiMatrix**([StiPagesCollection](../Components/StiPagesCollection.md) pages, bool checkForExcel, [StiExportService](StiExportService.md) service, ArrayList styles, [StiDataExportMode](StiDataExportMode.md) dataMode, bool hasDividedPages) |  |

**StiMatrix**(**pages**: [StiPagesCollection](../Components/StiPagesCollection.md), **service**: [StiExportService](StiExportService.md))

**Parameters**

- **pages** ([StiPagesCollection](../Components/StiPagesCollection.md))  
- **service** ([StiExportService](StiExportService.md))  

---

**StiMatrix**(**pages**: [StiPagesCollection](../Components/StiPagesCollection.md), **checkForExcel**: bool, **service**: [StiExportService](StiExportService.md))

**Parameters**

- **pages** ([StiPagesCollection](../Components/StiPagesCollection.md))  
- **checkForExcel** (bool)  
- **service** ([StiExportService](StiExportService.md))  

---

**StiMatrix**(**pages**: [StiPagesCollection](../Components/StiPagesCollection.md), **service**: [StiExportService](StiExportService.md), **styles**: ArrayList)

**Parameters**

- **pages** ([StiPagesCollection](../Components/StiPagesCollection.md))  
- **service** ([StiExportService](StiExportService.md))  
- **styles** (ArrayList)  

---

**StiMatrix**(**pages**: [StiPagesCollection](../Components/StiPagesCollection.md), **checkForExcel**: bool, **service**: [StiExportService](StiExportService.md), **styles**: ArrayList, **dataMode**: [StiDataExportMode](StiDataExportMode.md), **hasDividedPages**: bool)

**Parameters**

- **pages** ([StiPagesCollection](../Components/StiPagesCollection.md))  
- **checkForExcel** (bool)  
- **service** ([StiExportService](StiExportService.md))  
- **styles** (ArrayList)  
- **dataMode** ([StiDataExportMode](StiDataExportMode.md))  
- **hasDividedPages** (bool)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CoordX** | SortedList |  |
| **CoordY** | SortedList |  |
| **HorizontalPageBreaks** | List<int> |  |
| **LinePlacement** | StiTableLineInfo[] |  |
| **ParentBandName** | string[] |  |
| **Styles** | ArrayList |  |
| **TotalWidth** | double |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CheckStylesNames** | void |  |
| **Clear** | void |  |
| **GetBorderSideIndex** | int |  |
| **GetCellComponent** | StiComponent |  |
| **GetRange** | Rectangle |  |
| **GetRealImageData** | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **GetStringsFromTag** `static` | string[] |  |
| **GetStyleFromComponent** | [StiCellStyle](StiCellStyle.md) |  |
| **PrepareDocument** | void |  |
| **PrepareTable** | void |  |
| **SetCellComponent** | void |  |
| **SplitTag** `static` | string[] |  |
| **SplitTagWithCache** | string[] |  |

---

### Method Details

#### CheckStylesNames

**CheckStylesNames**(): void


---

#### Clear

**Clear**(): void


---

#### GetBorderSideIndex

**GetBorderSideIndex**(**side**: [StiBorderSide](../../Stimulsoft_Base/Drawing/StiBorderSide.md)): int

**Parameters**

- **side** ([StiBorderSide](../../Stimulsoft_Base/Drawing/StiBorderSide.md))  

**Returns** int


---

#### GetCellComponent

**GetCellComponent**(**cell2**: [StiCell](StiCell.md)): StiComponent

**Parameters**

- **cell2** ([StiCell](StiCell.md))  

**Returns** StiComponent


---

#### GetRange

**GetRange**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): Rectangle

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  

**Returns** Rectangle


---

#### GetRealImageData

**GetRealImageData**(**cell**: [StiCell](StiCell.md), **baseImage**: [Image](../../Stimulsoft_Drawing/root/Image.md), **list**: ArrayList): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **cell** ([StiCell](StiCell.md))  
- **baseImage** ([Image](../../Stimulsoft_Drawing/root/Image.md))  
- **list** (ArrayList)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)


---

#### GetStringsFromTag `static`

**GetStringsFromTag**(**tag**: string, **startPosition**: int): string[]

**Parameters**

- **tag** (string)  
- **startPosition** (int)  

**Returns** string[]


---

#### GetStyleFromComponent

**GetStyleFromComponent**(**component**: StiComponent, **x**: int, **y**: int, **width**: int): [StiCellStyle](StiCellStyle.md)

**Parameters**

- **component** (StiComponent)  
- **x** (int)  
- **y** (int)  
- **width** (int)  

**Returns** [StiCellStyle](StiCellStyle.md)


---

#### PrepareDocument

**PrepareDocument**(**service**: [StiExportService](StiExportService.md), **mode**: [StiDataExportMode](StiDataExportMode.md)): void

**Parameters**

- **service** ([StiExportService](StiExportService.md))  
- **mode** ([StiDataExportMode](StiDataExportMode.md))  


---

#### PrepareTable

**PrepareTable**(): void


---

#### SetCellComponent

**SetCellComponent**(**cell2**: [StiCell](StiCell.md), **component**: StiComponent, **indexComponent**: int): void

**Parameters**

- **cell2** ([StiCell](StiCell.md))  
- **component** (StiComponent)  
- **indexComponent** (int)  


---

#### SplitTag `static`

**SplitTag**(**inputString**: string): string[]

**Parameters**

- **inputString** (string)  

**Returns** string[]


---

#### SplitTagWithCache

**SplitTagWithCache**(**inputString**: string): string[]

**Parameters**

- **inputString** (string)  

**Returns** string[]


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Bookmarks** | [StiMatrixBookmarksCollection](StiMatrixBookmarksCollection.md) |  |
| **BordersX** | [StiMatrixBorderSidesXCollection](StiMatrixBorderSidesXCollection.md) |  |
| **BordersY** | [StiMatrixBorderSidesYCollection](StiMatrixBorderSidesYCollection.md) |  |
| **CellStyles** | [StiMatrixCellStylesCollection](StiMatrixCellStylesCollection.md) |  |
| **Cells** | [StiMatrixCellsCollection](StiMatrixCellsCollection.md) |  |
| **DataArrayLength** | int |  |
| **Fields** | DataField[] |  |
| **Primitive** | [StiRoundedRectanglePrimitive](../Components/StiRoundedRectanglePrimitive.md) |  |
| **Rect** | Rectangle |  |
