# Pareto-Releases
Here you will find release notes and updates.  The latest release is listed first.  

cynthia@sio2graphs.com  
www.sio2graphs.com  
easy, effective, aesthetic  

## v8.0.0.1 Certified
###### Published 4/2024  
Fixes the display of a blank screen, not the landing page with the sio2Graphs logo, on the passing of a blank or null to the Categories well.  
###### Updates
This will not be a disruptive release, as there are almost no changes to the underlying code.<br /><br />
0 Major Changes<br />
0 Minor Changes<br />
0 Maintenance Improvements<br />
#### 1 Bug Fix
Corrected for the passing of null or blank into a category.

## v8.0.0.0 Certified
###### Published 3/2024  
If your visual displays a blank screen, not the landing page with the sio2Graphs logo, please remove all nulls, blanks, and control characters from your data, pass only valid text categories to fix the issue.  A fix is being published now.

If you can see the landing page or formatting selections are not applying properly, this has to do with the publishing process. Apologies for any inconvenience.  I recently upgraded to version 8.0.0.0, which required a large portion of the supporting and direct code to be either changed or updated.  It is a major change, and some of the formatting will have to be re-applied.  For example, label rotation and stacking because these two formatting options were condensed.  

To correct any issues, please make sure you have the latest version of both the PBI Desktop and service for Pareto 8.0.0.0.  You have to re-download “Pareto for sio2Graphs” and confirm the version by right clicking the graph icon and looking at “about”. You might also have to click off of “Pareto” onto a bar chart and then click back onto “Pareto”.  This should solve the problem.  There may be some delay in the roll out to the PBI service.  I don’t control the actual publishing, so it is hard to pinpoint.  You will need to re-publish and fix any changed formatting options.  

###### Updates

When moving between different label display options, such as stacked and rotate, you might need to flip "Fit to Page" in "Display" in order to see the whole label or hide the scrollbar. 
For hundreds of categories, set the margins to 0, turn values, labels and scrolling off.  Specifically, inner bar padding must be set to 0.
Scroll to accommodate the dataset, keeping in mind filtering to highlight the 20% Driving the 80% might be your best option.  You might need to turn "Margins" and "Padding" to 0 in "Display".
To add margins on the outside of the visual, go to Formatting pane, General Tab, Properties, Padding
The standard behavior when clicking on a datapoint is to use CTRL + click to select multiple datapoints.  I have not implemented this, because I have seen some bugs during implementation, I am working on it.  
The select will work and automatically select multiple.  You then just need to de-select it in order to take it out of the selection.

#### Multiple Major Changes  
Flipped left and right axes so bar abutts data and labels are on the outside.  This is standard orientation for a chart.  
Added border to landing page.  Visual would blend into page if clicked off of when adding multiple visuals at once.    
Added arc text hover.  
Changed label text hover to a label instead of larger font.  
Edited Format Pane. Consolidated areas for easy and standard access.  
How 1-Click Formatting is applied was improved.  
Locale was improved and fixed.  The value "none" now defaults to the local Power BI implementation.  
Added "Label Density" to arc.  This will thin percentages if needed or wanted.  
Improved label text placement.  
Added "Customize Labels" to shorten or edit long labels.  Can go from the start or end of the text.  
Improved display and architecture elements in order to make all of the above changes.<br />

All Changes were rolled into a major update

0 Minor Changes<br />
0 Maintenance Improvements<br />
0 Bug Fixes<br />

## pareto7.12.0.11-Certified
###### published 11/2023

#### Updates
The only changes were to downgrade powerbi-visuals-utils-formattingutils and upgrade powerbi-visuals-api.<br />

0 Major Changes<br />
0 Minor Changes<br />
0 Maintenance Improvements
#### 1 Bug Fix
downgraded powerbi-visuals-utils-formattingutils so locale would work.

## v7.12.0.10 Certified
###### published 10/2023

0 Major Changes
#### 2 Minor Changes
Added type and opacity to Business Pane, so users can use a solid color for the pane.  
Formatted scrollbar, visually impactful for the user<br /><br />
0 Maintenance Improvements
#### 1 Bug Fix
Was not displaying properly in Firefox.  Mulitple changes from .style to .attr.  Use .attr for shape and size.

#### Other Changes
Added code to detect browser.  
Right axis moving off page fixed.  
Rotate was not showing if level 2 cats were taken off while stack was on and then hidden

## v7.11.1.8 Certified
###### published 05/2023
 
#### 1 Major Change<br />
Added label handling on drill down to level 4.<br /><br />
0 Minor Changes<br />
0 Maintenance Improvements
#### 1 Bug Fix  
Added back level 3 and 4 labels.  

## v7.10.2.7 Certified
###### published 04/2023 
0 Major Changes<br />
0 Minor Changes<br />
0 Maintenance Improvements
#### 2 Bug Fixes  
When selecting a data point in another chart, pareto data points were not highlighting<br />
2nd level labels were using 1st level labels for coloring

## v7.9.4.6 Certified
###### published 02/2023
#### 3 Major Changes
Add rectangular box behind bars, a bar and a statement to highlight the 80%, add driver highlights for the 20%<br />  
Added scrolling<br/>
Added Repeating Gradients<br/>
#### 3 Minor Improvements 
Added Transparency property, used PBI included sort options for forced sort, improved tooltips to display text<br />
Added Click, Mouse Hover In and Out to Values to compensate for almost no data context menu<br />
Bar Coloring default changed to “Each” from one solid color<br />
#### 0 Maintenance Adjustments  
#### 2 Bug Fixes  
Make the spine thinner on Category X to show almost no data<br />
Right Axis running off viewable page<br/>

###### Pareto by sio2Graphs 7.9.0.6
* Had to add more testing instructions
###### Pareto by sio2Graphs 7.9.1.6
* Rejected because field in Values well was moving to Tooltips well when moving between previous version and this version.
* When moving between visuals fields switching between "Values" and "Tooltips" wells
###### Pareto by sio2Graphs 7.9.2.6
* Rejected because there was no right click context menu. I had taken this out, mistakenly, because I thought this was associated to hover tooltips.  This was sloppy.
###### Pareto by sio2Graphs 7.9.3.6
* Prevented the adding of bad data as it causes errors in the webservice on addition to Values
* Rejected because adding bad data was causing errors in the webservice.



## v4.6.3.5 Certified
Published 12/04/2022 12th offer

Pareto 4.6.0.5 (12th offered 11/01/2022) 
		1 Major Improvement
			Submitted for Certification
Pareto 4.6.1.5 (12th offered 11/16/2022) 
		1 Adjustment
			Had to fix JS errors on negative <rect> height
Pareto 4.6.3.5 (12th offered 12/04/2022) 
		2 Adjustments
			Had to fix more JS errors on negative <rect> height
			Had to fix 3 lint errors on method body exceeding 100 in length

## pareto3.6.0.5
Published 10/15/2022 11th offer

Pareto 3.6.0.5 (11th offered 10/15/2022) 
		1 Minor Improvements
			Added color to the label spine and ticks
		2 Bug Fixes
			Added “No Data” Page
			Added “rendering” events

## pareto3.5.0.3
Published 10/01/2022

Pareto 3.5.0.3 (10th offered 10/01/2022)
		1 bug fix
			Fixed tooltips (wrong data was displaying)   

## Pareto by sio2Graphs 3.5.0.2
Published 09/26/2022 9th offer

**Pareto by sio2Graphs 3.2.0.2 (9th offered 8/07/2022 – Never Published)**  
	*2 Minor Improvements*  
		* Added certification  
		* Added Landing Page    
	*2 bug fixes*  
  		* Fixed tooltips not showing full count and property descriptions  
  		* Remove horizontal scrollbar and addressed negative values
			
**Pareto by sio2Graphs 3.5.0.2 (9th offered 9/26/2022)**  
	*4 Minor Improvements*
		* Added numeric tooltips  
		* Added Drill-through  
		* Added label rotation  
		* Updated Landing page  
	*2 Improvements*  
		* Opened up categories, no longer limited to 10.  Looks poor when there are too many categories.  
		* Changed arc to curve at percent of category  			
	*2 bug fixes*  
		* Fixed conditional formatting  
    *Addressed negative values*  
	*In Addition*  
		* Improved the display for path and line of the axes  
		* Added and enhanced properties  
		* Streamlined the backend

  # pareto3.1.1.0
Published 06/16/2022 8th offer

Pareto 3.1.1.0 (8th offered 6/16/2022)
		1 Minor Improvement
			I added conditional formatting
		In Addition
			Added some more properties

## Pareto by sio2Graphs 3.0.0.0
Published 2/28/2022 7th offer

**Pareto by sio2Graphs 1.11.9 (never published)**  
	*1 Improvement*  
	*Added Landing Page  
	*0 bug fixes*  
**Pareto by sio2Graphs 2.0.0 (major upgrade; never published)**  
	*4 Improvements*  
	*Changed the platform to allow communication to my website   
	*Communication will validate a user who has purchased a microservice  
	*A microservice will be the purchase of advanced functions on 1 visual  
	*Added advanced functions:  
			*Drilldown
			*Axis manipulation
			
**Pareto by sio2Graphs 3.0.0.0**  
published 2/28/2022 7th offer   
	*2 Improvements*  
		*Opened up categories, no longer limited to 10.  Looks poor when there are too many categories.  
		*Changed arc to curve at percent of category  			
	*1 bug fix*  
		*Fixed pointer errors  
	*In Addition*  
		*Added 4th digit to version  
		*Brought forward Drilldown and Axis manipulation from Pareto 2.0.0  
		*Multiple Improvements and Enhancements in user customization  

## Pareto by sio2Graphs 1.10.9
Published 12/2/2020 6th offer

**Features**  
  * to be determined

**Version Changes**  
*2 bug fixes*  
  * Deleted unused code
  * Fixed default for Value Category Placement was 3 changed it to 4
  
*1 Improvement*  
  * Added Context Menu

## Pareto by sio2Graphs 1.9.7
Published 11/20/2020 5th offer

**Version Changes**  
*3 bug fixes*  
  * Corrected message syntax to users
  * Deleted unused variables and code blocks
  * In the case of “Outside Placement”, category text is no longer suppressed
  
*1 Improvement*  
  * Added Text Sizing
	  * Arc Text	
	  * Category Text	
	  * Value Text

## v1.8.4
###### published 6/24/2020 4th offer  
Submitted with standard notes and no errors
**Features**
  * persist properties
0 Major Changes
#### 2 Minor Improvements
* Added formatting
	* Axis
	* Category Text		
	* Value Text
	* Value Multiple and Decimal
	* Arc Text
	* Arc Line
	* Currency Support
  * Added Dark Background Support
#### 2 Bug Fixes
* Fixed category labels
  * Fixed value when maximum value is at the top of the left axis

# Pareto by sio2Graphs 1.6.2
Published 4/20/2020 3rd offer

**Version Changes**

1. *bug fix*  
  * Syntax correction.  style.less font setting was commented out.
  
3. *Improvements*
  * Changed font stroke
  * Changed font
  * Added gradient coloring

## Pareto by sio2Graphs 1.0.0 
This offer submitted on 12/31/2019 did not pass certification and was never published.

## Pareto by sio2Graphs 1.3.1 - 1st offer published on 02/27/2020

**Version Changes**

1. *bug fix*  
  * Syntax correction
  
3. *Improvements*
  * Data Values added on the bars with property control of placement and display (font & font stroke)
  * Labels corrected to not cut off
  * Tooltip messages were improved
