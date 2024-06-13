# Markdown-Syntax-Basics
A repository for Markdown syntax basics for GitHub beginners

# Markdown Syntax Basics

Markdown is a lightweight markup language with plain-text formatting syntax. It is widely used for formatting README files on GitHub. Here are some basic Markdown syntax elements you can use to format your text:

## Headings

Use `#` for headings. The number of `#`s indicates the level of the heading. For example:

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Bold and Italic

To make text **bold**, wrap it with double asterisks `**` or double underscores `__`.

To make text *italic*, wrap it with single asterisks `*` or single underscores `_`.

For example:

**This text is bold**  
__This text is also bold__

*This text is italic*  
_This text is also italic_

## Lists

### Unordered Lists

To create an unordered list, use `-` or `*` followed by a space:

- Item 1
- Item 2
  - Subitem A
  - Subitem B
    - Sub-subitem i
    - Sub-subitem ii
- Item 3

### Ordered Lists

To create an ordered list, use numbers followed by periods and a space:

1. First item
2. Second item
3. Third item
   1. Subitem 1
   2. Subitem 2
      - Sub-subitem a
      - Sub-subitem b
4. Fourth item

## Links

To create a hyperlink, use square brackets `[]` for the link text and round brackets `()` for the URL:

[GitHub-MFMKURIA](https://github.com/MFMKURIA)

## Images

To display an image, use an exclamation mark `!`, followed by square brackets `[]` for the alt text and round brackets `()` for the image URL:

![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

## Blockquotes

To create a blockquote, use the greater than sign `>`:

> This is a blockquote.
> You can write multiple lines.

## Code Blocks

To create a code block, wrap your code with three backticks ```:

To specify the language, you can use three backticks followed by the language name:

```python
def greet():
    print("Hello, world!")
```

## The Horizontal Rule
To create a horizontal rule, 
use three or more 
- hyphens ---
or
- asterisks ***
or
underscores ___

## Escape Characters
To display literal characters that have special meaning in Markdown, you can use the backslash `\` :

*This text will not be italicized*

## Tables
You can create tables using hyphens `-`, pipes `|`, and colons `:`. 

Here's an example:

| Name  | Age | Gender |
|-------|-----|--------|
| John  | 30  | Male   |
| Alice | 25  | Female |

or

| Left-aligned | Center-aligned | Right-aligned |
| :----------- | :------------: | ------------: |
| Left         | Center         | Right         |
| Left         | Center         | Right         |

