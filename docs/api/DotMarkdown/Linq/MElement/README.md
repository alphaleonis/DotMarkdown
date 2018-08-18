<a name="_top"></a>

# MElement Class

[Home](../../../README.md#_top) &#x2022; [Constructors](#constructors) &#x2022; [Properties](#properties) &#x2022; [Methods](#methods)

**Namespace**: [DotMarkdown.Linq](../README.md#_top)

**Assembly**: DotMarkdown\.dll

```csharp
public abstract class MElement : MObject
```

### Inheritance

[Object](https://docs.microsoft.com/en-us/dotnet/api/system.object) &#x2192; [MObject](../MObject/README.md#_top) &#x2192; MElement

### Derived

* DotMarkdown\.Linq\.[MAutolink](../MAutolink/README.md#_top)
* DotMarkdown\.Linq\.[MBlockContainer](../MBlockContainer/README.md#_top)
* DotMarkdown\.Linq\.[MBlockQuote](../MBlockQuote/README.md#_top)
* DotMarkdown\.Linq\.[MBold](../MBold/README.md#_top)
* DotMarkdown\.Linq\.[MBulletItem](../MBulletItem/README.md#_top)
* DotMarkdown\.Linq\.[MBulletList](../MBulletList/README.md#_top)
* DotMarkdown\.Linq\.[MComment](../MComment/README.md#_top)
* DotMarkdown\.Linq\.[MContainer](../MContainer/README.md#_top)
* DotMarkdown\.Linq\.[MDocument](../MDocument/README.md#_top)
* DotMarkdown\.Linq\.[MEntityRef](../MEntityRef/README.md#_top)
* [...](#all-derived-types)

## Constructors

| Constructor | Summary |
| ----------- | ------- |
| [MElement()](-ctor/README.md#_top) | |

## Properties

| Property | Summary |
| -------- | ------- |
| [Document](../MObject/Document/README.md#_top) |  \(Inherited from [MObject](../MObject/README.md#_top)\) |
| [Kind](../MObject/Kind/README.md#_top) |  \(Inherited from [MObject](../MObject/README.md#_top)\) |
| [NextElement](NextElement/README.md#_top) | |
| [Parent](../MObject/Parent/README.md#_top) |  \(Inherited from [MObject](../MObject/README.md#_top)\) |
| [PreviousElement](PreviousElement/README.md#_top) | |

## Methods

| Method | Summary |
| ------ | ------- |
| [Ancestors()](Ancestors/README.md#_top) | |
| [ElementsAfterSelf()](ElementsAfterSelf/README.md#_top) | |
| [ElementsBeforeSelf()](ElementsBeforeSelf/README.md#_top) | |
| [Equals(Object)](https://docs.microsoft.com/en-us/dotnet/api/system.object.equals) |  \(Inherited from [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)\) |
| [GetHashCode()](https://docs.microsoft.com/en-us/dotnet/api/system.object.gethashcode) |  \(Inherited from [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)\) |
| [GetType()](https://docs.microsoft.com/en-us/dotnet/api/system.object.gettype) |  \(Inherited from [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)\) |
| [MemberwiseClone()](https://docs.microsoft.com/en-us/dotnet/api/system.object.memberwiseclone) |  \(Inherited from [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)\) |
| [Remove()](Remove/README.md#_top) | |
| [Save(MarkdownWriter)](Save/README.md#DotMarkdown_Linq_MElement_Save_DotMarkdown_MarkdownWriter_) | |
| [Save(Stream, MarkdownFormat)](Save/README.md#DotMarkdown_Linq_MElement_Save_System_IO_Stream_DotMarkdown_MarkdownFormat_) | |
| [Save(String, MarkdownFormat)](Save/README.md#DotMarkdown_Linq_MElement_Save_System_String_DotMarkdown_MarkdownFormat_) | |
| [Save(TextWriter, MarkdownFormat)](Save/README.md#DotMarkdown_Linq_MElement_Save_System_IO_TextWriter_DotMarkdown_MarkdownFormat_) | |
| [ToString()](ToString/README.md#DotMarkdown_Linq_MElement_ToString) |  \(Overrides [Object.ToString](https://docs.microsoft.com/en-us/dotnet/api/system.object.tostring)\) |
| [ToString(MarkdownFormat)](ToString/README.md#DotMarkdown_Linq_MElement_ToString_DotMarkdown_MarkdownFormat_) | |
| [ToString(MarkdownWriterSettings)](ToString/README.md#DotMarkdown_Linq_MElement_ToString_DotMarkdown_MarkdownWriterSettings_) | |
| [WriteTo(MarkdownWriter)](WriteTo/README.md#_top) | |

## All Derived Types

* DotMarkdown\.Linq\.[MAutolink](../MAutolink/README.md#_top)
* DotMarkdown\.Linq\.[MBlockContainer](../MBlockContainer/README.md#_top)
* DotMarkdown\.Linq\.[MBlockQuote](../MBlockQuote/README.md#_top)
* DotMarkdown\.Linq\.[MBold](../MBold/README.md#_top)
* DotMarkdown\.Linq\.[MBulletItem](../MBulletItem/README.md#_top)
* DotMarkdown\.Linq\.[MBulletList](../MBulletList/README.md#_top)
* DotMarkdown\.Linq\.[MComment](../MComment/README.md#_top)
* DotMarkdown\.Linq\.[MContainer](../MContainer/README.md#_top)
* DotMarkdown\.Linq\.[MDocument](../MDocument/README.md#_top)
* DotMarkdown\.Linq\.[MEntityRef](../MEntityRef/README.md#_top)
* DotMarkdown\.Linq\.[MFencedCodeBlock](../MFencedCodeBlock/README.md#_top)
* DotMarkdown\.Linq\.[MHeading](../MHeading/README.md#_top)
* DotMarkdown\.Linq\.[MHorizontalRule](../MHorizontalRule/README.md#_top)
* DotMarkdown\.Linq\.[MCharEntity](../MCharEntity/README.md#_top)
* DotMarkdown\.Linq\.[MImage](../MImage/README.md#_top)
* DotMarkdown\.Linq\.[MIndentedCodeBlock](../MIndentedCodeBlock/README.md#_top)
* DotMarkdown\.Linq\.[MInline](../MInline/README.md#_top)
* DotMarkdown\.Linq\.[MInlineCode](../MInlineCode/README.md#_top)
* DotMarkdown\.Linq\.[MItalic](../MItalic/README.md#_top)
* DotMarkdown\.Linq\.[MLabel](../MLabel/README.md#_top)
* DotMarkdown\.Linq\.[MLink](../MLink/README.md#_top)
* DotMarkdown\.Linq\.[MList](../MList/README.md#_top)
* DotMarkdown\.Linq\.[MOrderedItem](../MOrderedItem/README.md#_top)
* DotMarkdown\.Linq\.[MOrderedList](../MOrderedList/README.md#_top)
* DotMarkdown\.Linq\.[MRaw](../MRaw/README.md#_top)
* DotMarkdown\.Linq\.[MStrikethrough](../MStrikethrough/README.md#_top)
* DotMarkdown\.Linq\.[MTable](../MTable/README.md#_top)
* DotMarkdown\.Linq\.[MTableColumn](../MTableColumn/README.md#_top)
* DotMarkdown\.Linq\.[MTableRow](../MTableRow/README.md#_top)
* DotMarkdown\.Linq\.[MTaskItem](../MTaskItem/README.md#_top)
* DotMarkdown\.Linq\.[MTaskList](../MTaskList/README.md#_top)
* DotMarkdown\.Linq\.[MText](../MText/README.md#_top)
