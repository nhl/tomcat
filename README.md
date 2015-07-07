# Tomcat Connection Pool with Patches

* fixes an odd issue with validation query resulting in subsequent empty ResultSet on MySQL 

To build:

```
cd modules/jdbc-pool
ant build -Dcompile.source=1.7 -Dcompile.target=1.7
```
