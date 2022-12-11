About qt-tools
==============

Home: http://qt-project.org

Package license: LGPL-3.0-only

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/qt-tools-feedstock/blob/main/LICENSE.txt)

Summary: qttools Qt is a cross-platform application and UI framework.

Development: https://github.com/qt/qttools

Documentation: http://doc.qt.io/

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/qt-tools-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/qt-tools-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/qt-tools-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/qt-tools-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_ppc64le_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/qt-tools-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/qt-tools-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/qt-tools-feedstock?branchName=main&jobName=win&configuration=win%20win_64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-qt--tools-green.svg)](https://anaconda.org/qtforge/qt-tools) | [![Conda Downloads](https://img.shields.io/conda/dn/qtforge/qt-tools.svg)](https://anaconda.org/qtforge/qt-tools) | [![Conda Version](https://img.shields.io/conda/vn/qtforge/qt-tools.svg)](https://anaconda.org/qtforge/qt-tools) | [![Conda Platforms](https://img.shields.io/conda/pn/qtforge/qt-tools.svg)](https://anaconda.org/qtforge/qt-tools) |

Installing qt-tools
===================

Installing `qt-tools` from the `qtforge` channel can be achieved by adding `qtforge` to your channels with:

```
conda config --add channels qtforge
conda config --set channel_priority strict
```

Once the `qtforge` channel has been enabled, `qt-tools` can be installed with `conda`:

```
conda install qt-tools
```

or with `mamba`:

```
mamba install qt-tools
```

It is possible to list all of the versions of `qt-tools` available on your platform with `conda`:

```
conda search qt-tools --channel qtforge
```

or with `mamba`:

```
mamba search qt-tools --channel qtforge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search qt-tools --channel qtforge

# List packages depending on `qt-tools`:
mamba repoquery whoneeds qt-tools --channel qtforge

# List dependencies of `qt-tools`:
mamba repoquery depends qt-tools --channel qtforge
```




Updating qt-tools-feedstock
===========================

If you would like to improve the qt-tools recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`qtforge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `qtforge` channel.
Note that all branches in the conda-forge/qt-tools-feedstock are
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

* [@conda-forge/qt-main](https://github.com/conda-forge/qt-main/)

