# bash基本命令
以下是常用 Bash 命令的简要说明：

命令	简要说明
cd	Change Directory 的缩写；转到指定目录，直接cd是回到m当前用户的默认目录
cd .. 退回到上一级
ls	List 的缩写；列出当前目录中的内容
mkdir	Make Directory 的缩写；在当前目录中创建一个新的目录
pwd	Present Working Directory 的缩写；显示当前工作目录的详细工作路径
touch	创建一个指定名称的空新文件--其实就是新建文件
rm	Remove 的缩写；删除指定文件
rmdir	Remove Directory 的缩写；删除指定目录
cp	Copy 的缩写；拷贝指定文件，使用方法例子：cp source.txt destination.txt  # 文件复制并重命名
cp file.txt /target/dir/       # 复制到指定目录
mv	Move 的缩写；移动指定文件 发现移动到上一个目录可以直接用 .. ,例如 mv 1.txt .. 就可以移动到当前目录到上一层，cp同样适用。
cat	Concatenate 的缩写；在屏幕中显示文件内容，这个可以打开文件查看内容，测试:都只在terminal中显示，所以打开mp4/rmvb等文件会报错，最好还是只打开txt之类的文本文件。

