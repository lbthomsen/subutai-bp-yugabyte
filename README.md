# subutai-bp-yugabyte
Subutai Blueprint for YugabyteDB

## Port

Where PostgreSQL is using port 5432 by default, YugabyteDB uses 5433.  After deploy of Blueprint, you can connect to your YugabyteDB database using the PostgreSQL client:

```
psql -h <bp domain name> -p 5433 -U yugabyte yugabyte
```

Default password is "yugabyte".