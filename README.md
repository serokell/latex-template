# Serokell LaTeX templates (`latex-template`)

This is a repository containing templates for creating LaTeX documents.

## Use

* Install Pandoc and TeX Live (only tested with full).
* Copy your `.md` document into the same diretory as the templates
  (this needs to be done due to relative paths to images used in templates).
* Run: `pandoc --pdf-engine=xelatex --template=./serokell.latex <input.md> -o <output.pdf>`


## License

[MPL-2.0] © [Serokell]

[MPL-2.0]: https://spdx.org/licenses/MPL-2.0.html
[Serokell]: https://serokell.io/
