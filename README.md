About alchemlyb-feedstock
=========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/alchemlyb-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/alchemistry/alchemlyb

Package license: BSD-3-Clause

Summary: the simple alchemistry library

Development: https://github.com/alchemistry/alchemlyb

Documentation: https://alchemlyb.readthedocs.io/

alchemlyb is an open-source Python software package for
the analysis of alchemical free energy calculations. Its
functionality contains individual composable building
blocks for all aspects of a full typical free energy
analysis workflow, starting with the extraction of raw
data from the output of diverse molecular simulation
packages, moving on to data preprocessing tasks such as
decorrelation of time series, using various estimators to
derive free energy estimates from simulation samples, and
finally providing quality analysis tools for data
convergence checking and visualization. alchemlyb also
contains high-level end-to-end workflows that combine
multiple building blocks into a user-friendly analysis
pipeline from the initial data input stage to the final
results.


Current build status
====================


<table><tr>
    <td>GitHub Actions</td>
    <td>
      <a href="https://github.com/conda-forge/alchemlyb-feedstock/actions/workflows/conda-build.yml">
        <img src="https://github.com/conda-forge/alchemlyb-feedstock/actions/workflows/conda-build.yml/badge.svg?event=push&branch=main">
      </a>
    </td>
  </tr>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=16170&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/alchemlyb-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>osx_64_acceleratorcorepython3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=16170&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/alchemlyb-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_acceleratorcorepython3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_acceleratorcorepython3.12.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=16170&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/alchemlyb-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_acceleratorcorepython3.12.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_acceleratorcorepython3.13.____cp313</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=16170&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/alchemlyb-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_acceleratorcorepython3.13.____cp313" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_acceleratorcorepython3.14.____cp314</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=16170&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/alchemlyb-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_acceleratorcorepython3.14.____cp314" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_acceleratorcorepython3.15.____cp315</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=16170&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/alchemlyb-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_acceleratorcorepython3.15.____cp315" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_acceleratorjaxpython3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=16170&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/alchemlyb-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_acceleratorjaxpython3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_acceleratorjaxpython3.12.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=16170&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/alchemlyb-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_acceleratorjaxpython3.12.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_acceleratorjaxpython3.13.____cp313</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=16170&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/alchemlyb-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_acceleratorjaxpython3.13.____cp313" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_acceleratorjaxpython3.14.____cp314</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=16170&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/alchemlyb-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_acceleratorjaxpython3.14.____cp314" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_acceleratorjaxpython3.15.____cp315</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=16170&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/alchemlyb-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_acceleratorjaxpython3.15.____cp315" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-alchemlyb-green.svg)](https://anaconda.org/conda-forge/alchemlyb) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/alchemlyb.svg)](https://anaconda.org/conda-forge/alchemlyb) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/alchemlyb.svg)](https://anaconda.org/conda-forge/alchemlyb) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/alchemlyb.svg)](https://anaconda.org/conda-forge/alchemlyb) |

Installing alchemlyb
====================

Installing `alchemlyb` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

How to use
----------

<details>
<summary>With conda</summary>

```
conda install alchemlyb
```

</details>

<details>
<summary>With mamba</summary>

```
mamba install alchemlyb
```

</details>

<details>
<summary>With pixi</summary>

```
# for adding to your local project
pixi add alchemlyb
# for installing globally
pixi global install alchemlyb
```

</details>

Search package versions
-----------------------

It is possible to list all of the versions of `alchemlyb` available on your platform:

<details>
<summary>With conda</summary>

```
conda search alchemlyb --channel conda-forge
```

</details>

<details>
<summary>With mamba</summary>

```
mamba search alchemlyb --channel conda-forge
```

</details>

<details>
<summary>With pixi</summary>

```
pixi search alchemlyb --channel conda-forge
```

</details>

<details>
<summary>With mamba repoquery, which may provide more information</summary>

```
# Search all versions available on your platform:
mamba repoquery search alchemlyb --channel conda-forge

# List packages depending on `alchemlyb`:
mamba repoquery whoneeds alchemlyb --channel conda-forge

# List dependencies of `alchemlyb`:
mamba repoquery depends alchemlyb --channel conda-forge
```

</details>



About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/) and [GitHub](https://github.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance,
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information, please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating alchemlyb-feedstock
============================

If you would like to improve the alchemlyb recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/alchemlyb-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@jan-janssen](https://github.com/jan-janssen/)
* [@orbeckst](https://github.com/orbeckst/)
* [@xiki-tempula](https://github.com/xiki-tempula/)

