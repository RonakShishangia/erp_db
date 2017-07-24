# ERPO system databse
- Complete database of ERP system.

### Total tables : 378
 - Error like : *Specified key was too long; max key length is 767 bytes*
### If error occurs
- Login in you mariaDB.
- fire these two commands.
  - set global innodb_file_format = BARRACUDA;
  - set global innodb_large_prefix = ON;
