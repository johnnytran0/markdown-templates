# markdown-templates

## Prerequisites
* [jgm/pandoc](https://github.com/jgm/pandoc)
  * [Pandoc User's Guide](https://pandoc.org/MANUAL.html#)
* [plantuml/plantuml](https://github.com/plantuml/plantuml)
  * [Drawing UML with PlantUML](https://plantuml.com/guide)

## Getting Started
### Generate PlantUML diagrams
```bash
plantuml -svg document.md
```

### PDF
```bash
pandoc document.md -o output.pdf \
  --pdf-engine=xelatex \
  -V geometry=margin=1in
```

#### fonts
```bash
pandoc document.md -o output.pdf \
  --pdf-engine=xelatex \
  -V geometry=margin=1in \
  -V mainfont="Source Serif 4"
```

[man fc-list](https://linux.die.net/man/1/fc-list)
> lists fonts and styles available on the system for applications using fontconfig
```{#fc-list .bash}
fc-list --format="%{family[0]}\n" | sort | uniq
```

### Style Reference
* https://pandoc.org/MANUAL.html#option--reference-doc

#### Word
```bash
pandoc document.md -o output.docx \
  --highlight-style tango \
  --reference-doc=.pandoc/reference.docx
```
* [Customize or create new styles](https://support.microsoft.com/en-us/office/customize-or-create-new-styles-d38d6e47-f6fc-48eb-a607-1eb120dec563)

#### PowerPoint
```bash
pandoc pptx.md -o output.pptx \
  --reference-doc=.pandoc/reference.pptx
```
* https://pandoc.org/MANUAL.html#powerpoint-layout-choice
* [PowerPoint Help & Training / Slides & layouts / What is a slide master?](https://support.microsoft.com/en-us/office/what-is-a-slide-master-b9abb2a0-7aef-4257-a14e-4329c904da54)

## Markdown
* [Markdown v1.0.1: Syntax](https://daringfireball.net/projects/markdown/syntax)
* GitHub Flavored Markdown (gfm)
  * [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
  * [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#alerts)
  * :notebook_with_decorative_cover: [ikatyang/emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet?tab=readme-ov-file#table-of-contents)
