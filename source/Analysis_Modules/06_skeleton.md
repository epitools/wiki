#Skeleton Generation#

---------------------------------------
##Summary##
The cell label data structure is transformed into binary skeletons for every frame. A skeleton depicts the boundaries between cells with a white 1 pixel line (255) over black background (0). File format is PNG.

![Selective Plane Projection](../../Images/matlab/skeletonize.png)

---------------------------------------
##Assumptions##
The segmentation module needs to be run before this module

---------------------------------------
##Parameters##

`Parameter: Use Polygonal Mask`

* Allows to crop the skeletons before saving them by applying the polygonal mask created beforehand.
* *Additional requirement*: polygonal mask module

`Parameter: Use Corrected Segmentation`

* Allows to use the corrected segmentation results instead of the first segmentation results. 
* *Additional requirement*: Tracking & Re-Segmentation Module 

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