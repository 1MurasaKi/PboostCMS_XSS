# PboostCMS_XSS

BUG_Author: Murasaki

URL:

- /admin.php?p=/Area/index#tab=t2
- /admin.php?p=/Role/index



Parameter "name"(POST) exists cross site script injection vulnerability

Link:https://gitee.com/hnaoyun/PbootCMS



There is a cross site scripting vulnerability in the POOTCMS system.

In the data area of the backend, the name parameter can be submitted by constructing a JavaScript statement. When the administrator clicks on the system role, the script statement will be triggered, causing cross site script injection.

The following is the process of reproducing vulnerabilities:
