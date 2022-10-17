# 常用命令


| 命令     | 英文全拼                 | 作用                 |
| -------- | ------------------------| ------------------------ |
| [ls](#ls) | list files | 列出目录及文件名 |
| [cd](#cd) | change directory | 切换目录 |
| [pwd](#pwd) | print work directory | 显示目前的目录 |
| [mkdir](#mkdir) | make directory | 创建一个新的目录 |
| [rmdir](#rmdir) | remove directory | 删除一个空的目录 |
| [cp](#cp) | copy file | 复制文件或目录 |
| [rm](#rm) | remove | 删除文件或目录 |
| [mv](#mv) | move file | 移动文件与目录，或修改文件与目录的名称 |


## ls
在 `Linux` 系统当中， `ls` 命令可能是最常被运行的。

### 选项与参数
- `-a` ：全部的文件，连同隐藏文件 (开头为 . 的文件) 一起列出来
- `-d` ：仅列出目录本身，而不是列出目录内的文件数据
- `-l` ：长数据串列出，包含文件的属性与权限等等数据
- `-h` ：以容易理解的格式列出文件大小 (例如 1K 234M 2G)

### 常用范例

例一：列出 `/sys` 文件夹下的内容

#### 命令
```
ls /sys
```

#### 输出
```
block  bus  class  dev  devices  firmware  fs  hypervisor  kernel  module  power
```

例二：列出 `/sys` 文件夹下的内容 (以列表的形式)

#### 命令
```
ls -l /sys
```

#### 输出
```
total 0
drwxr-xr-x   2 root root 0 Sep 21 08:48 block
drwxr-xr-x  22 root root 0 Sep 19 03:12 bus
drwxr-xr-x  33 root root 0 Sep 17 08:43 class
drwxr-xr-x   4 root root 0 Sep 17 07:21 dev
drwxr-xr-x  16 root root 0 Sep 13 02:18 devices
drwxr-xr-x   6 root root 0 Sep 17 08:43 firmware
drwxr-xr-x   7 root root 0 Sep 13 02:18 fs
drwxr-xr-x   2 root root 0 Sep 21 08:48 hypervisor
drwxr-xr-x  15 root root 0 Sep 13 02:18 kernel
drwxr-xr-x 118 root root 0 Sep 19 01:43 module
drwxr-xr-x   3 root root 0 Sep 21 08:48 power
```

## cd

## pwd

## mkdir

## rmdir

## cp

## rm

## mv