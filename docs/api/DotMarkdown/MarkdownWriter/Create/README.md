# MarkdownWriter\.Create Method

[Home](../../../README.md)

**Containing Type**: DotMarkdown\.[MarkdownWriter](../README.md)

**Assembly**: DotMarkdown\.dll

## Overloads

| Method | Summary |
| ------ | ------- |
| [Create(Stream, Encoding, MarkdownWriterSettings)](#DotMarkdown_MarkdownWriter_Create_System_IO_Stream_System_Text_Encoding_DotMarkdown_MarkdownWriterSettings_) | |
| [Create(Stream, MarkdownWriterSettings)](#DotMarkdown_MarkdownWriter_Create_System_IO_Stream_DotMarkdown_MarkdownWriterSettings_) | |
| [Create(StringBuilder, IFormatProvider, MarkdownWriterSettings)](#DotMarkdown_MarkdownWriter_Create_System_Text_StringBuilder_System_IFormatProvider_DotMarkdown_MarkdownWriterSettings_) | |
| [Create(StringBuilder, MarkdownWriterSettings)](#DotMarkdown_MarkdownWriter_Create_System_Text_StringBuilder_DotMarkdown_MarkdownWriterSettings_) | |
| [Create(TextWriter, MarkdownWriterSettings)](#DotMarkdown_MarkdownWriter_Create_System_IO_TextWriter_DotMarkdown_MarkdownWriterSettings_) | |

## Create\(Stream, Encoding, MarkdownWriterSettings\) <a name="DotMarkdown_MarkdownWriter_Create_System_IO_Stream_System_Text_Encoding_DotMarkdown_MarkdownWriterSettings_"></a>

```csharp
public static DotMarkdown.MarkdownWriter Create(System.IO.Stream stream, System.Text.Encoding encoding, DotMarkdown.MarkdownWriterSettings settings = null)
```

### Parameters

**stream** &emsp; System\.IO\.[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)

**encoding** &emsp; System\.Text\.[Encoding](https://docs.microsoft.com/en-us/dotnet/api/system.text.encoding)

**settings** &emsp; DotMarkdown\.[MarkdownWriterSettings](../../MarkdownWriterSettings/README.md)

### Returns

DotMarkdown\.[MarkdownWriter](../README.md)

## Create\(Stream, MarkdownWriterSettings\) <a name="DotMarkdown_MarkdownWriter_Create_System_IO_Stream_DotMarkdown_MarkdownWriterSettings_"></a>

```csharp
public static DotMarkdown.MarkdownWriter Create(System.IO.Stream stream, DotMarkdown.MarkdownWriterSettings settings = null)
```

### Parameters

**stream** &emsp; System\.IO\.[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)

**settings** &emsp; DotMarkdown\.[MarkdownWriterSettings](../../MarkdownWriterSettings/README.md)

### Returns

DotMarkdown\.[MarkdownWriter](../README.md)

## Create\(StringBuilder, IFormatProvider, MarkdownWriterSettings\) <a name="DotMarkdown_MarkdownWriter_Create_System_Text_StringBuilder_System_IFormatProvider_DotMarkdown_MarkdownWriterSettings_"></a>

```csharp
public static DotMarkdown.MarkdownWriter Create(System.Text.StringBuilder output, System.IFormatProvider formatProvider, DotMarkdown.MarkdownWriterSettings settings = null)
```

### Parameters

**output** &emsp; System\.Text\.[StringBuilder](https://docs.microsoft.com/en-us/dotnet/api/system.text.stringbuilder)

**formatProvider** &emsp; System\.[IFormatProvider](https://docs.microsoft.com/en-us/dotnet/api/system.iformatprovider)

**settings** &emsp; DotMarkdown\.[MarkdownWriterSettings](../../MarkdownWriterSettings/README.md)

### Returns

DotMarkdown\.[MarkdownWriter](../README.md)

## Create\(StringBuilder, MarkdownWriterSettings\) <a name="DotMarkdown_MarkdownWriter_Create_System_Text_StringBuilder_DotMarkdown_MarkdownWriterSettings_"></a>

```csharp
public static DotMarkdown.MarkdownWriter Create(System.Text.StringBuilder output, DotMarkdown.MarkdownWriterSettings settings = null)
```

### Parameters

**output** &emsp; System\.Text\.[StringBuilder](https://docs.microsoft.com/en-us/dotnet/api/system.text.stringbuilder)

**settings** &emsp; DotMarkdown\.[MarkdownWriterSettings](../../MarkdownWriterSettings/README.md)

### Returns

DotMarkdown\.[MarkdownWriter](../README.md)

## Create\(TextWriter, MarkdownWriterSettings\) <a name="DotMarkdown_MarkdownWriter_Create_System_IO_TextWriter_DotMarkdown_MarkdownWriterSettings_"></a>

```csharp
public static DotMarkdown.MarkdownWriter Create(System.IO.TextWriter output, DotMarkdown.MarkdownWriterSettings settings = null)
```

### Parameters

**output** &emsp; System\.IO\.[TextWriter](https://docs.microsoft.com/en-us/dotnet/api/system.io.textwriter)

**settings** &emsp; DotMarkdown\.[MarkdownWriterSettings](../../MarkdownWriterSettings/README.md)

### Returns

DotMarkdown\.[MarkdownWriter](../README.md)

