# Pandoc-Themes
General purpose themes for converting markdown to pdf using pandoc.

Examples for each theme stored in the _examples_ directory.

__Warning_: These templates are very liberal with packages and assume the user has the entirety of texlive installed._

## Usage

Symlink or copy the template files to your /usr/share/pandoc/data/templates/.

Copy or symlink _pandoc-fonts_ to /usr/share/fonts/.

```bash
pandoc --pdf-engine=xelatex -f markdown -t pdf --template=name_of_template.tex /path/to/markdown/file.md > /path/to/pdf/file.pdf
```
Metadata from markdown file will not be given priority. Most of the things will be set by the templates.

## Contributing
This is the loneliest account on Github, but in case anyone who is reading this who is not me, this is too big of a project to be handled by one person. So if you have the skills please consider contributing code.

Possible ways you can help:
+ Create a new pandoc template from an existing Typora theme. Stick as close as possible to the original source. If you want to do this I would recommend copying any template here and editing it to create the new one as it maintains code consistency.
+ Solve any one of the known issues
+ Review the code and recommend a simplification

### Known issues

**None**

## Other projects
+ All of the testing is done with [zathura](https://wiki.archlinux.org/title/zathura)
+ The fonts have been obtained using [woff2ttf](https://archlinux.org/packages/extra/x86_64/woff2/) and [woff2otf.py](https://github.com/hanikesn/woff2otf)
+ [typora-free](https://aur.archlinux.org/packages/typora-free) for the AUR was used for visual aid
+ Themes are inspired from all those who wrote themes for Typora
+ Of course, none of this would be possible without [pandoc](https://pandoc.org/) and [texlive](https://www.tug.org/texlive/)
