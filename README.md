# MyRenv
My Renv Base

For a new project

Download the MyRenv lock and Activate file
```shell
git clone https://github.com/chenweng1991/MyRenv.git
```

In R,
```R
source("activate.R")
Sys.setenv(RENV_PATHS_CACHE = "/lab/solexa_weissman/cweng/Packages/R/x86_64-pc-linux-gnu-library/4.1-focal")   ## If in a new system, assign a path for cache
renv::paths$cache()
.libPaths()
```
