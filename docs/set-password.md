# change password

## References
* http://dev.mysql.com/doc/refman/5.7/en/resetting-permissions.html

##### Set root password on localhost
```sql
SET PASSWORD FOR 'root'@'localhost' = PASSWORD('asdfasdfasdf');
```

##### Set root password from any host
```sql
SET PASSWORD FOR 'root'@'%' = PASSWORD('asdfasdfasdf');
```
