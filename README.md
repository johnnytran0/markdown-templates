# markdown-templates

## Prerequisites
* [jgm/pandoc](https://github.com/jgm/pandoc)
  * [Pandoc User's Guide](https://pandoc.org/MANUAL.html#)
* [plantuml/plantuml](https://github.com/plantuml/plantuml)
  * [Drawing UML with PlantUML](https://plantuml.com/guide)

## Getting Started
### Generate PlantUML diagrams
```bash
plantuml -svg template.md
```
### Style Reference
* https://pandoc.org/MANUAL.html#option--reference-doc

#### Word
* [Customize or create new styles](https://support.microsoft.com/en-us/office/customize-or-create-new-styles-d38d6e47-f6fc-48eb-a607-1eb120dec563)

```bash
pandoc template.md -o template.docx \
  --highlight-style tango \
  --reference-doc=.pandoc/reference.docx
```
#### PowerPoint
```bash
pandoc template.md -o template.pptx \
  --reference-doc=.pandoc/reference.pptx
```
* https://pandoc.org/MANUAL.html#powerpoint-layout-choice
* [PowerPoint Help & Training / Slides & layouts / What is a slide master?](https://support.microsoft.com/en-us/office/what-is-a-slide-master-b9abb2a0-7aef-4257-a14e-4329c904da54)
