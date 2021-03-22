About intake
============

Home: https://github.com/intake/intake

Package license: BSD-2-Clause

Feedstock license: [BSD-3-Clause](https://github.com/nsls-ii-forge/intake-feedstock/blob/master/LICENSE.txt)

Summary: Data load and catalog system

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=188&branchName=master">
        <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/intake-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-intake-green.svg)](https://anaconda.org/nsls2forge/intake) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/intake.svg)](https://anaconda.org/nsls2forge/intake) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/intake.svg)](https://anaconda.org/nsls2forge/intake) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/intake.svg)](https://anaconda.org/nsls2forge/intake) |

Installing intake
=================

Installing `intake` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `intake` can be installed with:

```
conda install intake
```

It is possible to list all of the versions of `intake` available on your platform with:

```
conda search intake --channel nsls2forge
```




Updating intake-feedstock
=========================

If you would like to improve the intake recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/intake-feedstock are
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


