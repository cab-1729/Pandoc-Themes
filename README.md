# Pandoc-Themes
General purpose themes for converting markdown to pdf using pandoc.

Examples for each theme stored in the _examples_ directory.

## Usage
__Warning_: These templates are very liberal with packages and assume the user has the entirety of texlive installed._

Symlink or copy the template files to your /usr/share/pandoc/data/templates/.

Copy or symlink _pandoc-fonts_ to /usr/share/fonts/.

```bash
pandoc --pdf-engine=xelatex -f markdown -t pdf --template=name_of_template.tex /path/to/markdown/file.md > /path/to/pdf/file.pdf
```
Metadata from markdown file will not be given priority. Most of the things will be set by the templates.

## Other projects
+ All of the testing is done with [zathura](https://wiki.archlinux.org/title/zathura)
+ The fonts have been obtained using [woff2ttf](https://archlinux.org/packages/extra/x86_64/woff2/) and [woff2otf.py](https://github.com/hanikesn/woff2otf)
+ Themes are inspired from all those who wrote themes for Typora
+ Of course, none of this would be possible without [pandoc](https://pandoc.org/) and [texlive](https://www.tug.org/texlive/)
