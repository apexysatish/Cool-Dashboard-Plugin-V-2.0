# Cool Dashboard Plugin V 2.0

![Screenshot](https://raw.githubusercontent.com/sattuvirus/Cool-Dashboard-Plugin-V-2.0/master/screenshot.gif)

This is a Attractive Region Dashboard Plug-in v 2.0 for Oracle APEX that let's you easily create some nice,responsive Dashboard Design Cards. These Cards can be shown in a small Information with your application details with an icon.

When you use these Dashboard plugin in Apex, below sql query will help to create sample Dashboard.
```
Select 1 as sort_order,
'https://www.google.com/' as LINK1,
'Users' title,
'250' data,
'fa-users fa-fw fa-3x' as icon_class,
'dark-blue' as class1,
'dark-blue' as class2,
'https://www.google.com/' as link
from dual
union all
Select 2 as sort_order,
'https://www.google.com/' as LINK1,
'Online' title,
'150' data,
'fa-phone fa-fw fa-3x' as icon_class,
'red' as class1,
'red' as class2,
'https://www.google.com/' as link
from dual
union all
Select 3 as sort_order,
'https://www.google.com/' as LINK1,
'Off-line' title,
'100' data,
'fa-area-chart fa-fw fa-3x' as icon_class,
'orange' as class1,
'orange' as class2,
'https://www.google.com/' as link
from dual
union all
Select 4 as sort_order,
'https://www.google.com/' as LINK1,
'Pending' title,
'250' data,
'fa fa-download fa-fw fa-3x' as icon_class,
'green' as class1,
'green' as class2,
'https://www.google.com/' as link
from dual
```	
For working Demo just click on:
<a href ="https://apex.oracle.com/pls/apex/f?p=140847:5"> <h4>Click Here For Demo</h4></a>

If you like my stuff, Please Like share and comment.

