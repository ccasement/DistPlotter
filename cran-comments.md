## Test environments
- R-hub windows-x86_64-devel (r-devel)
- R-hub ubuntu-gcc-release (r-release)
- R-hub fedora-clang-devel (r-devel)

## R CMD check results
> On windows-x86_64-devel (r-devel), ubuntu-gcc-release (r-release), fedora-clang-devel (r-devel)
  checking CRAN incoming feasibility ... NOTE
  Maintainer: 'Christopher Casement <casementc@gmail.com>'
  
  New submission

> On windows-x86_64-devel (r-devel)
  checking for detritus in the temp directory ... NOTE
  Found the following files/directories:
    'lastMiKTeXException'

  There were 2 NOTES. The first NOTE is due to a new submission, and the second 
  NOTE might be due to a bug/crash in MiKTeX, as is noted in R-hub issue #503, 
  which can be found at https://github.com/r-hub/rhub/issues/503.

0 errors √ | 0 warnings √ | 2 notes x
