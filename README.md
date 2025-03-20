# Common-Error-fix-nh-apt-get-update-apt-get-upgrade
While doing apt-get update or apt-get upgrade, you might encounter an error. Here is the fix
## fix
* `nano usr/lib/cnf-update-db/`
 Now I want you to search for        `col.create(db)` and I only want you to delete this part of col.create`(db)`
