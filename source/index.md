![EpiTools logo by Lorenzo Gatti](Images/logo.png)


# Welcome to Epitools
---

Here we present a new software toolkit to extract the membrane signal from epithelial tissues and analyze it with the aid of computer vision. The development of EpiTools was inspired by the challenges in analyzing time-lapses of growing Drosophila imaginal discs. The folded morphology, the very small apical cell surfaces and the long time series required a new automated cell recognition to accurately study growth dynamics.

**EpiTools is composed of two main software projects to allow extended modularity**

First **an image processing application for MATLAB** to extract the membrane outlines from the experimental data, featuring:

* [Adaptive surface projection](Analysis_Modules/00_projection)
* [A Region growing segmentation algorithm with selective seeding](Analysis_Modules/03_segmentation)
* [Assisted Seed Correction for expert input](Analysis_Modules/05_tracking)
* [An advanced GUI for a guided & reproducible analysis](Quick_Guide/01_CreateAnalysisFile)

Second **a plugin collection for the <a href="http://icy.bioimageanalysis.org" target="_blank">bioimaging platform icy</a>** to interactively analyze the skeleton files, featuring:

* [A network based java data-structure to semantically describe the tissue](Icy_Plugins/02_CellGraph)
* [Automatic estraction & display of development features](Icy_Plugins/01_CellOverlay) including:
	* Divisions and Eliminations
	* Junction rearragements (T1,T2)
	* Cell Elongation Patterns
* [Numerous Export options including Spreadsheets, GraphML and Vector Graphics](Icy_Plugins/03_CellExport)
* [Visualization and measurement of the estimated 3D gridfit surface](Icy_Plugins/05_CellSurface)
* [Clone detection based on a secondary channel](Icy_Plugins/06_CellClone)

Our projects are pulished with Open source licenses. Follow us on BitBucket!

EpiTools was published in Developmental Cell (January 2016), freely available at [http://dx.doi.org/10.1016/j.devcel.2015.12.012](http://dx.doi.org/10.1016/j.devcel.2015.12.012)


## News
---
	2018-11-06 GUI-Independent EpiTools MATLAB modules
	* added projection module at github.com/epitools/module_projection
	* added segmentation module at github.com/epitools/module_segmentation 

	2018-07-26 EpiTools Icy Plugins v0.9.1
	* IMPORTANT Bugfix for EDGE_COLOR_TAG, the length measure in the CSV export was reported incorrectly
	* new CELL_CLONE overlay (see CellClone page under Icy plugins) to interactively detect clones
	* new CELL_INTENSITY overlay to measure the junction intensity for all cells
	* more details in the github release page
	
	2018-07-10 EpiTools Project moved to Github!
	* new website address: epitools.github.io
	* new repository: github.com/epitools
	* download sections are now pointing to the release tab of each repository
	* example datasets can be found in the epitools-samples repository

View older news [here](Support/Latest_News).

## Downloads
---


MATLAB Application | ICY Plugins        
---|---
<a href="https://github.com/epitools/epitools-matlab/releases"><img border="0" alt="Epitools for Matlab v2" src="Images/download_matlab_v2.png"></a> | <a href="https://github.com/epitools/epitools-icy/releases"><img border="0" alt="Epitools for Icy" src="Images/download_icy_plugins.png"></a> 
[MATLAB source code](https://github.com/epitools/epitools-matlab) | [Plugins surce code](https://github.com/epitools/epitools-icy) |

**For best compatability we reccomend using Matlab 2014a**

visit our [F.A.Q. section](Support/FAQ) for more details on the topic.


EpiTools is licensed under GPLv3 you can find the details [here](Support/Software_License).

## Video Tutorials
---

<a href="https://epitools-eu-central-1-088391093549-movies.s3-eu-west-1.amazonaws.com/index.html" target="_blank">EpiTools v2 Video Tutorials</a> 

<a href="https://www.dropbox.com/sh/q99vbi39ag8cwgw/AAC8W4gkb_e-T0BtCxPOXc8ga?dl=0" target="_blank">Icy Plugin Tutorials (with audio!)</a>

Make sure to download them to enjoy the HD quality 
*(click on the dots in the lower right corner and click download).*

## Who built EpiTools? 
---

##### Authors

* Davide Heller (1)
* Alexander Tournier (5)
* Andreas Hoppe (2)
* Simon Restrepo (1)
* Lorenzo Gatti (1,3,4)
* Nicolas Tapon (5)
* Konrad Basler (1)
* Yanlan Mao (6)

##### Affiliations

1. Institute of Molecular Life Sciences, University of Zurich, Switzerland
2. Digital Imaging Research Centre, Faculty of Science, Engineering and Computing, Kingston University, Kingston-upon-Thames, KT1 2EE, United Kingdom.
3. Institute of Applied Simulations, Zürich University of Applied Sciences, Einsiedlerstrasse 31a, 8820 Wädenswil, Switzerland
4. SIB Swiss Institute of Bioinformatics, Quartier Sorge - Batiment Genopode, 1015 Lausanne, Switzerland
5. Apoptosis and Proliferation Control Laboratory, Cancer Research UK, London Research Institute, 44 Lincoln's Inn Fields, London, WC2A 3LY, United Kingdom. 
6. MRC Laboratory for Molecular Cell Biology, University College London, Gower Street, London WC1E 6BT, United Kingdom

## How to cite EpiTools
---

Davide Heller, Andreas Hoppe, Simon Restrepo, Lorenzo Gatti, Alexander L. Tournier, Nicolas Tapon, Konrad Basler, and Yanlan Mao (2016). *EpiTools: An Open-Source Image Analysis Toolkit for Quantifying Epithelial Growth Dynamics*. Developmental Cell 36 (1) (January): 103–116. [doi:10.1016/j.devcel.2015.12.012](http://dx.doi.org/10.1016/j.devcel.2015.12.012)

	
## Screenshots
---

_Matlab Application v2_

![Matlab Stable V2](Images/interface_v2.png)

_Icy Plugins_

![Icy Plugins V1](Images/interface_icy.png)

---------------------------------------
## Support

* In case of bugs or improvement suggestions feel free to:
    * File an issue on the relative github repository ([icy](https://github.com/epitools/epitools-icy/issues) or [matlab](https://github.com/epitools/epitools-matlab/issues)) .
    * Write to [Yanlan Mao](mailto:y.mao@ucl.ac.uk?Subject=EpiTools)
    * Write to [Davide Heller](mailto:davide.heller@imls.uzh.ch?Subject=EpiTools)
    * Write to [Lorenzo Gatti](mailto:lorenzo.gatti@uzh.ch?Subject=EpiTools)

We use Google Analytics to study the traffic of this website. Please find information about the data usage [here](http://www.google.com/policies/privacy/partners/).

---------------------------------------
###### This page was written by [Lorenzo Gatti](mailto:lorenzo.gatti.89@gmail.com) and [Davide Heller](mailto:davide.heller@imls.uzh.ch) on 26.08.14@16:57

<!-- This contains the hidden content for inline calls -->

<script>
(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
})(window,document,'script','//www.google-analytics.com/analytics.js','ga');

ga('create', 'UA-55332946-1', 'auto');
ga('send', 'pageview');
</script>
