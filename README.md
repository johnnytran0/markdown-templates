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
### Convert Markdown
#### Word
```bash
pandoc template.md -o template.docx \
  --highlight-style tango \
  --reference-doc=references/custom-reference.docx
```
#### PowerPoint
```bash
pandoc template.md -o template.pptx \
  --reference-doc=references/custom-reference.pptx
```
