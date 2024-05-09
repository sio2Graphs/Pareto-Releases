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
Added Repeating Gradients
#### 3 Minor Improvements 
Added Transparency property, used PBI included sort options for forced sort, improved tooltips to display text<br />
Added Click, Mouse Hover In and Out to Values to compensate for almost no data context menu<br />
Bar Coloring default changed to “Each” from one solid color
#### 4 Maintenance Adjustments
Added context menu on right click<br />
Prevented the adding of bad data
#### 2 Bug Fixes
Make the spine thinner on Category X to show almost no data<br />
Right Axis running off viewable page

## v4.6.3.5 Certified
###### Published 12/2022

## v4.6.3.5
#### 1 Major Change
#### 1 Minor Improvement
Added color to the label spine and ticks<br />
#### 3 Maintenance Adjustments
#### 2 Bug Fixes
Added “No Data” Page
Added “rendering” events

## v3.5.0.3
###### Published 10/2022
#### 0 Major Changes
#### 0 Minor Improvements
#### 0 Maintenance Adjustments
#### 1 Bug Fix
Fixed tooltips   

## v3.5.0.2
###### Published 09/2022
#### 0 Major Changes
#### 8 Minor Improvements
Added certification<br />
Added Landing Page<br />
Opened up categories, no longer limited to 10.  Looks poor when there are too many categories.<br />
Changed arc to curve at percent of category<br />
Added numeric tooltips<br />  
Added Drill-through<br /> 
Added label rotation<br />  
Updated Landing page
#### 0 Maintenance Adjustments
#### 2 Bug Fixes
Fixed tooltips not showing full count and property descriptions<br />
Remove horizontal scrollbar and addressed negative values
Fixed conditional formatting
			
## v3.1.1.0
###### Published 06/2022
#### 0 Major Changes
#### 1 Minor Improvement
I added conditional formatting
#### 0 Maintenance Adjustments
#### 0 Bug Fixes

## v3.0.0.0
###### Published 2/2022
###### Multiple Improvements and Enhancements in user customization
#### 2 Major Changes
Opened up categories, no longer limited to 10<br />
Changed arc to curve at percent of category
#### 1 Minor Improvement
Added Landing Page<br />
Axis manipulation<br />
Drilldown
#### 0 Maintenance Adjustments
#### 1 Bug Fix
Fixed pointer errors  

## v1.10.9
###### Published 12/2020

**Version Changes**  
*2 bug fixes*  
  * Deleted unused code
  * Fixed default for Value Category Placement was 3 changed it to 4
  
*1 Improvement*  
  * Added Context Menu

## v1.9.7
###### Published 11/2020

**Version Changes**  
*3 bug fixes*  
  * Corrected message syntax to users<br />
  * Deleted unused variables and code blocks<br />
  * In the case of “Outside Placement”, category text is no longer suppressed
  
*1 Improvement*  
  * Added Text Sizing
	  * Arc Text<br />	
	  * Category Text<br />	
	  * Value Text

## v1.8.4
###### published 6/24/2020 4th offer  
Submitted with standard notes and no errors
**Features**
  * persist properties
0 Major Changes
#### 2 Minor Improvements
* Added formatting
	* Axis<br />
	* Category Text<br />		
	* Value Text<br />
	* Value Multiple and Decimal<br />
	* Arc Text<br />
	* Arc Line<br />
	* Currency Support<br />
  * Added Dark Background Support
#### 2 Bug Fixes
* Fixed category labels
  * Fixed value when maximum value is at the top of the left axis

## v1.6.2
###### Published 4/2020

**Version Changes**

1. *bug fix*  
  * Syntax correction.  style.less font setting was commented out.
  
3. *Improvements*
  * Changed font stroke
  * Changed font
  * Added gradient coloring

## v1.3.1
###### Published 2/2020

**Version Changes**

1. *bug fix*  
  * Syntax correction
  
3. *Improvements*
  * Data Values added on the bars with property control of placement and display (font & font stroke)
  * Labels corrected to not cut off
  * Tooltip messages were improved
