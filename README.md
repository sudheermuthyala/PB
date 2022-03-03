# PB

# What is Power Query?
 Power Query is a data transformation and data preparation engine. Power Query comes with a graphical interface for getting data from sources and a Power Query Editor for applying transformations.
Using Power Query, you can perform the extract, transform, and load (ETL) processing of data.
![](2022-03-03-16-36-12.png)

**How does Power Query help with data acquisition?**
-	Power Query enables connectivity to a wide range of data sources, including data of all sizes and shapes.
-	Power Query Consistency of experience, and parity of query capabilities over all data sources.
-	Highly interactive and intuitive experience for rapidly and iteratively building queries over any data source, of any size.
-	When using Power Query to access and transform data, you define a repeatable process (query) that can be easily refreshed in the future to get up-to-date data.
-	In the event that you need to modify the process or query to account for underlying data or schema changes, you can use the same interactive and intuitive experience you used when you initially defined the query.
-	Power Query offers the ability to work against a subset of the entire dataset to define the required data transformations, allowing you to easily filter down and transform your data to a manageable size.
-	Power Query queries can be refreshed manually or by taking advantage of scheduled refresh capabilities in specific products (such as Power BI) or even programmatically (by using the Excel object model).
-	Because Power Query provides connectivity to hundreds of data sources and over 350 different types of data transformations for each of these sources, you can work with data from any source and in any shape.

**Where can you use Power Query?**

The following table lists Microsoft products and services where Power Query can be found.

![](2022-03-03-16-43-52.png)
![](2022-03-03-16-45-50.png)

# 1.Power Query User Experience ?
The Power Query Editor is the primary data preparation experience, where you can connect to a wide range of data sources and apply hundreds of different data transformations by previewing data and selecting transformations from the UI. These data transformation capabilities are common across all data sources, whatever the underlying data source limitations.
When you create a new transformation step by interacting with the components of the Power Query interface, Power Query automatically creates the M code required to do the transformation so you don't need to write any code.

Currently, two Power Query experiences are available:
- **Power Query Online :** Found in integrations such as Power BI dataflows, Microsoft Power Platform dataflows, Azure Data Factory wrangling dataflows, and many more that provide the experience through an online webpage.
- **Power Query for Desktop :** Found in integrations such as Power Query for Excel and Power BI Desktop.

# 2.By default Power Quey Page looks like in the below,
The Power Query editor represents the Power Query user interface, where you can add or modify queries, manage queries by grouping or adding descriptions to query steps or visualize your queries and their structure with different views. The Power Query user interface has five distinct components.

![](2022-03-03-16-51-40.png)

1.	**Ribbon**: the ribbon navigation experience, which provides multiple tabs to add transforms, select options for your query, and access different ribbon buttons to complete various tasks.
2.	**Queries pane:** a view of all your available queries.
3.	**Current view:** your main working view, that by default, displays a preview of the data for your query. You can also enable the diagram view along with the data preview view. You can also switch between the schema view and the data preview view while maintaining the diagram view.
NOTE: The Schema view and Diagram View feature are available only for Power Query Online.
4.	**Query settings:** a view of the currently selected query with relevant information, such as query name, query steps, and various indicators.
5.	**Status bar:** a bar displaying relevant important information about your query, such as execution time, total columns and rows, and processing status. This bar also contains buttons to change your current view.

# 3. Transformations in Power Query:
These transformations can be as simple as removing a column or filtering rows, or as common as using the first row as a table header. There are also advanced transformation options such as merge, append, group by, pivot, and unpivot.
The following illustration shows a few of the transformations available in Power Query Editor.

![](2022-03-03-16-54-51.png)