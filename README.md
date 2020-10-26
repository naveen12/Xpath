# Xpath
**A is a python based cross-platform tool that automates the process of detecting and exploiting error-based injection security flaws.**

[![Xpath3-0.png](https://i.postimg.cc/x1YTx1bc/Xpath3-0.png)](https://postimg.cc/F7W41mp4)


## ***Requirements***

- Python 3
- Python `pip3`
- Python module `requests`
- Python module `colorama`
- Python module `chardet`

## ***Module Installation***

    pip install -r requirements.txt

## ***Tested on***

- Windows 7/8/8.1/10
- Ubuntu-LTS (tested with super user)

## ***Download Xpath***

You can download the latest version of udemy-dl by cloning the GitHub repository.

    git clone https://github.com/r0oth3x49/Xpath.git

## **Advanced Usage**

<pre><code>
Author: Nasir khan (<a href="http://r0oth3x49.herokuapp.com/">r0ot h3x49</a>)

usage: python xpath.py -u URL [OPTIONS]

A cross-platform python based automated tool to detect and exploit error-based sql injections.

General:
  -h, --help         Shows the help.
  -v, --version      Shows the version.

Target:
  At least one of these options has to be provided to define the
  target(s)

  -u URL, --url URL  Target URL (e.g. 'http://www.site.com/vuln.php?id=1).

Request:
  These options can be used to specify how to connect to the target URL

  --data DATA        Data string to be sent through POST (e.g. "id=1")
  --cookie COOKIE    HTTP Cookie header value (e.g. "PHPSESSID=a8d127e..")

Enumeration:
  These options can be used to enumerate the back-end database
  managment system information, structure and data contained in the
  tables.

  -b, --banner       Retrieve DBMS banner
  --current-user     Retrieve DBMS current user
  --current-db       Retrieve DBMS current database
  --hostname         Retrieve DBMS server hostname
  --dbs              Enumerate DBMS databases
  --tables           Enumerate DBMS database tables
  --columns          Enumerate DBMS database table columns
  --dump             Dump DBMS database table entries
  -D DB              DBMS database to enumerate
  -T TBL             DBMS database tables(s) to enumerate
  -C COL             DBMS database table column(s) to enumerate

Example:
  python xpath.py http://www.site.com/vuln.php?id=1 --dbs
</code></pre>


### Legal disclaimer

    Usage of xpath for attacking targets without prior mutual consent is illegal.
    It is the end user's responsibility to obey all applicable local,state and federal laws. 
    Developer assume no liability and is not responsible for any misuse or damage caused by this program.
