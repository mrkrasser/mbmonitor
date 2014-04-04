mbmonitor
==

last update: 2005-07-26

Script on Perl.  
Check CPU temperature and Fan speed via **mbmon** program and exec command when temp is too high.

### mbmon install
FreeBSD  
```cd /usr/ports/sysutils/mbmon/ && make install clean```  
Ubuntu  
```sudo apt-get install mbmon xmbmon```
 
### mbmon exec
*/1 * * * * /home/user/bin/mbmonitor
 вращения кулера можно скорректировать в начале скрипта.
