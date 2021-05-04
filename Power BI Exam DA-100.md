# Power BI Exam DA-100

{Work in Process, Stay Tuned}

`Data Analysts enable businesses to maximize the value of their data assets by using Power BI. As a subject matter expert, data analysts are responsible for designing and building scalable data models, cleaning and transforming data, and enabling advanced analytic capabilities that provide meaningful business value through easy-to-comprehend data visualizations. Data analysts also collaborate with key stakeholders across verticals to deliver relevant insights based on identified business requirements.
The Data Analyst should have a fundamental understanding of data repositories and data processing both on-premises and in the cloud.`

## Exam
* [Exam DA-100: Analyzing Data with Microsoft Power BI](https://docs.microsoft.com/en-us/learn/certifications/exams/da-100) - Microsoft Certification can take you from the start of your career to its pinnacle. Certification can increase your visibility, differentiate you from your peers, and validate your knowledge and skills.
* [About Microsoft Certification exams](https://docs.microsoft.com/en-us/learn/certifications/certification-exams)

-----

## Skills measured (March 23, 2021)
### Prepare the data (20-25%)
##### Get data from different data sources
* Identify and connect to a data source
  * [Connect to data sources in Power BI Desktop](https://docs.microsoft.com/en-us/power-bi/connect-data/desktop-connect-to-data?ref=najielkotob)
  * [SharePoint Folder](https://docs.microsoft.com/en-us/power-query/connectors/sharepointfolder?ref=najielkotob)
* Change data source settings
  * [Manage data sources](https://docs.microsoft.com/en-us/power-bi/connect-data/service-gateway-data-sources?ref=najielkotob)
* Select a shared dataset or create a local dataset
  * [Connect to datasets in the Power BI service from Power BI Desktop](https://docs.microsoft.com/en-us/power-bi/connect-data/desktop-report-lifecycle-datasets) 
* [Select a storage mode](https://docs.microsoft.com/en-us/power-bi/transform-model/desktop-storage-mode?ref=najielkotob)
* [Choose an appropriate query type]()
* [Identify query performance issues]()
* [Use Microsoft Dataverse](https://docs.microsoft.com/en-us/powerapps/maker/data-platform/data-platform-powerbi-connector?ref=najielkotob) - Create a Power BI report using data from Dataverse
  * Common Data Service has been renamed to Microsoft Dataverse
* [Use parameters](https://docs.microsoft.com/en-us/power-query/power-query-query-parameters?ref=najielkotob)
* Use or create a PBIDS file
  * [Using PBIDS files to get data](https://docs.microsoft.com/en-us/power-bi/connect-data/desktop-data-sources#using-pbids-files-to-get-data)
* [Use or create a data flow](https://docs.microsoft.com/en-us/power-bi/transform-model/dataflows/dataflows-create?ref=najielkotob)
* Connect to a dataset using the XMLA endpoint
  * [Dataset connectivity with the XMLA endpoint](https://docs.microsoft.com/en-us/power-bi/admin/service-premium-connect-tools?ref=najielkotob) 

##### Profile the data
* Identify data anomalies
  * [Column profile](https://docs.microsoft.com/en-us/power-query/data-profiling-tools#column-profile) 
* Examine data structures
  * [Data types in Power Query](https://docs.microsoft.com/en-us/power-query/data-types) 
  * [Column distribution](https://docs.microsoft.com/en-us/power-query/data-profiling-tools#column-distribution) 
* Interrogate column properties
  * [Column quality](https://docs.microsoft.com/en-us/power-query/data-profiling-tools#column-quality) 
* Interrogate data statistics
  * [Column profile](https://docs.microsoft.com/en-us/power-query/data-profiling-tools#column-profile) 
  * [Create a Profiling Report in Power BI: Give the End User Information about the Data](https://radacad.com/create-a-profiling-report-in-power-bi-give-the-end-user-information-about-the-data?ref=najielkotob) - radacad.com


##### Clean, transform, and load the data
* Resolve inconsistencies, unexpected or null values, and data quality issues
* Apply user-friendly value replacements
* Identify and create appropriate keys for joins
  * [Seven Types of Table Joins](https://www.powerbi-pro.com/en/power-bi-seven-types-of-table-joins/) - powerbi-pro.com
* Evaluate and transform column data types
* Apply data shape transformations to table structures
* Combine queries
* Apply user-friendly naming conventions to columns and queries
* Leverage Advanced Editor to modify Power Query M code
* Configure data loading
* Resolve data import errors
  * [Viewing Error Messages For All Rows In Power Query](https://blog.crossjoin.co.uk/2014/12/22/viewing-error-messages-for-all-rows-in-power-query/) - Chris Webb's BI Blog

### Model the data (25-30%)
#### Design a data model
* Define the tables
* Configure table and column properties
* Define quick measures
  * [Use quick measures for common calculations](https://docs.microsoft.com/en-us/power-bi/transform-model/desktop-quick-measures) 
* Flatten out a parent-child hierarchy
* Define role-playing dimensions
  *  [Understand star schema and the importance for Power BI](https://docs.microsoft.com/en-us/power-bi/guidance/star-schema#role-playing-dimensions)
* Define a relationship's cardinality and cross-filter direction
  * [Model relationships in Power BI Desktop](https://docs.microsoft.com/en-us/power-bi/transform-model/desktop-relationships-understand) 
* Design the data model to meet performance requirements
  * [Best practice rules to improve your model’s performance](https://powerbi.microsoft.com/en-us/blog/best-practice-rules-to-improve-your-models-performance/?ref=najielkotob) 
* Resolve many-to-many relationships
* Create a common date table
  * [Create date tables in Power BI Desktop](https://docs.microsoft.com/en-us/power-bi/guidance/model-date-tables) 
* Define the appropriate level of data granularity
  
#### Develop a data model
* Apply cross-filter direction and security filtering
  * [Cross filter direction](https://docs.microsoft.com/en-us/power-bi/transform-model/desktop-relationships-understand#cross-filter-direction)
* Create calculated tables
  * [Create calculated tables in Power BI Desktop](https://docs.microsoft.com/en-us/power-bi/transform-model/desktop-calculated-tables) 
* Create hierarchies
* Create calculated columns
  * [Create calculated columns in Power BI Desktop](https://docs.microsoft.com/en-us/power-bi/transform-model/desktop-calculated-columns) 
* Implement row-level security roles
  * [Row-level security (RLS) with Power BI](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-rls) 
* Set up the Q&A feature

#### Create measures by using DAX
* Use DAX to build complex measures
* Use CALCULATE to manipulate filters
* Implement Time Intelligence using DAX
* Replace numeric columns with measures
* Use basic statistical functions to enhance data
* Create semi-additive measures

#### Optimize model performance
* Remove unnecessary rows and columns
* Identify poorly performing measures, relationships, and visuals
* Improve cardinality levels by changing data types
* Improve cardinality levels through summarization
* Create and manage aggregations

### Visualize the data (20-25%)
#### Create Report
* Add visualization items to reports
* Choose an appropriate visualization type
* Format and configure visualizations
* Import a custom visual
* Configure conditional formatting
* Apply slicing and filtering
  * [How visuals cross-filter each other in a Power BI report](https://docs.microsoft.com/en-us/power-bi/consumer/end-user-interactions?ref=najielkotob) * Add an R or Python visual
* Configure the report page
* Design and configure for accessibility
  * [Design Power BI reports for accessibility](https://docs.microsoft.com/en-us/power-bi/create-reports/desktop-accessibility-creating-reports?ref=najielkotob) 
* Configure automatic page refresh
* Create a paginated report
  * [What are paginated reports in Power BI Premium?](https://docs.microsoft.com/en-us/power-bi/paginated-reports/paginated-reports-report-builder-power-bi?ref=najielkotob)

#### Create dashboards
* Set mobile view
  * [Optimize Power BI reports for the mobile app](https://docs.microsoft.com/en-us/power-bi/create-reports/desktop-create-phone-report?ref=najielkotob) 
* Manage tiles on a dashboard
  * [Intro to dashboard tiles for Power BI designers](https://docs.microsoft.com/en-us/power-bi/create-reports/service-dashboard-tiles?ref=najielkotob)
  * [Pin a tile to a Power BI dashboard from a report](https://docs.microsoft.com/en-us/power-bi/create-reports/service-dashboard-pin-tile-from-report?ref=najielkotob)
  * [Pin a tile from one dashboard to another dashboard](https://docs.microsoft.com/en-us/power-bi/create-reports/service-pin-tile-to-another-dashboard?ref=najielkotob)
* Configure data alerts
  * [Data alerts in the Power BI service](https://docs.microsoft.com/en-us/power-bi/create-reports/service-set-data-alerts?ref=najielkotob) 
* Use the Q&A feature
  * [Tips for asking questions in Power BI Q&A](https://docs.microsoft.com/en-us/power-bi/consumer/end-user-q-and-a-tips?ref=najielkotob)  
* Add a dashboard theme
  * [Use dashboard themes in the Power BI service](https://docs.microsoft.com/en-us/power-bi/create-reports/service-dashboard-themes?ref=najielkotob) 
* Pin a live report page to a dashboard
  * [Pin an entire report page, as a live tile, to a Power BI dashboard](https://docs.microsoft.com/en-us/power-bi/create-reports/service-dashboard-pin-live-tile-from-report?ref=najielkotob) 


#### Enrich reports for usability
* Configure bookmarks
* Create custom tooltips
* Edit and configure interactions between visuals
* Configure navigation for a report
* Apply sorting
* Configure Sync Slicers
* Use the selection pane
* Use drillthrough and cross filter
* Drilldown into data using interactive visuals
* Export report data
* Design reports for mobile devices


### Analyze the data (10-15%)
#### Enhance reports to expose insights
* Apply conditional formatting
* Apply slicers and filters
* Perform top N analysis
* Explore statistical summary
* Use the Q&A visual
* Add a Quick Insights result to a report
* Create reference lines by using Analytics pane
* Use the Play Axis feature of a visualization
* Personalize visuals

#### Perform advanced analysis
* Identify outliers
* Conduct Time Series analysis
* Use groupings and binnings
  * [Use grouping and binning in Power BI Desktop](https://docs.microsoft.com/en-us/power-bi/create-reports/desktop-grouping-and-binning?ref=najielkotob) 
* Use the Key Influencers to explore dimensional variances
* Use the decomposition tree visual to break down a measure
* Apply AI Insights

### Deploy and maintain deliverables (10-15%)
#### Manage datasets
* Configure a dataset scheduled refresh
  * [Data refresh in Power BI](https://docs.microsoft.com/en-us/power-bi/connect-data/refresh-data) 
* Configure row-level security group membership
* Providing access to datasets
* Configure incremental refresh settings
  * [Incremental refresh for datasets](https://docs.microsoft.com/en-us/power-bi/connect-data/incremental-refresh-overview) 
* Promote or certify Power BI datasets
* Identify downstream dataset dependencies
  * [Identifying shared datasets](https://docs.microsoft.com/en-us/power-bi/collaborate-share/service-dataset-impact-analysis#identifying-shared-datasets) 
* Configure large dataset format


#### Create and manage workspaces
* Create and configure a workspace
  * [Create the new workspaces in Power BI](https://docs.microsoft.com/en-us/power-bi/collaborate-share/service-create-the-new-workspaces) 
* Recommend a development lifecycle strategy
* Assign workspace roles
  * [Roles in the new workspaces](https://docs.microsoft.com/en-us/power-bi/collaborate-share/service-new-workspaces#roles-in-the-new-workspaces) 
* Configure and update a workspace app
* Publish, import, or update assets in a workspace
* Apply sensitivity labels to workspace content
* Use deployment pipelines
* Configure subscriptions
* Promote or certify Power BI content


-----

## Kahoot
* [Power BI Quiz with Adam Saxton](https://www.youtube.com/watch?v=KGWnrhILY7c)
* [Power BI Quiz with Will Thompson](https://www.youtube.com/watch?v=GHpm9EHVK4k)

## Microsoft Learn
* [Get started with Microsoft data analytics](https://docs.microsoft.com/en-us/learn/paths/data-analytics-microsoft/?ref=najielkotob)
* [Prepare data for analysis](https://docs.microsoft.com/en-us/learn/paths/prepare-data-power-bi/?ref=najielkotob)
* [Model data in Power BI](https://docs.microsoft.com/en-us/learn/paths/model-power-bi/?ref=najielkotob)
* [Visualize data in Power BI](https://docs.microsoft.com/en-us/learn/paths/visualize-data-power-bi/?ref=najielkotob)
* [Data analysis in Power BI](https://docs.microsoft.com/en-us/learn/paths/perform-analytics-power-bi/?ref=najielkotob)
* [Manage workspaces and datasets in Power BI](https://docs.microsoft.com/en-us/learn/paths/manage-workspaces-datasets-power-bi/?ref=najielkotob)
