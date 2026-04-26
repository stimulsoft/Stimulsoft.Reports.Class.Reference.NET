---
title: "StiLexerException Class"
---

## StiLexerException Class

**Namespace:** `Stimulsoft.Base`

The exception that is thrown when a lexical analysis error occurs.

### Inheritance

Inherits from: Exception  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiLexerException**([StiLexerError](StiLexerError.md) error) | Create a new instance of the StiLexerException class. |

**StiLexerException**(**error**: [StiLexerError](StiLexerError.md))

Create a new instance of the StiLexerException class.

**Parameters**

- **error** ([StiLexerError](StiLexerError.md)) — Type of lexical analysis error.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **LexerError** | [StiLexerError](StiLexerError.md) | Gets or sets type of lexical analysis error. |
