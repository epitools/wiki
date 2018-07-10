#Contrast limited adaptive histogram equalization#

---------------------------------------
##Summary##
Applies the matlab command **adapthisteq**®  to reduce contrast differences throughout  
the image. From the matlab documentation:

> CLAHE operates on small regions in the image, called tiles, rather than the entire image. Each tile's contrast is enhanced, so that the histogram of the output region approximately matches the histogram specified by the 'Distribution' parameter. The neighboring tiles are then combined using bilinear interpolation to eliminate artificially induced boundaries. The contrast, especially in homogeneous areas, can be limited to avoid amplifying any noise that might be present in the image

![Selective Plane Projection](../Images/matlab/clahe.png)

---------------------------------------
##Assumptions##
The method assumes 2D images in grayscale

---------------------------------------
##Parameters##

`Parameter: Enhancement limit`

* Real scalar in the range [0 1] that specifies a contrast enhancement limit. Higher numbers result in more contrast.
* *units* [positive real value]  
* *recommended range*: [0.01 0.05]

`Parameter: Enhancement width`

* Discribes the size of the tiles used by the clahe method
* *units* [pixels]  
* *recommended range* [20 30]  

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
