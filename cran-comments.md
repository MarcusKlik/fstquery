
## Submission

This is a submission. In this version the following changes have been made:

## Test environments

* OS X on travis-ci
* Ubuntu 14.04 on travis-ci
* Ubuntu 16.04 locally
* docker with the rocker/r-devel-ubsan-clang instrumented image
* docker with the rocker/r-devel-san instrumented image
* Windows 10 local R 3.4.3
* Windows Server 2012 R2 x64 (build 9600) on AppVeyor R 3.4.3
* R-hub all available platforms. Note: OpenMP is not enabled on most platforms, so limited testing possible.

## R CMD check results

There were no ERRORs or WARNINGs.

On CRAN r-devel-linux-x86_64-fedora-gcc there is a note:
   'installed size is 6.8Mb'.
The install size on different platforms varies significantly; from 1.42 MB (windows 10) to 6.8 MB on fedora (only the fedora build reports a size larger than 5 MB).

## Downstream dependencies

I have run R CMD check on downstream dependencies:
