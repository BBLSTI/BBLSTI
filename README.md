The BBLSTI application is designed utilising the Python/Django Framework and is available for deployment as currently stands.

Core technologies used that expected to be familiar with:
- Python/Django Web Framework
- PostgreSQL RDBMS with PostGIS
- REST Service Architecture Style
- Geographic Information Systems
- JavaScript
- HTML5
- CSS3
- Bootstrap 4 CSS Framework
- Linux-based OS environment
- Git version control

Core server technologies you will be required to have a working knowledge of are:
- Linux-based OS environment
- PostgreSQL RDBMS with PostGIS
- Redis Server
- Nginx Web Server
- Gunicorn

Docker has not been employed yet as the system currently stands.

The application may be installed in an ENV by cloning the repository and running requirements.txt. On the PostGreSQL database installation the PostGIS extension is required to be added. Additional installation of redis-server is required to run the background and cached applications.

Installation may be effected form anyone of the branches but deployment should be effected from the Main branch with all revisions and devopment performed in the branches and merged with main after final acceptance and allocation for production.

Utilisation of both function-based views (FBVs), and class-based views (CBVs) has been employed due the the requirement to develop outside of the traditional CRUD functionallity as required by CBV's for the development of the Register. Best practice to develop according the the multiform and multifunctionality would be to utilise detail views with multiple endpoints on the templates. In order to align and create the AJAX or REST Service Architecture Style functionality a thorough knowledge of Javascript or JQuery will be required.

The menu system utilises a basic formatted menu with redirects and a simple administration access utilising CRUD styled lists with the initial filters being developed prior to report development.

The Calendar has been initiated utilising CBV's with templatetags for functionality and pending review for acceptance. Ininial development allows personal access to the calendar with a multiview Detailed calendar for administrative use based on the provided excel spreadsheets currently utilised.
