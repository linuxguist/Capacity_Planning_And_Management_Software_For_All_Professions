# Capacity_Planning_And_Management_Software_For_All_Professions
Free &amp; Open Source, Capacity Planning &amp; Management Software, in a Complete Virtual Machine

Every Profession has some sort of Resource to manage, be it materials, money, physical or logical resources & with it some vital queries to be answered: At what Rate is my Resource getting consumed? How Long will current stock last? What will be near future requirement?

In Just Two Simple steps of Defining Your Resource & Actively Tracking its Consumption, you will be in total control of your Resource, with this Software.

After starting this VM, from any PC on your Local Network, access the: 

Application Website: https://trcfir.local

( Accept Any Warnings due to Usage of Self-Signed https certificates )


Logins: operator & groupsmanager 

Password: change_this 


If you are new to Virtual Machines, then please watch the Video below ( taken from my other project. just replace td with trcfir wherever mentioned )

Backup system regularly as shown in video, to avoid any issues.

This VM helps to make a Capacity Planning Software / Server live, within minutes.

## Features

It is a Resource Consumption Recording, Forecasting, Capacity Planning, Capacity Management Software.

Add unlimited number of groups through groupsmanager login to seggregate data and then give them page access permission similar or lesser than the default operator id

Flexible definition of resources with choice of past and future timeframes for analysis. Just before you take a report, set the Report_Start_Date, Report_End_Date and Forecast_Upto_This_Date ( Future Date ) in the Define_Resources_Here page. It can be left empty while defining first time. The report start and end date can be set as per your recording of consumption or even smaller time frame. Also adjust the Stock Available / Free Limit Value just before you take a report

Defining and Recording Resource Consumption in the same unit of measurement is mandatory though for correct analysis and forecasts. This means Available / Free Limit Value and Consumption recording are Numeric values. No Alphabets allowed

This Virtual Machine's System console logins are tc, trcfir and root. Passwords are the same as above. sudo -s gives you root access. Change their passwords as shown in the example video below.

No internet connectivity required. Just local network is sufficient.

Data entry can be done from multiple computers for speeding up

Differential report requires atleast two records of consumption ( For Subtracting ) while Incremental report requires one record

VirtualBox or VMware Player are freely available softwares for playing virtual machines. Search Google for their websites and download them.

groupsmanager login need to be used for changing the application login passwords. These passwords are MD5 encrypted and can be easily derived using free online string to md5 generators, for deriving new passwords.

A small correction in the Video below: Choose a LAN Card Network Adapter Connection in Virtualbox ( Not Wifi ), after connecting your PC to your Router / Switch, with a LAN Cable. If the Router / Switch has a DHCP Server enabled inside, then the Virtual Machine, will be able to obtain an IP Address from it, quickly.

As this system is meant for local network usage, it uses a self-signed https certificate. Hence, browsers will throw a warning for the first time. Please accept the same and proceed ahead.

The acronym trcfir stands for Track Resource Consumption and Forecast Its Requirement.

Please save this webpage completely, for future references.

if you are new to Virtual Machines OR if you need more instructions on this project, then please watch the youtube video below, which is taken from my other project: ( Right Click to Open in New Tab )

https://youtu.be/Crxr8X9bGn8

Hope you find this software very useful in your day to day work. If you do, please give a Star Rating to it, so that others get to know about it.

## Direct download link given below ( Right Click to Open in New Tab ) : 

https://sourceforge.net/projects/trcfir/files/latest/download

Some screenshot below:

![Screenshot 1](https://i.imgur.com/Kod2Bwq.jpg "Screenshot 1")

