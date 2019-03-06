# SquatchWatch
This is a program simulation for a bigfoot reasercher company.  It uses MySQL for the database, Java for the buisness logic, and Web UI for front end.  The main feature of this is dynamic catalog of items, they can be added or deleted, based on the level of administration.  Using Spring Security I both hide and alter user abilities, with four different access levels.  The items feature a name, cost, description, picture, and tags. Each of these categories can be filtered either together or individual when searching for items.  Home page features a dynamic 'featured items' list with name and picture, which can only be added or removed by management.

**cooperation**

this was created in a group collaborative project.  Four of us in total over a short agile SDLC.  Sprints were made and content needs updated.  The team used JIRA to allocate work and keep people accountable for tasks.

**Database**

We used MySQL to persist the changes and information. We gathered information from the table using the rowMapper interface.  For organization we used 2nd form normalization and bridge tables.  Pictures had to be uploaded online.

**Web UI**

For our front end we used HTML, CSS, Bootstrap, and JQuery.  It communicated by httpServlet requests, JSON formatted data.  To receive information we used Models.  Web UI also changes based of device useage, changing navbars into easier to handle drop downs when on a phone.

**Java**

Java is the language chosen for the business logic.  We kept things loosly couped using dependency injection with interfaces.  We also perform try-catches on all incoming data to prevent crashes and dirty data.
