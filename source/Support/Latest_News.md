# Support
---------------------------------------

In this section you will find information about new software updates and what changes they include.

----

### Latest news

	2016-04-22 EpiTools Icy Plugins v0.8.9
	* Added layer option panel for CellEditor with buttons to confirm or undo modifications
	* Added the possibility to Convert icy ROIs like rectangles&squares to CellColorTag
	* Added an import functionality for CellColorTag to use previous tags
	* Fixed missing labeling of excel sheets in EdgeColorTag
	
	2016-02-09 EpiTools Matlab: Parallel Computing Support
	* Due to a software regression the parallel computing capabilities are currently broken.
	  As consequence, please do not increase the number of processors in the input GUI.
	  We hope to re-add the support in the next release!
	* We added an FAQ section to the wiki [Support > Faq] for reported problems

	2015-12-15 EpiTools Icy Plugins v0.8.8
	* Fixed excel sheet export on EDGE_INTENSITY overlay (for single time points output file would be empty)
	* Fixed relative intensity option in EDGE_INTENSITY overlay (error on icy >= 1.7) 

	2015-12-03 EpiTools license change and Compatibility on OSX 10.11
	* EpiTools is now licensed with GPLv3 to comply with all dependencies
	* OSX 10.11 El Capitan: When starting a new analysis, file choice windows
	  lack titles but functionality is preserved. We are working on a solution.

	2015-11-11 EpiTools Matlab v2.1.5
	* Projection module: surface files containing the 2nd gridfit estimation are now saved

	2015-11-11 EpiTools Icy Plugins v0.8.7
	* New Plugin: CellSurface to visualize the gridfit surface estimation from EpiTools for Matlab
	* New Overlay: Cell Projection colors every cell by the z-component through the gridfit estimation
	* Added option to automatically read all available time points for CellGraph
	* Developer: Added Test Overlay example overlay to experiment new ideas with ease.
	* Toolbar update: to add the icon of CellSurface to the EpiTools bar please update the Workspace file
	
	2015-10-12 EpiTools Icy Plugins v0.8.6
	* Added edge geometry selection mode in EdgeColorTag overlay: exclude, include or select the vertex geometry
	* Added option to analyze entire time-series in EdgeIntensity overlay
	* Added option to select channel to measure in EdgeColorTag and EdgeIntensity
	* Added cell major and minor axis data in XLS export for EdgeOrientation overlay
	* Developer: eclipse project files was added to git repository to allow easier import
	* Fix: Crash when attempting to put sequence with stGraph overlays into 3DVTK mode
	
	2015-08-10 EpiTools Icy Plugins v0.8.5
	* Added EdgeOrientation Plugin to retrieve the orientation of edges
	* Added Summary statics option for Intensity readout: Mean, Max, Min, SD, Sum
	
	2015-06-02 EpiTools Icy Plugins v0.8.4
	* All color gradient overlays now use the optionPanel for gradient control
	* Better description for Gradient controls in optionPanel
	* Fixed normalization procedure for color gradient, i.e (x - min)/(max - min) instead of (x - min)/max

	2015-06-01 EpiTools Icy Plugins v0.8.3
	* Changed default behavior of excluding outer most segmentation border on input
	* Changed default border exclusion behavior when LOAD_CSV_TRACKING option is used 

	2015-05-29 EpiTools Icy Plugins v0.8.2
	* Trial gradient control for Area Gradient Overlay from OptionLayerMenu instead of plugin
	* Updated to final MIT license

	2015-05-22 EpiTools Icy Plugins v0.8.1
	* Major code refactoring and documentation for upcoming release
	* Added icons to the plugins, to enable these please substitute the entire davhelle folder

	2015-04-29 EpiTools Icy Plugins v0.8.0
	* Added Legends for all overlays with hide/show option in the layer options menu
	* IntensityOverlay: added raw option and adjustable buffer
	* Removed MOSAIC tracking algorithm because of deprecated support
	* Expanded clicking area for EdgeMarker
	
	17 Apr 2015 07:54 (GMT +2:00)
	The latest Matlab versions 2014b and 2015a present some issues
	due the new graphics environment. We currently cannot guarantee 
	full compatability. We reccomend using 2014a if you have access 
	to it.
	
	For Command line use we recommend using version 1 stable. 
	A sample script can be found in the main folder.
	
	2015-04-13 EpiTools Icy Plugins v0.7.9
	* Bug-fix for folder selection in CellExport causing UIthreading Violation

	2015-04-11 EpiTools Icy Plugins v0.7.8
	* CellGraph gui simplification, no need to specify skeleton type anymore
	* CellExport now contains the WKT and CSV save option previously contained in CellGraph
	* CellExport can export the current graph as TIFF skeleton files compatible with CellEditor

	2015-04-10 EpiTools Icy Plugins v0.7.7
	* Removed deprecated internal wiki which was making the archive unnecessarily big

	2015-04-10 EpiTools Icy Plugins v0.7.6
	* Changed overlay names in CellOverlay for a better overview
	* Added EdgeTag Overlay to follow selected Edges over time and color code them as for CellTag. Export also measure intensity of underlying image

	2015-03-30 EpiTools Icy Plugins v0.7.5
	* Bug fix for PdfPrinter when selecting a frame no which is not in the graph but in the image sequence
	* CellFinder updated with better GUI description

	2015-03-27 EpiTools Icy Plugins v0.7.4
	* Solved ellipseFitter bug due to hardcoded image size parameters

	2015-03-27 EpiTools Icy Plugins v0.7.3
	* DivisionOrientation was extended with GUI commands to set the start/length of avg.
	* small changes in overlay names, e.g. CELL_OVERLAY -> CELL_OUTLINE

	2015-03-26 EpiTools Icy Plugins v0.7.2
	* CellTag/CellMarker now propagates the click through all cells for visual help
	* CellGraph now takes any file name without requirements when t is 1 (single time point)
	* Cell_Displacement overlay has now its own menu and colors are explained
	* Cell_Tracking overlay menu contains color code explanation
	* Divisions and Elimination submenu was updated. Co-occurences of eliminations and divisions are now magenta (previously yellow) and are shown from the first frame onwards.

	2015-03-25 EpiTools Icy Plugins v0.7.1
	* PdfPrinter: export a vector graphic from all currently added Overlays to the image
	* CellMarkerOverlay now exports more fields including elongation and division
	* added Always_tracked_cells Overlay to visualize in Orange continuously tracked cells

	2015-03-24 EpiTools Icy Plugins v0.7.0
	* CellEditor: re-implemented, now independent of painter plugin and easier to use
	* CellExporter: new plugin collecting export options such as a single XLS file and GraphML
	* CellOverlay: adapted all overlays to support the side panel XLS export option
	* General GUI improvements to simplify and guide usage

	-------------------------------------------------------
	19 Dec 2014 07:54 (GMT +2:00)
	We are pleased to announce the release of the EpiTools 2.0 (beta version). 
	Due to current coding phase, this release is still under development and 
	it should be used only for testing. Keep us posted with your feedbacks, 
	bug reports and suggestions. This is the last release for this year!
	EpiTools team wishes you all a Merry Christmas and Happy New Year 2015. 
	
	-------------------------------------------------------
	14 Nov 2014 15:11 (GMT +2:00)
	EpiTools Tracking interface does not respond to user inputs with the latest 
	version of MATLAB 2014b. We are currently working to solve this problem. 
	In order to select a previous version of MATLAB installed on your machine, 
	change the following line in the launcher (linux/mac):

	from 

	last_installation=${installation_directories[$tLen-1]}

	to

	last_installation=${installation_directories[$tLen-2]} 

	-------------------------------------------------------

	2 Oct 2014 11:34 (GMT +2:00)
	Due to a bug affecting user preferences saving and reading, we just uplaod 
	a new HOTFIX-94c557a.  In order to make it works, in case you have downloaded 
	EpiTools before 2 Oct, please download it again or pull the update from git.
	Remove .usersettings.xml or usersettings.xml from epitools/src folder. 
	Restart EpiTools.




---------------------------------------

######  Do you think these informations are not enough to help you? Drop a line to the author and he will extend this tutorial asap!

###### This page was written by [Lorenzo Gatti](mailto:lorenzo.gatti.89@gmail.com) and [Davide Heller](mailto:davide.heller@imls.uzh.ch) on 22.04.16@15.41


<script type="text/javascript" src="http://imls-bg-jira.uzh.ch:8080/s/dec35b3786a7548dc4b26192f22b864e-T/en_USbjk9py/64014/4/1.4.24/_/download/batch/com.atlassian.jira.collector.plugin.jira-issue-collector-plugin:issuecollector/com.atlassian.jira.collector.plugin.jira-issue-collector-plugin:issuecollector.js?locale=en-US&collectorId=dab092eb"></script>


<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-55332946-1', 'auto');
  ga('send', 'pageview');

</script>