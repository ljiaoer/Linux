Linux命令：
. 		 代表此层目录
..  	 代表上层目录
-   	 代表前一个工作目录
~   	 代表“目前用户身份”所在主文件夹
~account 代表account这个用户主文件夹
cd		切换目录（Change Directory）
pwd		显示当前目录(Print Working Directory)
mkdir	新建一个新的目录(Make Directory)
rmdir	删除一个空的目录
ls		查看文件与目录(list)
cp		复制文件或目录(copy)
rm 		移除文件或目录（remove）
mv		移动文件或目录或更名(move)
文件内容查阅
cat		由第一行开始显示文件内容（concatenate）
tac		由最后一行开始显示文件内容，tac是cat的倒写形式
nl		显示的时候，顺便显示行号
more	一页一页的显示文件内容
less	与more类似，但是比more更好的是，它可以一页一页往前翻
head	只看前几行，默认前10行，语法：head -n x（10）
tail	取出后面几行，语法同head
touch	修改文件时间或者创建文件夹
file	查看文件类型
whereis 查找特定文件
find	查找文件
gzip	压缩文件
bzip2	压缩文件
zcat	读取压缩文件
bzcat	读取压缩文件
dump    备份
restore 文件恢复
