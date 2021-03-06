About criterion
===============

Home: https://github.com/Snaipe/Criterion

Package license: MIT

Feedstock license: [BSD-3-Clause](https://github.com/smutch/criterion-feedstock/blob/main/LICENSE.txt)

Summary: A cross-platform C and C++ unit testing framework for the 21st century

Development: https://github.com/Snaipe/Criterion

Documentation: http://criterion.readthedocs.org

A dead-simple, yet extensible, C and C++ unit testing framework.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/smutch/feedstock-builds/_build/latest?definitionId=3&branchName=main">
            <img src="https://dev.azure.com/smutch/feedstock-builds/_apis/build/status/criterion-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/smutch/feedstock-builds/_build/latest?definitionId=3&branchName=main">
                  <img src="https://dev.azure.com/smutch/feedstock-builds/_apis/build/status/criterion-feedstock?branchName=main&jobName=linux&configuration=linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64</td>
              <td>
                <a href="https://dev.azure.com/smutch/feedstock-builds/_build/latest?definitionId=3&branchName=main">
                  <img src="https://dev.azure.com/smutch/feedstock-builds/_apis/build/status/criterion-feedstock?branchName=main&jobName=linux&configuration=linux_aarch64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le</td>
              <td>
                <a href="https://dev.azure.com/smutch/feedstock-builds/_build/latest?definitionId=3&branchName=main">
                  <img src="https://dev.azure.com/smutch/feedstock-builds/_apis/build/status/criterion-feedstock?branchName=main&jobName=linux&configuration=linux_ppc64le_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/smutch/feedstock-builds/_build/latest?definitionId=3&branchName=main">
                  <img src="https://dev.azure.com/smutch/feedstock-builds/_apis/build/status/criterion-feedstock?branchName=main&jobName=osx&configuration=osx_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/smutch/feedstock-builds/_build/latest?definitionId=3&branchName=main">
                  <img src="https://dev.azure.com/smutch/feedstock-builds/_apis/build/status/criterion-feedstock?branchName=main&jobName=win&configuration=win_64_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-criterion-green.svg)](https://anaconda.org/smutch/criterion) | [![Conda Downloads](https://img.shields.io/conda/dn/smutch/criterion.svg)](https://anaconda.org/smutch/criterion) | [![Conda Version](https://img.shields.io/conda/vn/smutch/criterion.svg)](https://anaconda.org/smutch/criterion) | [![Conda Platforms](https://img.shields.io/conda/pn/smutch/criterion.svg)](https://anaconda.org/smutch/criterion) |

Installing criterion
====================

Installing `criterion` from the `smutch` channel can be achieved by adding `smutch` to your channels with:

```
conda config --add channels smutch
conda config --set channel_priority strict
```

Once the `smutch` channel has been enabled, `criterion` can be installed with:

```
conda install criterion
```

It is possible to list all of the versions of `criterion` available on your platform with:

```
conda search criterion --channel smutch
```




Updating criterion-feedstock
============================

If you would like to improve the criterion recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`smutch` channel, whereupon the built conda packages will be available for
everybody to install and use from the `smutch` channel.
Note that all branches in the smutch/criterion-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@smutch](https://github.com/smutch/)

