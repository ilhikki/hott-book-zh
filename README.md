同伦类型论：数学的一价语义基础
=
本书是 [The HoTT Book](https://github.com/HoTT/book) 的非官方翻译。
当前进度是第一章。

## License
This work is licensed under the
[Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/).

## 获得 PDF
### 编译 .tex 文件
1. 准备编译环境，参照[原著的 README 文件](README.src.md)。
1. 使用命令
```
latexmk -xelatex  -interaction=batchmode  hott-online.tex
```
注意项目使用 `xelatex` 支持中文，但只做了必要的兼容。所以 `makefile` 无法直接使用，不再兼容 LaTex 的 `ifpdf` 命令。

### 直接下载 Releases

## 其它
本项目使用的翻译辅助工具是 [OmegaT](https://github.com/omegat-org/omegat) 。
但是修改了它的 LaTex 过滤器，暂时没有上传翻译库和词汇表到此项目中。

