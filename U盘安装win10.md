## uefi引导和gpt分区的U盘启动
# 1.不能直接把window镜像复制到U盘。uefi引导无法识别U盘。
# 2.不要用软碟通之类的工具。默认的制作U盘启动为fat32格式，无法加载超过4g的文件如install.wim。
# 3.最后的解决方法。可以用rufus工具
