# Registration of Time Series #

---------------------------------------
##Summary##
If the sample is characterized by movement during the acquisition the time series can be corrected by aligning successive frames to the first.

![Selective Plane Projection](../Images/matlab/registration.png)

---------------------------------------
##Assumptions##
The method assumes a 2D time series as input

---------------------------------------
##Options##

`Parameter: StackReg`

* Sends the time series to imageJ where the plugin StackReg is applied with a 'rigid' transformation model.
* Rigid: only translation or rotations i.e. no scaling
* **Attention:** make sure to allocate enough Java Heap Space in Matlab to be able to process the image
* Reference:
	* A Pyramid Approach to Subpixel Registration Based on Intensity P. Thévenaz, U.E. Ruttimann, M. Unser IEEE Transactions on Image Processing, vol. 7, no. 1, pp. 27-41, January 1998.
	* [StackReg website](http://bigwww.epfl.ch/thevenaz/stackreg/)

`Parameter: EpiTools's registration [beta]`

* This experimental registration method aligns the images in two steps:
	1. registration based on big features
	2. correction based on small features

---------------------------------------
######  Do you think these informations are not enough to help you? Drop a line to the author and he will extend this tutorial asap!

###### This page was written by [Davide Heller](mailto:davide.heller@imls.uzh.ch) on 10.09.14@17.08


<script type="text/javascript" src="http://imls-bg-jira.uzh.ch:8080/s/dec35b3786a7548dc4b26192f22b864e-T/en_USbjk9py/64014/4/1.4.24/_/download/batch/com.atlassian.jira.collector.plugin.jira-issue-collector-plugin:issuecollector/com.atlassian.jira.collector.plugin.jira-issue-collector-plugin:issuecollector.js?locale=en-US&collectorId=dab092eb"></script>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-55332946-1', 'auto');
  ga('send', 'pageview');

</script>
