# Learning Markdown Language

## Introduction

Markdown is a lightweight markup language used to format text. It is commonly used for technical documentation, README files, and project notes.

This article demonstrates different Markdown syntaxes and explains how they are used.

---

## 1. Headings

Markdown supports six levels of headings.

# Heading Level 1
## Heading Level 2
### Heading Level 3
#### Heading Level 4
##### Heading Level 5
###### Heading Level 6

## 2. Text Formatting

Markdown supports several text formatting options.

- **Bold text**
- *Italic text*
- ***Bold and italic text***
- ~~Strikethrough text~~

You can display a command inside a sentence using `inline code`.

## 3. Paragraphs and Line Breaks

This is the first paragraph.

This is the second paragraph, separated by a blank line.

This line ends with two spaces to create a line break.  
This sentence appears on the next line.

## 4. Unordered Lists

Common computer components include:

- Hardware
- Software
- Networking
- Storage

### Nested Unordered Lists

- Hardware
  - Keyboard
  - Mouse
  - Monitor
- Software
  - Operating systems
  - Applications

## 5. Ordered Lists

Steps for creating a Git repository:

1. Create a project folder.
2. Open the folder in VS Code.
3. Initialize Git.
4. Create a Markdown file.
5. Commit the changes.

## 6. Links

Visit [GitHub](https://github.com) to explore software repositories.

Visit the [Markdown Guide](https://www.markdownguide.org/) to learn more.

## 7. Images

Markdown can display an image using this syntax:

![Example image](https://placehold.co/400x200/png)

## 8. Blockquotes

Blockquotes highlight important information.

> Markdown makes technical documentation easier to write and maintain.

Nested blockquotes are also possible.

> This is the main quotation.
>
> > This is a nested quotation.

## 9. Inline Code

Use backticks to display commands within a sentence.

For example, `git status` displays the current Git repository status.

## 10. Code Blocks

### PowerShell Example

```powershell
Get-Process
Get-Service
```

### Git Example

```bash
git status
git add MarkdownArticle.md
git commit -m "Add Markdown article"
```

## 11. Tables

| Technology | Purpose | Example |
|---|---|---|
| Markdown | Format documentation | README.md |
| Git | Track changes | git commit |
| GitHub | Host repositories | Remote repository |

## 12. Task Lists

- [x] Create a project folder
- [x] Create a Markdown file
- [ ] Review the article
- [ ] Commit the changes

## 13. Horizontal Rules

Horizontal rules separate sections.

---

This paragraph appears after a horizontal rule.

***

## 14. Escaping Special Characters

A backslash can display a Markdown character without applying its formatting.

\*This text is surrounded by literal asterisks.\*

\# This is not a heading.

## 15. Automatic Links

Some Markdown renderers automatically convert URLs into clickable links.

https://github.com

## 16. HTML in Markdown

Some Markdown renderers support basic HTML.

<p>This paragraph uses an HTML paragraph tag.</p>

<details>
<summary>Click to expand</summary>

This is additional information inside an HTML details element.

</details>

HTML support depends on the Markdown renderer.

## 17. Conclusion

Markdown provides a simple way to create readable technical documents.

By using headings, lists, text formatting, links, code blocks, tables, and other syntax, users can create organized documentation for software projects.

Saving Markdown files in a Git repository also makes it possible to track changes and maintain a history of the document.