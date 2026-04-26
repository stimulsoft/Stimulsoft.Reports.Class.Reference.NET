---
title: "StiDashboardStyleHelper Class"
---

## StiDashboardStyleHelper Class

**Namespace:** `Stimulsoft.Report.Dashboard.Styles`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConvertToReportCardsStyle** `static` | StiCardsStyle |  |
| **ConvertToReportControlStyle** `static` | StiDialogStyle |  |
| **ConvertToReportGaugeStyle** `static` | StiGaugeStyle |  |
| **ConvertToReportIndicatorStyle** `static` | StiIndicatorStyle |  |
| **ConvertToReportPivotTableStyle** `static` | StiCrossTabStyle |  |
| **ConvertToReportProgressStyle** `static` | StiProgressStyle |  |
| **ConvertToReportRegionMapStyle** `static` | StiMapStyle |  |
| **GetBackColor** `static` *(+1 overloads)* | Color |  |
| **GetCardsStyle** `static` *(+1 overloads)* | StiCardsElementStyle |  |
| **GetChartStyle** `static` *(+1 overloads)* | IStiChartStyle |  |
| **GetControlStyle** `static` | [StiControlElementStyle](StiControlElementStyle.md) |  |
| **GetCopyChartStyle** `static` | StiChartStyle |  |
| **GetCopyTableStyle** `static` *(+1 overloads)* | [StiTableStyle](../../Components/Table/StiTableStyle.md) |  |
| **GetDashboardBackColor** `static` | Color |  |
| **GetDataEmptyColor** `static` | Color |  |
| **GetDataEmptyForeColor** `static` | Color |  |
| **GetDialogBackColor** `static` | Color |  |
| **GetDialogGlyphColor** `static` | Color |  |
| **GetDialogHotSelectedBackColor** `static` | Color |  |
| **GetDialogHotSelectedForeColor** `static` | Color |  |
| **GetDialogSelectedBackColor** `static` | Color |  |
| **GetDialogSelectedForeColor** `static` | Color |  |
| **GetDialogSeparatorColor** `static` | Color |  |
| **GetDialogStyle** `static` | StiDialogStyle |  |
| **GetElementTitleStyle** `static` | [IStiTitleStyle](../../Styles/IStiTitleStyle.md) |  |
| **GetFont** `static` | [Font](../../../Stimulsoft_Drawing/root/Font.md) |  |
| **GetForeColor** `static` *(+1 overloads)* | Color |  |
| **GetGaugeStyle** `static` *(+1 overloads)* | StiGaugeStyleXF |  |
| **GetGlyphColor** `static` | Color |  |
| **GetHotBackColor** `static` | Color |  |
| **GetIndicatorStyle** `static` | [StiIndicatorElementStyle](StiIndicatorElementStyle.md) |  |
| **GetMapStyle** `static` *(+1 overloads)* | [StiMapStyleFX](../../Maps/StiMapStyleFX.md) |  |
| **GetMapStyleIdent** `static` | [StiMapStyleIdent](../../Maps/StiMapStyleIdent.md) |  |
| **GetNativeForeColor** `static` | Color |  |
| **GetPivotTableStyle** `static` | [StiPivotElementStyle](StiPivotElementStyle.md) |  |
| **GetProgressStyle** `static` | [StiProgressElementStyle](StiProgressElementStyle.md) |  |
| **GetStyle** `static` | [StiElementStyleIdent](../StiElementStyleIdent.md) |  |
| **GetStyleForDataViewTable** `static` | StiTableElementStyle | Resulting style may be incomplete, as it contains only colors that are needed to paint a specific type of table. |
| **GetTableStyle** `static` *(+2 overloads)* | StiTableElementStyle |  |
| **GetTitleForeColor** `static` | Color |  |
| **IsDarkStyle** `static` *(+3 overloads)* | bool |  |

---

### Method Details

#### ConvertToReportCardsStyle `static`

**ConvertToReportCardsStyle**(**element**: IStiCardsElement): StiCardsStyle

**Parameters**

- **element** (IStiCardsElement)  

**Returns** StiCardsStyle


---

#### ConvertToReportControlStyle `static`

**ConvertToReportControlStyle**(**element**: IStiControlElement): StiDialogStyle

**Parameters**

- **element** (IStiControlElement)  

**Returns** StiDialogStyle


---

#### ConvertToReportGaugeStyle `static`

**ConvertToReportGaugeStyle**(**element**: IStiGaugeElement): StiGaugeStyle

**Parameters**

- **element** (IStiGaugeElement)  

**Returns** StiGaugeStyle


---

#### ConvertToReportIndicatorStyle `static`

**ConvertToReportIndicatorStyle**(**element**: IStiIndicatorElement): StiIndicatorStyle

**Parameters**

- **element** (IStiIndicatorElement)  

**Returns** StiIndicatorStyle


---

#### ConvertToReportPivotTableStyle `static`

**ConvertToReportPivotTableStyle**(**element**: IStiPivotTableElement): StiCrossTabStyle

**Parameters**

- **element** (IStiPivotTableElement)  

**Returns** StiCrossTabStyle


---

#### ConvertToReportProgressStyle `static`

**ConvertToReportProgressStyle**(**element**: IStiProgressElement): StiProgressStyle

**Parameters**

- **element** (IStiProgressElement)  

**Returns** StiProgressStyle


---

#### ConvertToReportRegionMapStyle `static`

**ConvertToReportRegionMapStyle**(**element**: IStiRegionMapElement): StiMapStyle

**Parameters**

- **element** (IStiRegionMapElement)  

**Returns** StiMapStyle


---

#### GetBackColor `static`

**GetBackColor**(**element**: object, **defaultColor**: Color?, **allowOpacity**: bool): Color

**Parameters**

- **element** (object)  
- **defaultColor** (Color?)  
- **allowOpacity** (bool)  

**Returns** Color

---

**GetBackColor**(**style**: [StiElementStyleIdent](../StiElementStyleIdent.md)): Color

**Parameters**

- **style** ([StiElementStyleIdent](../StiElementStyleIdent.md))  

**Returns** Color


---

#### GetCardsStyle `static`

**GetCardsStyle**(**element**: IStiCardsElement): StiCardsElementStyle

**Parameters**

- **element** (IStiCardsElement)  

**Returns** StiCardsElementStyle

---

**GetCardsStyle**(**style**: [StiElementStyleIdent](../StiElementStyleIdent.md)): StiCardsElementStyle

**Parameters**

- **style** ([StiElementStyleIdent](../StiElementStyleIdent.md))  

**Returns** StiCardsElementStyle


---

#### GetChartStyle `static`

**GetChartStyle**(**element**: IStiChartElement): IStiChartStyle

**Parameters**

- **element** (IStiChartElement)  

**Returns** IStiChartStyle

---

**GetChartStyle**(**style**: [StiElementStyleIdent](../StiElementStyleIdent.md)): IStiChartStyle

**Parameters**

- **style** ([StiElementStyleIdent](../StiElementStyleIdent.md))  

**Returns** IStiChartStyle


---

#### GetControlStyle `static`

**GetControlStyle**(**element**: object): [StiControlElementStyle](StiControlElementStyle.md)

**Parameters**

- **element** (object)  

**Returns** [StiControlElementStyle](StiControlElementStyle.md)


---

#### GetCopyChartStyle `static`

**GetCopyChartStyle**(**chartStyle**: IStiChartStyle, **element**: IStiChartElement): StiChartStyle

**Parameters**

- **chartStyle** (IStiChartStyle)  
- **element** (IStiChartElement)  

**Returns** StiChartStyle


---

#### GetCopyTableStyle `static`

**GetCopyTableStyle**(**element**: IStiTableElement, **tableStyle**: StiTableElementStyle): [StiTableStyle](../../Components/Table/StiTableStyle.md)

**Parameters**

- **element** (IStiTableElement)  
- **tableStyle** (StiTableElementStyle)  

**Returns** [StiTableStyle](../../Components/Table/StiTableStyle.md)

---

**GetCopyTableStyle**(**element**: IStiGridUI, **tableStyle**: StiTableElementStyle): [StiTableStyle](../../Components/Table/StiTableStyle.md)

**Parameters**

- **element** (IStiGridUI)  
- **tableStyle** (StiTableElementStyle)  

**Returns** [StiTableStyle](../../Components/Table/StiTableStyle.md)


---

#### GetDashboardBackColor `static`

**GetDashboardBackColor**(**surface**: [IStiSurface](../../Surface/IStiSurface.md), **isViewer**: bool): Color

**Parameters**

- **surface** ([IStiSurface](../../Surface/IStiSurface.md))  
- **isViewer** (bool)  

**Returns** Color


---

#### GetDataEmptyColor `static`

**GetDataEmptyColor**(**element**: IStiElement): Color

**Parameters**

- **element** (IStiElement)  

**Returns** Color


---

#### GetDataEmptyForeColor `static`

**GetDataEmptyForeColor**(**element**: IStiElement): Color

**Parameters**

- **element** (IStiElement)  

**Returns** Color


---

#### GetDialogBackColor `static`

**GetDialogBackColor**(**element**: object): Color

**Parameters**

- **element** (object)  

**Returns** Color


---

#### GetDialogGlyphColor `static`

**GetDialogGlyphColor**(**element**: object): Color

**Parameters**

- **element** (object)  

**Returns** Color


---

#### GetDialogHotSelectedBackColor `static`

**GetDialogHotSelectedBackColor**(**element**: object): Color

**Parameters**

- **element** (object)  

**Returns** Color


---

#### GetDialogHotSelectedForeColor `static`

**GetDialogHotSelectedForeColor**(**element**: object): Color

**Parameters**

- **element** (object)  

**Returns** Color


---

#### GetDialogSelectedBackColor `static`

**GetDialogSelectedBackColor**(**element**: object): Color

**Parameters**

- **element** (object)  

**Returns** Color


---

#### GetDialogSelectedForeColor `static`

**GetDialogSelectedForeColor**(**element**: object): Color

**Parameters**

- **element** (object)  

**Returns** Color


---

#### GetDialogSeparatorColor `static`

**GetDialogSeparatorColor**(**element**: object): Color

**Parameters**

- **element** (object)  

**Returns** Color


---

#### GetDialogStyle `static`

**GetDialogStyle**(**element**: object): StiDialogStyle

**Parameters**

- **element** (object)  

**Returns** StiDialogStyle


---

#### GetElementTitleStyle `static`

**GetElementTitleStyle**(**element**: IStiElement): [IStiTitleStyle](../../Styles/IStiTitleStyle.md)

**Parameters**

- **element** (IStiElement)  

**Returns** [IStiTitleStyle](../../Styles/IStiTitleStyle.md)


---

#### GetFont `static`

**GetFont**(**element**: object): [Font](../../../Stimulsoft_Drawing/root/Font.md)

**Parameters**

- **element** (object)  

**Returns** [Font](../../../Stimulsoft_Drawing/root/Font.md)


---

#### GetForeColor `static`

**GetForeColor**(**element**: object, **defaultColor**: Color?, **isEnabled**: bool, **checkExpression**: bool): Color

**Parameters**

- **element** (object)  
- **defaultColor** (Color?)  
- **isEnabled** (bool)  
- **checkExpression** (bool)  

**Returns** Color

---

**GetForeColor**(**ident**: [StiElementStyleIdent](../StiElementStyleIdent.md)): Color

**Parameters**

- **ident** ([StiElementStyleIdent](../StiElementStyleIdent.md))  

**Returns** Color


---

#### GetGaugeStyle `static`

**GetGaugeStyle**(**element**: IStiGaugeElement): StiGaugeStyleXF

**Parameters**

- **element** (IStiGaugeElement)  

**Returns** StiGaugeStyleXF

---

**GetGaugeStyle**(**style**: [StiElementStyleIdent](../StiElementStyleIdent.md)): StiGaugeStyleXF

**Parameters**

- **style** ([StiElementStyleIdent](../StiElementStyleIdent.md))  

**Returns** StiGaugeStyleXF


---

#### GetGlyphColor `static`

**GetGlyphColor**(**element**: IStiIndicatorElement): Color

**Parameters**

- **element** (IStiIndicatorElement)  

**Returns** Color


---

#### GetHotBackColor `static`

**GetHotBackColor**(**element**: IStiElement): Color

**Parameters**

- **element** (IStiElement)  

**Returns** Color


---

#### GetIndicatorStyle `static`

**GetIndicatorStyle**(**element**: IStiIndicatorElement): [StiIndicatorElementStyle](StiIndicatorElementStyle.md)

**Parameters**

- **element** (IStiIndicatorElement)  

**Returns** [StiIndicatorElementStyle](StiIndicatorElementStyle.md)


---

#### GetMapStyle `static`

**GetMapStyle**(**element**: IStiRegionMapElement): [StiMapStyleFX](../../Maps/StiMapStyleFX.md)

**Parameters**

- **element** (IStiRegionMapElement)  

**Returns** [StiMapStyleFX](../../Maps/StiMapStyleFX.md)

---

**GetMapStyle**(**style**: [StiElementStyleIdent](../StiElementStyleIdent.md)): [StiMapStyleFX](../../Maps/StiMapStyleFX.md)

**Parameters**

- **style** ([StiElementStyleIdent](../StiElementStyleIdent.md))  

**Returns** [StiMapStyleFX](../../Maps/StiMapStyleFX.md)


---

#### GetMapStyleIdent `static`

**GetMapStyleIdent**(**element**: IStiRegionMapElement): [StiMapStyleIdent](../../Maps/StiMapStyleIdent.md)

**Parameters**

- **element** (IStiRegionMapElement)  

**Returns** [StiMapStyleIdent](../../Maps/StiMapStyleIdent.md)


---

#### GetNativeForeColor `static`

**GetNativeForeColor**(**element**: object): Color

**Parameters**

- **element** (object)  

**Returns** Color


---

#### GetPivotTableStyle `static`

**GetPivotTableStyle**(**element**: IStiPivotTableElement): [StiPivotElementStyle](StiPivotElementStyle.md)

**Parameters**

- **element** (IStiPivotTableElement)  

**Returns** [StiPivotElementStyle](StiPivotElementStyle.md)


---

#### GetProgressStyle `static`

**GetProgressStyle**(**element**: IStiProgressElement): [StiProgressElementStyle](StiProgressElementStyle.md)

**Parameters**

- **element** (IStiProgressElement)  

**Returns** [StiProgressElementStyle](StiProgressElementStyle.md)


---

#### GetStyle `static`

**GetStyle**(**element**: object): [StiElementStyleIdent](../StiElementStyleIdent.md)

**Parameters**

- **element** (object)  

**Returns** [StiElementStyleIdent](../StiElementStyleIdent.md)


---

#### GetStyleForDataViewTable `static`

**GetStyleForDataViewTable**(**element**: IStiElement): StiTableElementStyle

Resulting style may be incomplete, as it contains only colors that are needed to paint a specific type of table.

**Parameters**

- **element** (IStiElement)  

**Returns** StiTableElementStyle


---

#### GetTableStyle `static`

**GetTableStyle**(**element**: IStiGridUI): StiTableElementStyle

**Parameters**

- **element** (IStiGridUI)  

**Returns** StiTableElementStyle

---

**GetTableStyle**(**element**: IStiTableElement): StiTableElementStyle

**Parameters**

- **element** (IStiTableElement)  

**Returns** StiTableElementStyle

---

**GetTableStyle**(**style**: [StiElementStyleIdent](../StiElementStyleIdent.md)): StiTableElementStyle

**Parameters**

- **style** ([StiElementStyleIdent](../StiElementStyleIdent.md))  

**Returns** StiTableElementStyle


---

#### GetTitleForeColor `static`

**GetTitleForeColor**(**element**: IStiElement): Color

**Parameters**

- **element** (IStiElement)  

**Returns** Color


---

#### IsDarkStyle `static`

**IsDarkStyle**(**dashboard**: IStiDashboard): bool

**Parameters**

- **dashboard** (IStiDashboard)  

**Returns** bool

---

**IsDarkStyle**(**screen**: IStiScreen): bool

**Parameters**

- **screen** (IStiScreen)  

**Returns** bool

---

**IsDarkStyle**(**element**: IStiElement): bool

**Parameters**

- **element** (IStiElement)  

**Returns** bool

---

**IsDarkStyle**(**ident**: [StiElementStyleIdent](../StiElementStyleIdent.md)): bool

**Parameters**

- **ident** ([StiElementStyleIdent](../StiElementStyleIdent.md))  

**Returns** bool

