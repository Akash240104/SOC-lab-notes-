Objectives : 
- Exploring splunk web 
- Running searches 
- Using commands 
- Creating reports 
- creating dashboards 
- Understanding knowledge objects 

**SPLUNK** is a unified data platform that allows teams to work together or individually to ensure mission critical digital systems stay secure and reliable.
- It can provide key to enterprise resilience and help build a safer digital world.

Its primary features are : 
-Index(heart of the splunk) contains the machine data from sources such as servers, network devices and web applications.
- Raw data is processed by inspectors along with the timestamps in order to match the event.
-  Once the data is processed it is available for searching and analyzing.
- By entering a query into splunk's search bar , we can find events that contaain values across multiple data sources
- Search results can be saved into reports which can provide continued insights into the data and can be used to power dashboard pannels.
- Knowledge can be organized into structured datasets called data models, to allow users to quicky visualize data in pivot.

-There are three predefined deault roles in splunk enterprise : 
1.The administrator(Most powerful) - can install apps, ingest data and create knowledge objects for all users.
2.The power - can create and share knowledge objects with all users of an app and perform real time searches   
3.The user - will only see their own knowledge objects and those that have been shared with them

Searching and reporting app 
- There are 8 main components of search and repoerting app's interface.

Breakdown of the data -- 
- Hosts - is the hostnane , ip address or fully qualified domain name of machine from which the event is originated.
- Sources - file or the directory path, network port or script from which the event originated
- Sourcetypes - classification of the data
