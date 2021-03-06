+++
Description = "tags"
Tags = ["Development", "OpenCensus"]
Categories = ["Development", "OpenCensus"]
menu = "main"

title = "Tags"
date = "2018-05-30T15:30:07-05:00"
+++

{{% sc_tags %}}

OpenCensus allows systems to associate contextual key-value pairs called tags with measurements as they are recorded. These tags can later be used in views as dimensions to break down the measurements, analyze them from various different perspectives and target specific cases in isolation even in highly interconnected and complex systems.  
&nbsp;  

Tags may be defined in one service and used in a view in a different service because they are propagated along the call chain. For example, assume you have a frontend service that processes REST API requests by making calls to a backend service responsible for data storage. You can create a view in the data storage service that breaks down some measurement (e.g. disk accesses) but the API method in the frontend.  
&nbsp;
&nbsp;

{{% /sc_tags %}}