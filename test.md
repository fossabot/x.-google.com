```
test
Reference	    : N/A
```
<br>

# Description

User can add XSS payload in Directory Name , Filename , file extension in function "File Manager"

<br>

# Reproduce

1. In user panel go to File Management --> File Manager

<kbd>![](_x)</kbd>

2. Go to "Create Directory" and insert XSS payload "<img src=x onerror=javascript&colon;alert&lpar;document&period;cookie&rpar;>" 

<kbd>![](_resources/CVE-2019-16295.md/2019-10-25-14-35-46.png)</kbd>

3. XSS will trigger.

<kbd>![](x)</kbd>

4. Go to "Create File" and insert XSS payload "<img src=x onerror=javascript&colon;alert&lpar;document&period;cookie&rpar;>" 

<kbd>![](x)</kbd>

5. XSS will trigger.

<kbd>![](x)</kbd>

