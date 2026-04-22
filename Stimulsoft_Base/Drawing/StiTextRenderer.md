---
title: "StiTextRenderer Class"
---

## StiTextRenderer Class

**Namespace:** `Stimulsoft.Base.Drawing`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiTextRenderer
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowCheckMissingGlyphs** `static` | bool |  |
| **Compatibility2009** `static` | bool | Enable text scaling mode as in the 2009.1 version. For backward compatibility |
| **CorrectionEnabled** `static` | bool | Enable the inter-character distance correction |
| **InterpreteFontSizeInHtmlTagsAsInHtml** `static` | bool | Interprete the FontSize attribute in the Html-tags as in Html |
| **MaxFontSize** `static` | float |  |
| **OptimizeBottomMargin** `static` | bool | Optimize the bottom margin of the text |
| **PrecisionMode2Enabled** `static` | bool |  |
| **PrecisionMode3Enabled** `static` | bool |  |
| **PrecisionMode4Enabled** `static` | bool |  |
| **PrecisionModeEnabled** `static` | bool |  |
| **PrecisionModeFactor** `static` | double | Obsolete |
| **StiDpiHelperGraphicsScale** `static` | double |  |
| **StiForceWidthAlignTag** `static` | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CheckTextForHtmlTags** `static` | bool |  |
| **Create** `static` | DRAWTEXTPARAMS |  |
| **FromXYWH** `static` | RECT |  |
| **GetFontGlyphs** `static` | object |  |
| **GetOffsetFromStiHtml2** `static` | int |  |
| **GetPlainTextFromHtmlTags** `static` | string |  |
| **ParseColor** `static` | Color |  |
| **ParseHtmlToStates** `static` | List<StiHtmlState> |  |
| **PrepareStateText** `static` | StringBuilder |  |
| **StateToHtml** `static` | string |  |
| **ToABC** `static` | string |  |
| **ToRectangle** | Rectangle |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **ArmStyle** | byte |  |
| **BackColor** | Color |  |
| **Bounds** | [RectangleD](RectangleD.md) |  |
| **ClipBounds** | RectangleF |  |
| **DefaultParagraphLineHeight** | double |  |
| **DpiX** | float |  |
| **DpiY** | float |  |
| **FontList** | StiFontState[] |  |
| **ForeColor** | Color |  |
| **Graphics2** | [Graphics](../../Stimulsoft_Drawing/Graphics.md) |  |
| **Hdc** | IntPtr |  |
| **NewRegion** | IntPtr |  |
| **OldGraphMode** | int |  |
| **OldMapMode** | int |  |
| **OldRegion** | IntPtr |  |
| **OldXForm** | XFORM |  |
| **PageUnit** | GraphicsUnit |  |
| **RegionRect** | [RectangleD](RectangleD.md) |  |
| **ResultGetClip** | int |  |
| **TextRect** | [RectangleD](RectangleD.md) |  |
| **TextSize** | [SizeD](SizeD.md) |  |
| **bContrast** | byte |  |
| **bFamilyType** | byte |  |
| **bLetterform** | byte |  |
| **bMidline** | byte |  |
| **bProportion** | byte |  |
| **bSerifStyle** | byte |  |
| **bStrokeVariation** | byte |  |
| **bWeight** | byte |  |
| **bXHeight** | byte |  |
| **bottom** | int |  |
| **cx** | int |  |
| **cy** | int |  |
| **du** | Int32 |  |
| **dv** | Int32 |  |
| **eDx** | float |  |
| **eDy** | float |  |
| **eM11** | float |  |
| **eM12** | float |  |
| **eM21** | float |  |
| **eM22** | float |  |
| **iLeftMargin** | int |  |
| **iRightMargin** | int |  |
| **iTabLength** | int |  |
| **left** | int |  |
| **otmAscent** | int |  |
| **otmDescent** | int |  |
| **otmEMSquare** | uint |  |
| **otmFiller** | byte |  |
| **otmItalicAngle** | int |  |
| **otmLineGap** | uint |  |
| **otmMacAscent** | int |  |
| **otmMacDescent** | int |  |
| **otmMacLineGap** | uint |  |
| **otmPanoseNumber** | PANOSE |  |
| **otmSize** | uint |  |
| **otmTextMetrics** | TEXTMETRIC |  |
| **otmfsSelection** | uint |  |
| **otmfsType** | uint |  |
| **otmpFaceName** | uint |  |
| **otmpFamilyName** | uint |  |
| **otmpFullName** | uint |  |
| **otmpStyleName** | uint |  |
| **otmptSubscriptOffset** | POINT |  |
| **otmptSubscriptSize** | POINT |  |
| **otmptSuperscriptOffset** | POINT |  |
| **otmptSuperscriptSize** | POINT |  |
| **otmrcFontBox** | RECT |  |
| **otmsCapEmHeight** | uint |  |
| **otmsCharSlopeRise** | int |  |
| **otmsCharSlopeRun** | int |  |
| **otmsStrikeoutPosition** | int |  |
| **otmsStrikeoutSize** | uint |  |
| **otmsUnderscorePosition** | int |  |
| **otmsUnderscoreSize** | int |  |
| **otmsXHeight** | uint |  |
| **otmusMinimumPPEM** | uint |  |
| **right** | int |  |
| **s** | SCRIPT_STATE |  |
| **tmAscent** | int |  |
| **tmAveCharWidth** | int |  |
| **tmBreakChar** | char |  |
| **tmCharSet** | byte |  |
| **tmDefaultChar** | char |  |
| **tmDescent** | int |  |
| **tmDigitizedAspectX** | int |  |
| **tmDigitizedAspectY** | int |  |
| **tmExternalLeading** | int |  |
| **tmFirstChar** | char |  |
| **tmHeight** | int |  |
| **tmInternalLeading** | int |  |
| **tmItalic** | byte |  |
| **tmLastChar** | char |  |
| **tmMaxCharWidth** | int |  |
| **tmOverhang** | int |  |
| **tmPitchAndFamily** | byte |  |
| **tmStruckOut** | byte |  |
| **tmUnderlined** | byte |  |
| **tmWeight** | int |  |
| **top** | int |  |
| **uiLengthDrawn** | uint |  |
| **x** | int |  |
| **y** | int |  |
