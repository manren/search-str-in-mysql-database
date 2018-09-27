# search-str-in-mysql-database
用来在全库寻找特定字符串，在迁移项目域名等情况可用

参数1 数据库名

参数2 要查找的字符串

命令行调用

CALL `proc_FindStrInAllDataBase` ('dbname','findstr');
