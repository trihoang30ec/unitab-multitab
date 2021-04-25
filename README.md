# Dealing with multiple responses

### program **``mtab``**
``syntax [varlist(default = none)] [, sheet(string) by(string) dir(string) type(string) format(string)]`` <br />
Example: ``mtab b51-b515, by(y1) sheet(b5) dir(mtab1.xlsx) type(percentage) format(percent_d2)``
### program **``multitab``**
``syntax [varlist(default = none)] [, sheet(string) dir(string)]`` <br />
Example: ``multitab b51-b515, sheet(b5) dir(multitab.xlsx)``
### program **``utab``**
``syntax [varlist(default = none)] [, by(string) dir(string) temp(string) type(string) format(string)]`` <br />
Example: ``utab dt a8 a9, by(y1) dir(u.xlsx) temp(utab.xls) type(percentage) format(percent_d2)``
### program **``unitab``**
``syntax [varlist(default = none)] [, dir(string) temp(string)]`` <br />
Example: ``unitab a1 a3, dir(unitab.xlsx) temp(temp.xls)``



