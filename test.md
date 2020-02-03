```
test
Reference	    : N/A
```
<br>

# Description

User can add XSS payload in Directory Name , Filename , file extension in function "File Manager"

<br>

# Reproduce

4. Go to "Create File" and insert XSS payload "<img src="x'x=x" onerror=javascript&colon;alert&lpar;document&period;cookie&rpar;>" 

<kbd>![](x)</kbd>


