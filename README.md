# Table of Contents
1.  [<SUBMODULE> LaTeX submodule:](#org9a8bce7)
    1.  [Adding it as a submodule:](#org1532e58)
    2.  [Include the submodule into a LaTeX formularyETH:](#org3172ee7)
        1.  [In order to include figures add to graphicspath](#org3084e32)


# <SUBMODULE> LaTeX submodule:

<DESCRIPTION>

## Adding this submodule to a LaTeX formulary:

    cd <path to formulary/folder>
    git submodule add git@github.com:grpollak/formularyETH.git/<SUBMODULE>_submodule.git

## Include the submodule into a LaTeX [formularyETH](https://github.com/git@github.com:grpollak/formularyETH.git):
``` tex
\section*{<SUBMODULE> Background}
    \input{<SUBMODULE>_submodule/<SUBMODULE>.tex}
```
### In order to include figures add to graphicspath
``` tex
\graphicspath{
    ...
    {<SUBMODULE>_submodule/figures/}
}
```

