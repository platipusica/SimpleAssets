# Jam.py Application Builder (compatible with Python3)

[![Build Status](https://api.travis-ci.org/platipusica/jam-py.png?branch=master)](http://travis-ci.org/platipusica/jam-py)
[![Coverage Status](https://coveralls.io/repos/github/platipusica/jam-py/badge.svg?branch=master)](https://coveralls.io/github/platipusica/jam-py?branch=master)
![Python versions](https://img.shields.io/pypi/pyversions/python3-saml.svg)

The Assets & Parts Management Application on PythonAnywhere lives here:

https://jampy.pythonanywhere.com


The DB contains 24825 Assets,500004 Parts,1000000 Suppliers (scaled to 450k for Github upload) and 1000 Employees, all random data. The App is WIP so please bear with me.

Please visit for more info:

http://jampyapplicationbuilder.com/

or more Demos:

https://jampyapp.pythonanywhere.com/

https://sem.pythonanywhere.com/

https://msaccess.pythonanywhere.com/

The above is a direct MS Acccess migration to the Web.


How to run in *your* environment?
==================================

Download this repo. Create a New App as per below, and Import the zip file SimpleAssets_1.0.9_5.4.83.... Rename Database (F4), to SimpleAssets.sqlite and stop the App server. Copy downloaded SimpleAssets.sqlite.gz file into the folder, unzip and start the Server. The database will contain random data. 

If still not convinced about the Jam.py speed, try click-and-run application:

https://github.com/platipusica/jampy-exe



Why using Jam.py?
------------------------------------

DRY principle! Don't repeat yourself, do it once, do it well.

With Jam.py Application Builder, you can resolve a specific business problem. Out of the box Jam is providing: fast access to underlying databases, security, authentication, validation, calendars, multi languages, all of that with minimum of coding needed. Being Python framework, it is extensible and flexible.

**“All in the browser” framework**
* Internet Browser IDE
* Code Editor with Syntax Highlighting and Code Completion
* No declarative options, you are in charge.
* Instant WYSIWYG
* Application lifecycle tracking.
* SQL and stored procedures supported for major vendors.
* Integrate any Python library with no contract lock-in and reduce cost instantly.
* Bootstrap, JQuery, JS, all in here. Use it with no fuss and learning this massive libraries.
* Create rich, informative reports, due to band-oriented report generation based on LibreOffice templates.

**Event driven grids**

* Event driven grids enable you to easily manipulate data simply by clicking on a cell and editing its value.
* Event driven data-aware visual interface controls makes the framework flexible and powerful.
* Edit your data in the grid, as you would in any Desktop spreadsheet application.
* Create the master-detail table with breeze, utilising templates for displaying, which is no more than a copy/paste. Easy. * Again, no declarative methods, the control is with you as it should be.

**jsCharts or any charting libraries**

* Locked-in with a vendor charting capabilities? Never again. Use free libraries as jsChart, at.al.
* Use the same charting capabilities on your mobile devices, once for all.
* Visualise charts immediately after you create/import tables, with a few lines of code. Simple and effective.
* Analyzing/displaying BIG data? Add free Python lib's, build a Jam Web Form with parameters, execute on the server. 
* Profit.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.


Installation
------------

### Dependencies

 * python 2.7 // python 3.x
 * For MySQL database access: mysqlclient, libmysqlclient-dev
 * For Oracle database access: cx_oracle
 * For Firebird database access: fdb
 * For Jam.py Reports editing/creation: LibreOffice

## Installing an official release with pip


The easiest is to use the standalone pip installer.

If you’re using Linux, Mac OS X or some other flavor of Unix, enter the command:
```
sudo pip install jam.py 
```
at the shell prompt. If you’re using Windows, start a command shell with administrator privileges and run the command:
```
pip install jam.py 
```
This will install Jam.py in your Python installation’s site-packages directory.


## Installing an official release manually

Download the package archive from https://github.com/jam-py/jam-py/tree/master

Create a new directory and unzip the archive there.

From the above directory, enter the command:

```
sudo python setup.py install
```

This will install Jam.py in your Python installation’s site-packages directory.

## Running the Demo App

Navigate to jam.py installation demo folder, enter the command:
```
python server.py
```

You'll have the Demo App running at http://localhost:8080

## Create a new App

```
mkdir newapp
cd newapp
jam-project.py
python server.py
```
The new and empty App will run at http://localhost:8080

Please visit http://jam-py.com/docs/intro/index.html for complete Getting Started Introduction.


## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.



## Authors

* **Andrew Yushev** - [Jam-py.com](https://github.com/jam-py)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the BSD License.

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc
