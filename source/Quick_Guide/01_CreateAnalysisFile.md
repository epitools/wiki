###### [Home](Home)
---------------------------------------

# Create a new analysis file #

EpiTools stores all the data associated with your analysis session in an XML file which can be accessed in writing and reading mode with any kind of xml IDE or text editors. 


## How to create a new analysis file ##

---------------------------------------
#### Create from EpiTools interface ####

Any new analysis generated from EpiTools interface is the result of a guided process where the user fills all the required informations via the GUI interface provided. The content of the analysis file defines completely the structure of the analysis and it guarantees its reproducibility.

1. From the main EpiTools interface, click on *File>New Analysis*.
2. Specify the path where the analysis file will be saved.
3. Specify the path where the images have been stored.
4. Give a memorisable name and assign a version to the analysis you are currently building.
5. If you can see all the image files you have stored in the folder specified at point 3, then press Confirm and Continue



#### Add specifics on loaded image files ####

EpiTools gives the user the control on which files and on which data subset run the analysis.


1. From the main EpiTools interface, click on *File>File Properties*.
2. You will see a table showing the image files that have been found in the image directory.
3. The following columns can be modified by the user in order to restrict the analysis only to a certain subset of the images.
	* **Include?** : This is a boolean control which is by default set to true 
	
			i.e. all the files with a tick in this box will be used for the current analysis
	
	* **Z planes?** : 	This control specifies the index of the z planes to include in the analysis process 
					
			i.e. [1,2-6,8-10,12] will result in including planes 1,2,3,4,5,6,8,9,10,12
					
	* **Channel?** : 	This control specifies the index of the channels to include in the analysis process 
					
			i.e. [1-2] will result in including channels 1,2
				
	* **Time points?** : This control specifies the index of the time points to include in the analysis process 
						
			i.e. [1,2-6,8-10,12] will result in including time points 1,2,3,4,5,6,8,9,10,12

4. You can propagate the informations stored in a single cell in a particular column of the table to all the column or a limited subset of the cells simply following this procedure:

* Select with the left click of the mouse the first cell you want the value to propagate to.
* Hold CAPS.
* Select with the left click of the mouse the last cell you want the value to propagate to.
* Write the new value in the last cell.
* Press ENTER.

---------------------------------------
### Our instructions are too complicated? Are u lost? Watch our video tutorials!

1. <a href="https://www.dropbox.com/sh/wpezw6t7lma5d4f/AAD4QKHwtk61sgE2gxMLp0Vva#lh:null-01_NewAnalysis.mov" target="_blank">Create analysis tutorial movie</a>

2. <a href="https://www.dropbox.com/sh/wpezw6t7lma5d4f/AAD4QKHwtk61sgE2gxMLp0Vva#lh:null-02_SettingImageProperties.mov" target="_blank">Set properties on image file tutorial movie</a>


---------------------------------------

######  Do you think these informations are not enough to help you? Drop a line to the author and he will extend this tutorial asap!

###### This page was written by [Lorenzo Gatti](mailto:lorenzo.gatti.89@gmail.com) on 22.08.14@15.41


<script type="text/javascript" src="http://imls-bg-jira.uzh.ch:8080/s/dec35b3786a7548dc4b26192f22b864e-T/en_USbjk9py/64014/4/1.4.24/_/download/batch/com.atlassian.jira.collector.plugin.jira-issue-collector-plugin:issuecollector/com.atlassian.jira.collector.plugin.jira-issue-collector-plugin:issuecollector.js?locale=en-US&collectorId=dab092eb"></script>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-55332946-1', 'auto');
  ga('send', 'pageview');

</script>
