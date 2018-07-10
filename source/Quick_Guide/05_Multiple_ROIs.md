# Step-by-Step guide to export skeletons from multiple ROIs


---------------------------------------
## Summary
Starting from the beta release [**2.1.13-NightBuilds-75**](http://imls-bg-arthemis.uzh.ch/epitools/files/epitools_matlab_experimental/epitools-dev-2.1.13-NightBuilds-75.tar.gz) you can export skeletons of different ROIs taken on the image you processed with EpiTools.

---------------------------------------
## How-to

1. Execute **Polygon mask (ROI)** [1]  
	
	a. Define the 1st cropping area
	
	a. A new tag will appear in the default pool	
	
2. Execute **Polygon mask (ROI)** [2]
	
	a. Specify the [comparative mode] execution 
	
	a. A new pool will appear in the list of available pools
	
	b. Define the 2nd cropping area
	
	a. A new tag will appear in the new pool


3. Exporting image skeletons using the **1st polygon mask**:
    
    1. Select “**Generate skeletons**” from the analysis menu
    
    2. The program will ask to move back to the default poll, click **[Ok]**
    
    3. Select “**Use Polygon crop**” from the popup window
    
    4. Your skeletons will be exported in the analysis folder under the [skeletons] subfolder


4. Exporting image skeletons using the **2nd polygon mask**:
    
    1. Click on **[Manage active pools]** from the toolbar ![Export an ovlerlay](../Images/book_addresses.png) 
    
    2. Select the second temporary pool from the list of available pool.
    
    3. Select “**Generate skeletons**” from the analysis menu
    
    4. The program will ask in which modality you want to execute the action, select **[overwrite module]**
    
    5. The program will ask to move back to the default poll, answer **[No]**
    
    6. Select “**Use Polygon crop**” from the popup window
    
    7. Your skeletons will be exported in the analysis folder in the *[skeleton_current.timestamp]* subfolder


---------------------------------------
######  Do you think these informations are not enough to help you? Drop a line to the author and he will extend this tutorial asap!

###### This page was written by [Lorenzo Gatti](mailto:lorenzo.gatti@alumni.ethz.ch) on 10.04.16@11:45



<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-55332946-1', 'auto');
  ga('send', 'pageview');

</script>
