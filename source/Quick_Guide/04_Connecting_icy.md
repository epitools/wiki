#Visualize results in icy#

---------------------------------------
##Summary##
Use the bio-imaging software [icy](http://icy.bioimageanalysis.org) to display the output of every module.

---------------------------------------
##Setup##

### 1. In Icy

* install the following plugins
	* [matlab communicator plugin](http://icy.bioimageanalysis.org/plugin/Matlab_communicator) by Yoann Le Montagner
	* [matlab X Server](http://icy.bioimageanalysis.org/plugin/Matlab_X_server) by Yoann Le Montagner
	

### 2. In EpiTools
* Open icy in background
* Click on the eye logo in the menu bar of EpiTools
	* locate your icy plugin folder to detect the _matlab communicator plugin_
	* e.g. applications/icy/plugins/ylemontag/matlabcommunicator

The connection with icy is now established. If you already opened an analysis you can test the connection by right-clicking the projection-module and clicking visualize results. The projected image should now appear as sequence in icy.

![SourceTree_BranchCheckout](../Images/matlab/send_to_icy.png)

---------------------------------------
######  Do you think these informations are not enough to help you? Drop a line to the author and he will extend this tutorial asap!

###### This page was written by [Davide Heller](mailto:davide.heller@imls.uzh.ch) on 30.09.14@18:10



<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-55332946-1', 'auto');
  ga('send', 'pageview');

</script>
