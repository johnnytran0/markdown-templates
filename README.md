# markdown-templates

## Prerequisites
* [jgm/pandoc](https://github.com/jgm/pandoc)
	* [Pandoc User's Guide](https://pandoc.org/MANUAL.html#)
* [plantuml/plantuml](https://github.com/plantuml/plantuml)
	* [Drawing UML with PlantUML](https://plantuml.com/guide)

## Getting Started
```bash
 plantuml -svg template.md && pandoc template.md -o powerpoint.pptx --reference-doc=references/custom-reference.pptx
 ```
