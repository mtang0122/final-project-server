# Full-Stack CRUD Application

Group: Marcus Tang - mtang0122

<br/>

## Common Errors You May Encounter
### Error: password authentication failed for user "postgres"
This error is related to the user password you set for your own local Postgres database. 
#### Solution:
In the `server-starter-code/database/utils/configDB.js` file, replace the `dBpwd` value with your password for Postgres database.

```
  const dbName = 'starter-server';
  const dbUser = 'postgres';
  const dbPwd = '<your password>';
```
