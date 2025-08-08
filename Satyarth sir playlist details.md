
Video 1: 
1)SSRS is a sever based reporting platform.
2)Here we can make charts, maps, sparklines, tabular reports and matrix report.
3)Data sources can be relational, XML, excel, etc.
4)Why SSRS?
5)Features of SSRS.
6)Request-response diagram for SSRS report.

Video 2:
1)Tools required to run SSRS report.
2)Data source (actual source).
3)Dataset (query logic).
4)Report.
5)Import reports (only MS Access).
6)The extension for report is .rdl.

Video 3:
1)Shared data source (available for multiple projects in one project).
2)Shared dataset (available for multiple projects in one project).
3)Building connection string for data string.

Video 4:
1)Embedded data source (only can be used for that particular report for which they are created).
2)Embedded dataset.
Note: Shared data source is available for all reports in a project, but embedded data source is not available for other reports other than the ne for which it is created.

Video 5:
1)Exporting report in various formats like excel, PDF, word, power point, CSV.

Video 6:
1)Parameter.
2)Parameterized report.
3)In short taking from user.

Video 7:
1)Radio button parameters.
2)Also how to use stored procedures instead of writing the query.
3)RDL stands for Report Definition Language.

Video 8:
1)Making parameters optional

Video 9:
1)Creating drop down parameter
2)There are tow ways to create dropdown 
		1.Without dataset (by specifying values)
		2.With dataset (getting values form query)
3)In this we will do without dataset

Video 10:
1)Here we will create dropdown based on the dataset

Video 11:
1)Cascade dropdown parameter

Video 12:
1)Multivalued/Multiselect cascade dropdown

Video 13:
1)Built in fields in SSRS
2)Images in SSRS
3)How to enable/disable header and footer

Video 14:
1)Image control/Image component

Video 15:
1)Images from database and external sources

Video 16:
1)Report formatting
2)Expressions
3)Report properties (page setup, orientation, units, size,....)
4)Code
5)External assemblies
6)Variables
7)All various functions (IMPORTANT)

Video 17:
1)Conditional formatting

Video 18:
1)Alternate row coloring

Video 19:
1)Working with report wizard
2)Query designer
3)There is one setting to do if we don't see much options in query designer (ask Chat gpt)
Note: We can even use query editor/designer for simple report as well. It is not necessary that we have to use report wizard only.
4)First we can create basic report/layout using report wizard and then can edit accordingly to our requirements

Video 20:
1)User or service account
2)In this we also saw that how to use SQL Server authentication
3)Also using this option we can enable the option like to enter the login ID and passwords and if that is correct then only the report will be shown.
4)Credentials dialog box is converted here in this video.

Video 21:
1)Formatting literals
2)Placeholder properties
3)When we use built in fields like report name, page name, page number and so on, so what we write in left of that built in field called literal
example: Employee Details : [&Report Name]
here the Employee Details is called as literals
4)How to add HTML to expression (for that we need to use placeholder properties)
5)All the placeholder properties are discussed in this video.

Video 22:
1)Tablix (table) properties
		-page break
		-tool tips
		-row headers
		-column headers
		-visibility (i.e. to show/hide the table or not)
		-fillers
		-sorting
		-toggle to show/hide a particular column

Video 23:
1)Display column headers on each page i.e. to make the column headers sticky so that even if we are scrolling they are shown.

Video 24:
1)Row grouping
2)Adding total both for before and after
3)Parent group
4)Child group

Video 25:
1)Exporting groupwise data on excel sheets
2)For example one countries data in one excel sheet and another countries data in another excel sheet
3)This can be done by adding page break between each instance of a group

Video 26:
1)Drill down reports
2)To implement drill down report we must have row grouping
3)Multilevel toggle is considered as drilldown

Video 27:
1)Creating a linked report
2)For example we can create one summary report and multiple detailed reports and then we can connect that all multiple detailed reports to that one particular summary report.

Video 28:
1)Working with sub report
2)Linked report and sub report are not same, they are a bit different
3)The difference is that in linked report we are directed to a totally new report whereas incase of sub report, the new report is embedded on the main report only.

Video 29:
1)Using matrix in SSRS
2)If we take table/tablix we can only create row groups and not column groups.
3)But using matrix we can access column groups as well as along with row groups.

Video 30:
1)Alternate row coloring on row groups
2)To implement alternate row coloring on group we do not use row number instead we use running value
3)We apply different formula for both group and rows.
4)We can even match the color of the group and rows for that particular group in which they are.

Video 31:
1)Bookmarks in SSRS report

Video 32:
1)Document map

Video 33:
1)List control

Video 34:
1)Lookup function

Video 35:
1)Positioning parameters
2)We can position parameters manually according to our requirements

Video 36:
1)Embedded and HTML formatting on text box
2)Indentation
3)Font color
and so on....

Video 37:
1)Introduction to charts

Video 38:
1)Chat properties
2)Filters

video 39:
1)Axis properties in charts
2)How to modify X and Y axis number and other related topics

Video 40:
1)Series properties in charts
2)Series properties work on bar chart by right clicking we get option for series properties.

Video 41:
1)Legend properties in charts

Video 42:
1)Using Data bars in SSRS reports.