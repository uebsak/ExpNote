# excel2016右键新建文件无法打开
解决方案 ：
----
1.按WIN+R，运行regedit，打开注册表编辑器。
 
2.然后在HKEY_CLASSES_ROOT下找到.xls和.xlsx，右键单击新建-项，命名为shellNew，然后在建立的项中新建-字符串，命名为NullFile，值为空。
---
上述方案显然不行
---
已经有shellNew了，里边的FileName的值倒是全部指向Office的模板目录。
