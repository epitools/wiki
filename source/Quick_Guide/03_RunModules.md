###### [Home](Home)
---------------------------------------
## Run your first analysis module

EpiTools separates each analysis step in modules which can executed independently. Their order is given by the pipeline that the user wants to implement and execute on the particular set of images he acquired. Analysis modules can be called from the *Actions* menu in the menu bar. 


---------------------------------------
#### Run modules

1. Select a module to run from *Action* menu
2. In case the module requires any additional settings, you will be prompted with a windows where you will be able to specified the required settings. 
3. On analysis module completion, you will be able to visualise the results (if the module generates them) and you will see a new node in the *analysis workflow* tree.


---------------------------------------
#### Available modules in release 0.1b

1. [Projection](../Analysis_Modules/00_projection) 
2. [Registration](../Analysis_Modules/01_registration)
3. [Contrast Enhancement](../Analysis_Modules/02_clahe)
4. [Segmentation](../Analysis_Modules/03_segmentation) 
	* [Re-segmentation](../Analysis_Modules/03_segmentation)
5. [Polygon Masking](../Analysis_Modules/04_polygonMask)
6. [Tracking Correction](../Analysis_Modules/05_tracking)
7. [Skeleton generation](../Analysis_Modules/06_skeleton)

---------------------------------------
### Our instructions are too complicated? Are u lost? Watch our video tutorials!


1. <a href="https://www.dropbox.com/sh/wpezw6t7lma5d4f/AAD4QKHwtk61sgE2gxMLp0Vva#lh:null-03_Projection.mov" target="_blank">Projection tutorial movie</a>
2. <a href="https://www.dropbox.com/sh/wpezw6t7lma5d4f/AAD4QKHwtk61sgE2gxMLp0Vva#lh:null-04_Registration_Builtin.mov" target="_blank">Registration tutorial movie</a>
3. <a href="https://www.dropbox.com/sh/wpezw6t7lma5d4f/AAD4QKHwtk61sgE2gxMLp0Vva#lh:null-05_CLAHE.mov" target="_blank">Contrast Enhancement tutorial movie</a>
4. <a href="https://www.dropbox.com/sh/wpezw6t7lma5d4f/AAD4QKHwtk61sgE2gxMLp0Vva#lh:null-06_Segmentation.mov" target="_blank">Segmentation tutorial movie</a>
5. <a href="https://www.dropbox.com/sh/wpezw6t7lma5d4f/AAD4QKHwtk61sgE2gxMLp0Vva#lh:null-07_Tracking.mov" target="_blank">Tracking tutorial movie</a>
6. <a href="https://www.dropbox.com/sh/wpezw6t7lma5d4f/AAD4QKHwtk61sgE2gxMLp0Vva#lh:null-09_SkeletonGeneration.mov" target="_blank">Skeleton tutorial movie</a>


---------------------------------------

######  Do you think these informations are not enough to help you? Drop a line to the author and he will extend this tutorial asap!

###### This page was written by [Lorenzo Gatti](mailto:lorenzo.gatti.89@gmail.com) on 22.08.14@14.58


<script type="text/javascript" src="http://imls-bg-jira.uzh.ch:8080/s/dec35b3786a7548dc4b26192f22b864e-T/en_USbjk9py/64014/4/1.4.24/_/download/batch/com.atlassian.jira.collector.plugin.jira-issue-collector-plugin:issuecollector/com.atlassian.jira.collector.plugin.jira-issue-collector-plugin:issuecollector.js?locale=en-US&collectorId=dab092eb"></script>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-55332946-1', 'auto');
  ga('send', 'pageview');

</script>
