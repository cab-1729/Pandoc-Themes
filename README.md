# Pandoc-Themes
General purpose themes for converting markdown to pdf using pandoc

## Usage
```bash
pandoc --pdf-engine=xelatex -f markdown -t pdf --data-dir=/path/to/theme/folder/ --template=name_of_template.latex > /path/to/pdf/file
```

## Other projects
+ All of the testing is done with [zathura](https://wiki.archlinux.org/title/zathura)
+ The fonts have been obtained using [woff2ttf](https://archlinux.org/packages/extra/x86_64/woff2/) and [woff2otf.py](https://github.com/hanikesn/woff2otf)
+ Themes are inspired from all those who wrote themes for Typora
+ Of course, none of this would be possible without [pandoc](https://pandoc.org/) and [texlive](https://www.tug.org/texlive/)

## Contributing
I know this is probably the loneliest account on Github, so most probably no one is reading this except me.
But in case someone else is, **please contribute code**.

I am aiming to make pandoc equivalents for all of Typora's themes. Their css source code is available on the internet. Please make sure themes are compatible with all markdown structures and common pandoc extensions.
