This edition of the book has been converted to LaTeX.
In order to build it, ensure you have a TeX distribution that contains
the `pdflatex` command. With that, you should be able to build the book
by running `make`, which will clone the OS itself and build the book
to `book.pdf` in the main directory.

Figures are drawn using `inkscape`.

---

该仓库正在尝试将 xv6 手册翻译为中文。

由于新增了中文内容，构建命令已切换为 `xelatex`，运行 `make` 即可生成 `book.pdf`。
如果你的环境已安装 `texlive-full`（或等价完整 LaTeX 环境），通常无需额外配置。
