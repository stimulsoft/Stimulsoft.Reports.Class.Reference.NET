---
title: "JsonExtensions Class"
---

## JsonExtensions Class

**Namespace:** `Stimulsoft.Base.Json.Linq`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddPropertyArrayColor** `static` | void |  |
| **AddPropertyBool** `static` | void |  |
| **AddPropertyBoolArray** `static` | void |  |
| **AddPropertyBorder** `static` *(+1 overloads)* | void |  |
| **AddPropertyBrush** `static` | void |  |
| **AddPropertyByteArray** `static` | void |  |
| **AddPropertyCap** `static` | void |  |
| **AddPropertyColor** `static` *(+1 overloads)* | void |  |
| **AddPropertyCornerRadius** `static` | void |  |
| **AddPropertyDateTime** `static` | void |  |
| **AddPropertyDecimal** `static` *(+1 overloads)* | void |  |
| **AddPropertyDouble** `static` *(+1 overloads)* | void |  |
| **AddPropertyEnum** `static` *(+1 overloads)* | void |  |
| **AddPropertyFloat** `static` | void |  |
| **AddPropertyFloatNullable** `static` | void |  |
| **AddPropertyFont** `static` | void |  |
| **AddPropertyFontArial10** `static` | void |  |
| **AddPropertyFontArial11** `static` | void |  |
| **AddPropertyFontArial12Bold** `static` | void |  |
| **AddPropertyFontArial13** `static` | void |  |
| **AddPropertyFontArial14Bold** `static` | void |  |
| **AddPropertyFontArial7** `static` | void |  |
| **AddPropertyFontArial8** `static` | void |  |
| **AddPropertyFontArial8BoldPixel** `static` | void |  |
| **AddPropertyFontArial9** `static` | void |  |
| **AddPropertyFontMicrosoftSansSerif8** `static` | void |  |
| **AddPropertyFontSegoeUI20** `static` | void |  |
| **AddPropertyFontTahoma12Bold** `static` | void |  |
| **AddPropertyFontTahoma8** `static` | void |  |
| **AddPropertyIdent** `static` | void |  |
| **AddPropertyImage** `static` | void |  |
| **AddPropertyInt** `static` | void |  |
| **AddPropertyIntArray** `static` | void |  |
| **AddPropertyIntNoDefaultValue** `static` | void |  |
| **AddPropertyJObject** `static` | void |  |
| **AddPropertyListString** `static` | void |  |
| **AddPropertyNameValueCollection** `static` | void |  |
| **AddPropertyNullableColor** `static` | void |  |
| **AddPropertyPoint** `static` | void |  |
| **AddPropertyPointF** `static` | void |  |
| **AddPropertyRectangleD** `static` | void |  |
| **AddPropertyShadow** `static` | void |  |
| **AddPropertyShort** `static` | void |  |
| **AddPropertySize** `static` | void |  |
| **AddPropertySizeD** `static` | void |  |
| **AddPropertyString** `static` *(+1 overloads)* | void |  |
| **AddPropertyStringArray** `static` | void |  |
| **AddPropertyStringIfNotEmpty** `static` | void |  |
| **AddPropertyStringIfNotNull** `static` | void |  |
| **AddPropertyStringNullOrEmpty** `static` | void |  |
| **AddPropertyTimeSpan** `static` | void |  |
| **AddPropertyType** `static` | void |  |
| **RemoveProperty** `static` | void |  |

---

### Method Details

#### AddPropertyArrayColor `static`

**AddPropertyArrayColor**(**jObject**: [JObject](JObject.md), **propertyName**: string, ****: Colorcolors): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **** (Colorcolors)  


---

#### AddPropertyBool `static`

**AddPropertyBool**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: bool, **defaultValue**: bool, **ignoreDefaultValues**: bool): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (bool)  
- **defaultValue** (bool)  
- **ignoreDefaultValues** (bool)  


---

#### AddPropertyBoolArray `static`

**AddPropertyBoolArray**(**jObject**: [JObject](JObject.md), **propertyName**: string, ****: boolarray, **ignoreDefaultValues**: bool): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **** (boolarray)  
- **ignoreDefaultValues** (bool)  


---

#### AddPropertyBorder `static`

**AddPropertyBorder**(**jObject**: [JObject](JObject.md), **propertyName**: string, **border**: [StiSimpleBorder](../../Drawing/StiSimpleBorder.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **border** ([StiSimpleBorder](../../Drawing/StiSimpleBorder.md))  

---

**AddPropertyBorder**(**jObject**: [JObject](JObject.md), **propertyName**: string, **border**: StiBorder): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **border** (StiBorder)  


---

#### AddPropertyBrush `static`

**AddPropertyBrush**(**jObject**: [JObject](JObject.md), **propertyName**: string, **brush**: [StiBrush](../../Drawing/StiBrush.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **brush** ([StiBrush](../../Drawing/StiBrush.md))  


---

#### AddPropertyByteArray `static`

**AddPropertyByteArray**(**jObject**: [JObject](JObject.md), **propertyName**: string, ****: bytebuffer): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **** (bytebuffer)  


---

#### AddPropertyCap `static`

**AddPropertyCap**(**jObject**: [JObject](JObject.md), **propertyName**: string, **cap**: StiCap): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **cap** (StiCap)  


---

#### AddPropertyColor `static`

**AddPropertyColor**(**jObject**: [JObject](JObject.md), **propertyName**: string, **color**: Color, **htmlDefaultColor**: string): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **color** (Color)  
- **htmlDefaultColor** (string)  

---

**AddPropertyColor**(**jObject**: [JObject](JObject.md), **propertyName**: string, **color**: Color, **defaultColor**: Color): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **color** (Color)  
- **defaultColor** (Color)  


---

#### AddPropertyCornerRadius `static`

**AddPropertyCornerRadius**(**jObject**: [JObject](JObject.md), **propertyName**: string, **cornerRadius**: StiCornerRadius): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **cornerRadius** (StiCornerRadius)  


---

#### AddPropertyDateTime `static`

**AddPropertyDateTime**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: DateTime): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (DateTime)  


---

#### AddPropertyDecimal `static`

**AddPropertyDecimal**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: decimal, **defaultValue**: decimal): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (decimal)  
- **defaultValue** (decimal)  

---

**AddPropertyDecimal**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: decimal): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (decimal)  


---

#### AddPropertyDouble `static`

**AddPropertyDouble**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: double, **defaultValue**: double): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (double)  
- **defaultValue** (double)  

---

**AddPropertyDouble**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: double): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (double)  


---

#### AddPropertyEnum `static`

**AddPropertyEnum**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: Enum, **defaultValue**: Enum): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (Enum)  
- **defaultValue** (Enum)  

---

**AddPropertyEnum**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: Enum): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (Enum)  


---

#### AddPropertyFloat `static`

**AddPropertyFloat**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: float, **defaultValue**: float): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (float)  
- **defaultValue** (float)  


---

#### AddPropertyFloatNullable `static`

**AddPropertyFloatNullable**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: float?, **defaultValue**: float?): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (float?)  
- **defaultValue** (float?)  


---

#### AddPropertyFont `static`

**AddPropertyFont**(**jObject**: [JObject](JObject.md), **propertyName**: string, **font**: [Font](../../../Stimulsoft_Drawing/root/Font.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  


---

#### AddPropertyFontArial10 `static`

**AddPropertyFontArial10**(**jObject**: [JObject](JObject.md), **propertyName**: string, **font**: [Font](../../../Stimulsoft_Drawing/root/Font.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  


---

#### AddPropertyFontArial11 `static`

**AddPropertyFontArial11**(**jObject**: [JObject](JObject.md), **propertyName**: string, **font**: [Font](../../../Stimulsoft_Drawing/root/Font.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  


---

#### AddPropertyFontArial12Bold `static`

**AddPropertyFontArial12Bold**(**jObject**: [JObject](JObject.md), **propertyName**: string, **font**: [Font](../../../Stimulsoft_Drawing/root/Font.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  


---

#### AddPropertyFontArial13 `static`

**AddPropertyFontArial13**(**jObject**: [JObject](JObject.md), **propertyName**: string, **font**: [Font](../../../Stimulsoft_Drawing/root/Font.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  


---

#### AddPropertyFontArial14Bold `static`

**AddPropertyFontArial14Bold**(**jObject**: [JObject](JObject.md), **propertyName**: string, **font**: [Font](../../../Stimulsoft_Drawing/root/Font.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  


---

#### AddPropertyFontArial7 `static`

**AddPropertyFontArial7**(**jObject**: [JObject](JObject.md), **propertyName**: string, **font**: [Font](../../../Stimulsoft_Drawing/root/Font.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  


---

#### AddPropertyFontArial8 `static`

**AddPropertyFontArial8**(**jObject**: [JObject](JObject.md), **propertyName**: string, **font**: [Font](../../../Stimulsoft_Drawing/root/Font.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  


---

#### AddPropertyFontArial8BoldPixel `static`

**AddPropertyFontArial8BoldPixel**(**jObject**: [JObject](JObject.md), **propertyName**: string, **font**: [Font](../../../Stimulsoft_Drawing/root/Font.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  


---

#### AddPropertyFontArial9 `static`

**AddPropertyFontArial9**(**jObject**: [JObject](JObject.md), **propertyName**: string, **font**: [Font](../../../Stimulsoft_Drawing/root/Font.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  


---

#### AddPropertyFontMicrosoftSansSerif8 `static`

**AddPropertyFontMicrosoftSansSerif8**(**jObject**: [JObject](JObject.md), **propertyName**: string, **font**: [Font](../../../Stimulsoft_Drawing/root/Font.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  


---

#### AddPropertyFontSegoeUI20 `static`

**AddPropertyFontSegoeUI20**(**jObject**: [JObject](JObject.md), **propertyName**: string, **font**: [Font](../../../Stimulsoft_Drawing/root/Font.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  


---

#### AddPropertyFontTahoma12Bold `static`

**AddPropertyFontTahoma12Bold**(**jObject**: [JObject](JObject.md), **propertyName**: string, **font**: [Font](../../../Stimulsoft_Drawing/root/Font.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  


---

#### AddPropertyFontTahoma8 `static`

**AddPropertyFontTahoma8**(**jObject**: [JObject](JObject.md), **propertyName**: string, **font**: [Font](../../../Stimulsoft_Drawing/root/Font.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  


---

#### AddPropertyIdent `static`

**AddPropertyIdent**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: string): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (string)  


---

#### AddPropertyImage `static`

**AddPropertyImage**(**jObject**: [JObject](JObject.md), **propertyName**: string, **image**: [Image](../../../Stimulsoft_Drawing/root/Image.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **image** ([Image](../../../Stimulsoft_Drawing/root/Image.md))  


---

#### AddPropertyInt `static`

**AddPropertyInt**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: int, **defaultValue**: int): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (int)  
- **defaultValue** (int)  


---

#### AddPropertyIntArray `static`

**AddPropertyIntArray**(**jObject**: [JObject](JObject.md), **propertyName**: string, ****: intarray): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **** (intarray)  


---

#### AddPropertyIntNoDefaultValue `static`

**AddPropertyIntNoDefaultValue**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: int): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (int)  


---

#### AddPropertyJObject `static`

**AddPropertyJObject**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: [JObject](JObject.md), **saveIfEmpty**: bool): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** ([JObject](JObject.md))  
- **saveIfEmpty** (bool)  


---

#### AddPropertyListString `static`

**AddPropertyListString**(**jObject**: [JObject](JObject.md), **propertyName**: string, **array**: List<string>): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **array** (List<string>)  


---

#### AddPropertyNameValueCollection `static`

**AddPropertyNameValueCollection**(**jObject**: [JObject](JObject.md), **propertyName**: string, **collection**: NameValueCollection): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **collection** (NameValueCollection)  


---

#### AddPropertyNullableColor `static`

**AddPropertyNullableColor**(**jObject**: [JObject](JObject.md), **propertyName**: string, **color**: Color?, **defaultColor**: Color?): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **color** (Color?)  
- **defaultColor** (Color?)  


---

#### AddPropertyPoint `static`

**AddPropertyPoint**(**jObject**: [JObject](JObject.md), **propertyName**: string, **point**: Point): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **point** (Point)  


---

#### AddPropertyPointF `static`

**AddPropertyPointF**(**jObject**: [JObject](JObject.md), **propertyName**: string, **point**: PointF): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **point** (PointF)  


---

#### AddPropertyRectangleD `static`

**AddPropertyRectangleD**(**jObject**: [JObject](JObject.md), **propertyName**: string, **rect**: [RectangleD](../../Drawing/RectangleD.md)): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **rect** ([RectangleD](../../Drawing/RectangleD.md))  


---

#### AddPropertyShadow `static`

**AddPropertyShadow**(**jObject**: [JObject](JObject.md), **propertyName**: string, **shadow**: StiSimpleShadow): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **shadow** (StiSimpleShadow)  


---

#### AddPropertyShort `static`

**AddPropertyShort**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: short, **defaultValue**: short): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (short)  
- **defaultValue** (short)  


---

#### AddPropertySize `static`

**AddPropertySize**(**jObject**: [JObject](JObject.md), **propertyName**: string, **size**: Size): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **size** (Size)  


---

#### AddPropertySizeD `static`

**AddPropertySizeD**(**jObject**: [JObject](JObject.md), **propertyName**: string, **size**: [SizeD](../../Drawing/SizeD.md), **defaultValue**: string, ****: 0"): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **size** ([SizeD](../../Drawing/SizeD.md))  
- **defaultValue** (string)  
- **** (0")  


---

#### AddPropertyString `static`

**AddPropertyString**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: string, **defaultValue**: string): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (string)  
- **defaultValue** (string)  

---

**AddPropertyString**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: string): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (string)  


---

#### AddPropertyStringArray `static`

**AddPropertyStringArray**(**jObject**: [JObject](JObject.md), **propertyName**: string, ****: stringarray): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **** (stringarray)  


---

#### AddPropertyStringIfNotEmpty `static`

**AddPropertyStringIfNotEmpty**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: string): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (string)  


---

#### AddPropertyStringIfNotNull `static`

**AddPropertyStringIfNotNull**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: string): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (string)  


---

#### AddPropertyStringNullOrEmpty `static`

**AddPropertyStringNullOrEmpty**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: string): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (string)  


---

#### AddPropertyTimeSpan `static`

**AddPropertyTimeSpan**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: TimeSpan): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (TimeSpan)  


---

#### AddPropertyType `static`

**AddPropertyType**(**jObject**: [JObject](JObject.md), **propertyName**: string, **value**: Type): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  
- **value** (Type)  


---

#### RemoveProperty `static`

**RemoveProperty**(**jObject**: [JObject](JObject.md), **propertyName**: string): void

**Parameters**

- **jObject** ([JObject](JObject.md))  
- **propertyName** (string)  

