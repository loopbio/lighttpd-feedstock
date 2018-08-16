About lighttpd
==============

Home: http://www.lighttpd.net/

Package license: BSD

Feedstock license: BSD 3-Clause

Summary: Light, fast web server

Lighttpd is rapidly redefining the efficiency of a webserver. It is
designed and optimized for high performance environments. With a small
memory footprint compared to other web-servers, effective management of
the cpu-load, and an advanced feature set, lighttpd is the perfect
solution for every server that is suffering load problems.


Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/loopbio/lighttpd-feedstock/master.svg?label=Linux)](https://circleci.com/gh/loopbio/lighttpd-feedstock)
[![OSX](https://img.shields.io/travis/loopbio/lighttpd-feedstock/master.svg?label=macOS)](https://travis-ci.org/loopbio/lighttpd-feedstock)
![Windows disabled](https://img.shields.io/badge/Windows-disabled-lightgrey.svg)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-lighttpd-green.svg)](https://anaconda.org/loopbio/lighttpd) | [![Conda Downloads](https://img.shields.io/conda/dn/loopbio/lighttpd.svg)](https://anaconda.org/loopbio/lighttpd) | [![Conda Version](https://img.shields.io/conda/vn/loopbio/lighttpd.svg)](https://anaconda.org/loopbio/lighttpd) | [![Conda Platforms](https://img.shields.io/conda/pn/loopbio/lighttpd.svg)](https://anaconda.org/loopbio/lighttpd) |

Installing lighttpd
===================

Installing `lighttpd` from the `loopbio` channel can be achieved by adding `loopbio` to your channels with:

```
conda config --add channels loopbio
```

Once the `loopbio` channel has been enabled, `lighttpd` can be installed with:

```
conda install lighttpd
```

It is possible to list all of the versions of `lighttpd` available on your platform with:

```
conda search lighttpd --channel loopbio
```




Updating lighttpd-feedstock
===========================

If you would like to improve the lighttpd recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`loopbio` channel, whereupon the built conda packages will be available for
everybody to install and use from the `loopbio` channel.
Note that all branches in the loopbio/lighttpd-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.
