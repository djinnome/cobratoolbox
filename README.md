<p align="center">
  <img class="readme_logo" src="docs/source/_static/images/logos/logo.png" height="160px"/>
</p>

The COBRA Toolbox <br> COnstraint-Based Reconstruction and Analysis Toolbox
=======================================================================

<table>
  <tr>
    <td><div align="center"><a href="https://opencobra.github.io/cobratoolbox/latest"><img src="https://img.shields.io/badge/COBRA-docs-blue.svg?maxAge=0"></a></div></td>
    <td><div align="center"><a href="https://groups.google.com/forum/#!forum/cobra-toolbox"><img src="https://img.shields.io/badge/COBRA-forum-blue.svg?maxAge=0"></a></div></td>
    <td><div align="center"><a href="https://github.com/opencobra/cobratoolbox/tree/master/tutorials"><img src="https://img.shields.io/badge/COBRA-tutorials-blue.svg?maxAge=0"></div></td>
    <td><div align="center"><a href="https://codecov.io/gh/opencobra/cobratoolbox/branch/master"><img src="https://codecov.io/gh/opencobra/cobratoolbox/branch/master/graph/badge.svg?maxAge=0"></a></div></td>
    <td><div align="center"><img src="https://prince.lcsb.uni.lu/jenkins/userContent/codegrade.svg?maxAge=0" alt="Ratio of the number of inefficient code lines and the total number of lines of code (in percent). A: 0-3%, B: 3-6%, C: 6-9%, D: 9-12%, E: 12-15%, F: > 15%."></div></td>
  </tr>
  <tr>
    <th style="text-align:center">MATLAB R2016b</th>
    <th style="text-align:center">MATLAB R2015b</th>
    <th style="text-align:center">MATLAB R2014b</th>
    <th style="text-align:center" colspan="2">Code</th>
  </tr>
  <tr>
    <td><div align="center"><a href="https://prince.lcsb.uni.lu/jenkins/job/COBRAToolbox-branches-auto-linux/MATLAB_VER=R2016b/"><img src="https://prince.lcsb.uni.lu/jenkins/buildStatus/icon?job=COBRAToolbox-branches-auto-linux/MATLAB_VER=R2016b"></a></div></td>
    <td><div align="center"><a href="https://prince.lcsb.uni.lu/jenkins/job/COBRAToolbox-branches-auto-linux/MATLAB_VER=R2015b/"><img src="https://prince.lcsb.uni.lu/jenkins/buildStatus/icon?job=COBRAToolbox-branches-auto-linux/MATLAB_VER=R2015b"></a></div></td>
    <td><div align="center"><a href="https://prince.lcsb.uni.lu/jenkins/job/COBRAToolbox-branches-auto-linux/MATLAB_VER=R2014b/"><img src="https://prince.lcsb.uni.lu/jenkins/buildStatus/icon?job=COBRAToolbox-branches-auto-linux/MATLAB_VER=R2014b"></a></div></td>
    <td><div align="center"><img src="https://img.shields.io/badge/Windows-passing-brightgreen.svg?maxAge=0"></div></td>
    <td><div align="center"><img src="https://img.shields.io/badge/macOS-passing-brightgreen.svg?maxAge=0"></div></td>
  </tr>
</table>
<br>

System Requirements
-------------------

<img src="https://prince.lcsb.uni.lu/jenkins/userContent/warning.png" height="20px" alt="warning"> Please follow [this guide](https://opencobra.github.io/cobratoolbox/docs/requirements.html) in order to configure your system properly.

Solver Installation
-------------------

The default solver is `glpk` (for `LP` and `MILP`). You can install `TOMLAB`, `IBM ILOG CPLEX`, `GUROBI`, or `MOSEK` by following these **[detailed instructions](https://opencobra.github.io/cobratoolbox/docs/solvers.html)**.

Installation
------------

1. Download this repository (the folder `./cobratoolbox/` will be created). You can clone the repository using:
    ````bash
    $ git clone https://github.com/opencobra/cobratoolbox.git cobratoolbox
    ````
    <img src="https://prince.lcsb.uni.lu/jenkins/userContent/warning.png" height="20px" alt="warning"> Run this command in `Terminal` (on <img src="https://prince.lcsb.uni.lu/jenkins/userContent/apple.png" height="20px" alt="macOS"> and <img src="https://prince.lcsb.uni.lu/jenkins/userContent/linux.png" height="20px" alt="Linux">) or in `Git Bash` (on <img src="https://prince.lcsb.uni.lu/jenkins/userContent/windows.png" height="20px" alt="Windows">) - **not** in <img src="https://prince.lcsb.uni.lu/jenkins/userContent/matlab.png" height="20px" alt="Matlab">. Although not recommended, you can download the repository as a [compressed archive](https://github.com/opencobra/cobratoolbox/archive/master.zip).

2. Change to the folder `cobratoolbox/` and run from <img src="https://prince.lcsb.uni.lu/jenkins/userContent/matlab.png" height="20px" alt="Matlab">
    ````Matlab
    >> initCobraToolbox
    ````

3. You can test your installation by running from <img src="https://prince.lcsb.uni.lu/jenkins/userContent/matlab.png" height="20px" alt="Matlab">
    ````Matlab
    >> testAll
    ````

Tutorials
---------

All tutorials are included in the directory [/tutorials](https://github.com/opencobra/cobratoolbox/tree/master/tutorials). More tutorials are currently being prepared.

Support and Documentation
-------------------------

- The documentation is available [here](http://opencobra.github.io/cobratoolbox). This version is in development, but the legacy version of the documentation is  [here](http://opencobra.github.io/cobratoolbox/deprecated/docs/index.html).

- Answers to Frequently Asked Questions (**FAQ**) are [here](https://opencobra.github.io/cobratoolbox/docs/FAQ.html).

- If you need support, please feel free to post your question in our <a href="https://groups.google.com/forum/#!forum/cobra-toolbox"><img src="https://img.shields.io/badge/COBRA-forum-blue.svg"></a>.

How to contribute
-----------------

<img src="https://prince.lcsb.uni.lu/jenkins/userContent/thumbsUP.png" height="20px" alt="+1">  <img src="https://prince.lcsb.uni.lu/jenkins/userContent/tada.png" height="20px" alt="tada"> First off, thanks for taking the time to contribute to [The COBRA Toolbox](https://github.com/opencobra/cobratoolbox)! <img src="https://prince.lcsb.uni.lu/jenkins/userContent/tada.png" height="20px" alt="tada"> <img src="https://prince.lcsb.uni.lu/jenkins/userContent/thumbsUP.png" height="20px" alt="+1">

<p align="center">
<img src="https://raw.githubusercontent.com/opencobra/MATLAB.devTools/develop/assets/devTools_logo.png" height="120px"/>
</p>

You can install the [MATLAB.devTools](https://github.com/opencobra/MATLAB.devTools) from within MATLAB by typing:
```Matlab
>> installDevTools()
```

<img src="https://prince.lcsb.uni.lu/jenkins/userContent/bulb.png" height="20px" alt="bulb"> **Check out the [MATLAB.devTools](https://github.com/opencobra/MATLAB.devTools) - and contribute the smart way!**

- Please follow the [Style Guide](https://opencobra.github.io/cobratoolbox/docs/styleGuide.html).
- More information on writing a **test** is [here](https://opencobra.github.io/cobratoolbox/docs/testGuide.html) and a template is [here](https://opencobra.github.io/cobratoolbox/docs/testTemplate.html).
- More information on formatting the documentation is [here](https://opencobra.github.io/cobratoolbox/docs/documentationGuide.html)
- A guide for reporting an **issue** or submitting a **pull request (PR)** is [here](https://opencobra.github.io/cobratoolbox/docs/issueGuide.html).

If you want to use `git` via the command line interface and need help, these [training slides](https://uni-lu.github.io/slides/) will get you started. This [guide](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github) or the official [GitHub guide](https://help.github.com/articles/creating-a-pull-request/) also come in handy.

How to cite the COBRA Toolbox
-----------------------------

When citing the COBRA Toolbox, it is important to cite the original paper where an algorithm was first reported, as well as its implementation in the COBRA Toolbox. This is important, because the objective of the COBRA Toolbox is to amalgamate and integrate the functionality of a wide range of COBRA algorithms and this will be undermined if contributors of new algorithms do not get their fair share of citations. The following is one example how to approach this within the methods section of a paper (**not** the supplemental material please):

*To generate a context-specific model the FASTCORE algorithm [1], implemented in The COBRA Toolbox v3.0 [2], was employed.*

> [1] = Vlassis N, Pacheco MP, Sauter T (2014) Fast Reconstruction of Compact Context-Specific Metabolic Network Models. PLoS Comput Biol 10(1): e1003424.
>

> [2] Laurent Heirendt & Sylvain Arreckx, Thomas Pfau, Sebastian N. Mendoza, Anne Richelle, Almut Heinken, Hulda S. Haraldsdottir, Sarah M. Keating, Vanja Vlasov, Jacek Wachowiak, Stefania Magnusdottir, Chiam Yu Ng, German Preciat, Alise Zagare, Siu H.J. Chan, Maike K. Aurich, Catherine M. Clancy, Jennifer Modamio, John T. Sauls, Alberto Noronha, Aarash Bordbar, Benjamin Cousins, Diana C. El Assal, Susan Ghaderi, Masoud Ahookhosh, Marouen Ben Guebila, Inigo Apaolaza, Andrejs Kostromins, Hoai M. Le, Ding Ma, Yuekai Sun, Luis V. Valcarcel, Lin Wang, James T. Yurkovich, Phan T. Vuong, Lemmer P. El Assal, Scott Hinton, William A. Bryant, Francisco J. Aragon Artacho, Francisco J. Planes, Egils Stalidzans, Alejandro Maass, Santosh Vempala, Michael Hucka, Michael A. Saunders, Costas D. Maranas, Nathan E. Lewis, Thomas Sauter, Bernhard Ø. Palsson, Ines Thiele, Ronan M.T. Fleming, **Creation and analysis of biochemical constraint-based models: the COBRA Toolbox v3.0** (submitted), 2017.
>

Binaries and Compatibility
---------------------------

For convenience, we provide [`glpk_mex`](https://github.com/blegat/glpkmex) and [`libSBML-5.15+`](http://sbml.org/Software/libSBML) in `/external`.

[Binaries](https://github.com/opencobra/COBRA.binary) for these libraries are provided in a submodule for Mac OS X 10.6 or later (64-bit), GNU/Linux Ubuntu 14.0+ (64-bit), and Microsoft Windows 7+ (64-bit).
For unsupported OS, please refer to their respective building instructions ([`glpk_mex`](https://github.com/blegat/glpkmex#instructions-for-compiling-from-source), [`libSBML`](http://sbml.org/Software/libSBML/5.13.0/docs//cpp-api/libsbml-installation.html)).

Read more on the compatibility with SBML-FBCv2 [here](https://opencobra.github.io/cobratoolbox/docs/notes.html).

Disclaimer
----------

*The software provided by the openCOBRA Project is distributed under the GNU GPLv3 or later.  However, this software is designed for scientific research and as such may contain algorithms that are associated with patents in the U.S. and abroad.  If the user so chooses to use the software provided by the openCOBRA project for commercial endeavors then it is solely the user’s responsibility to license any patents that may exist and respond in full to any legal actions taken by the patent holder.*
