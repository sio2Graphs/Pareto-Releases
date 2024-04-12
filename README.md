# Pareto-Releases
Here you will find release notes and updates.  The latest release is listed first.  

cynthia@sio2graphs.com  
www.sio2graphs.com  
easy, effective, aesthetic  

## v8.0.0.1 Certified
###### Published 4/2024  
Fixes the display of a blank screen, not the landing page with the sio2Graphs logo, on the passing of a blank or null to the Categories well.  
###### Updates
This will not be a disruptive release, as there are almost no changes to the underlying code.
#### 0 Major Changes  
Bug fix only.
#### 0 Minor Changes
Bug fix only.
#### 0 Maintenance Improvements
Bug fix only.
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
Improved display and architecture elements in order to make all of the above changes.  

#### 0 Minor Changes
All Changes were rolled into a major update  
#### 0 Maintenance Improvements
All Changes were rolled into a major update
#### 0 Bug Fixes
All Changes were rolled into a major update
## pareto7.12.0.11-Certified
###### published 11/2023

#### Updates
The only changes were to downgrade powerbi-visuals-utils-formattingutils and upgrade powerbi-visuals-api.

#### 0 Major Changes
#### 0 Minor Changes
#### 0 Maintenance Improvements
#### 1 Bug Fix
downgraded powerbi-visuals-utils-formattingutils so locale would work.

## v7.12.0.10 Certified
###### published 10/2023

#### 2 Minor Changes
Added type and opacity to Business Pane, so users can use a solid color for the pane.  
Formatted scrollbar, visually impactful for the user

#### 1 Bug Fix
Was not displaying properly in Firefox.  Mulitple changes from .style to .attr.  Use .attr for shape and size.

#### Other Changes
Added code to detect browser.  
Right axis moving off page fixed.  
Rotate was not showing if level 2 cats were taken off while stack was on and then hidden
