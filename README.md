# Linux-

一、命令格式

[root@localhost ~]#
root  当前登录用户，root为管理员
localhost  当前计算机主机名
~  当前所在目录（pwd:可显示当前所在位置）
$  普通用户提示符   #  超级用户提示符

命令 [选项] [参数]
注意：-a 等于 --all

1.ls:查询目录中内容
  ls [选项] [文件或目录]
选项： -a  显示所有文件，包括隐藏文件
      -l  显示详细信息
      -d  查看目录属性
      -h  人性化显示文件大小（-lh）
      -i  显示inode

点开头的文件是隐藏文件

权限：-rw-r--r--
     -文件类型（-：文件  d：目录  l：软链接文件）（第一位）
     ---：u所有者  ---：g所属组  ---：o其他人  r读 w写 x执行（后九位）

2.mkdir -p [目录名] ： 建立目录
  -p 递归创建（例：mkdir -p a/b）

3.cd [目录] ： 切换所在目录
  cd ~  进入当前用户的家目录 （直接cd也行）
  cd -  进入上一次目录
  cd ..  进入上一级目录
  cd .  进入当前目录
  
4.pwd: 查询所在目录位置
