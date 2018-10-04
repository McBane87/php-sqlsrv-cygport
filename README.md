# php-sqlsrv-cygport

### Howto Build/Install
1. Make sure you have `cygport`, `php`, `php-devel` and `libiodbc-devel` installed  
2. `cygport php7-sqlsrv.cygport prep`  
3. `cygport php7-sqlsrv.cygport compile`  
4. `cygport php7-sqlsrv.cygport install`  
5.
   For i686:   `cp -avr sqlsrv-5.3.0-1.i686/inst/* /`  
   For x86_64: `cp -avr sqlsrv-5.3.0-1.x86_64/inst/* /`  

6. Download and install "Microsoft ODBC Driver 17 for SQL Server"  
(just the Windows version, no special Linux or Cygwin version needed)  

7. Copy the contents of `iodbc-example-config/odbcinst.ini` to `/etc/odbcinst.ini`
