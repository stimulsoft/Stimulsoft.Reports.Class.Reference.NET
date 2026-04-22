---
title: "StiLexer Class"
---

## StiLexer Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

Performs the lexical analysis.

```csharp
public sealed class StiLexer
```

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLexer**(string textValue) | Creates a new instance of the StiLexer class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **IsVB** | bool |  |
| **PositionInText** | int | Gets or sets current position in text. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetAllTokens** `static` | List<[StiToken](StiToken.md)> |  |
| **GetPosition** | [StiPosition](StiPosition.md) | Gets position of token in text. |
| **GetToken** | [StiToken](StiToken.md) | Gets next token. |
| **IdentExists** `static` | bool |  |
| **ReplaceWithNotEqualPrefix** | void | Replaces all occurrences of a specified String, with another specified string. Before oldValue must not follow specified prefix - string. |
| **ReplaceWithPrefix** `static` *(+1 overloads)* | string | Replaces all occurrences of a specified String, with another specified String. Before oldValue must follow specified prefix - token. Replacing is produced with provision for tokens. |
| **Reset** | void | Reset state. |
| **SavePosToken** | void | Saves position of token in text. |
| **ScanChar** | [StiToken](StiToken.md) | Scans the symbol. |
| **ScanIdent** | [StiToken](StiToken.md) | Scans the identifier. |
| **ScanInterpolatedString** | [StiToken](StiToken.md) | Scans an interpolated string, which begins with $" and can contain expressions in { }. |
| **ScanNumber** | [StiToken](StiToken.md) | Scans the number. |
| **ScanString** | [StiToken](StiToken.md) | Scans the string. |
| **SkipWhitespaceAndComments** | void | Skips all whitespace and comments (both single-line and multi-line). |
| **UngetToken** | void | Returns to previous token. |
| **WaitAssign2** | bool | Wait the assign. |
| **WaitComma2** | bool | Wait the right bracket. |
| **WaitLbrace2** | bool | Wait the left brace. |
| **WaitLparen2** | bool | Wait the left paren. |
| **WaitRbrace2** | bool | Wait the right brace. |
| **WaitRparen2** | bool | Wait the right paren. |
| **WaitSemicolon2** | bool | Wait the semicolon. |
