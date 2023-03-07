## BigSerial类型
BIGSERIAL是PostgreSQL数据库中的一种数据类型，它是一种自动增长的64位整数类型，类似于MySQL中的AUTO_INCREMENT。

基于sequence的自增主键

验证sql语句
```sql
CREATE TABLE my_table (
   id BIGSERIAL PRIMARY KEY,
   name TEXT NOT NULL,
   age INTEGER
);
\d
```