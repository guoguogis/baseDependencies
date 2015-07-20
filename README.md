##### window下安装：
 
+ 下载、解压、拷贝所有，覆盖client/build文件夹下的同名文件夹及文件。
+ 

##### linux下安装：

+ 下载并解压文件；
+ 拷贝 `node_modules` 文件夹到 `/root/ibase` 下；
+ 拷贝 `node_modules/grunt-cli` 文件夹到 `/usr/local/lib/node_modules` 下；
+ 通过命令 `ln -s /usr/local/lib/node_modules/grunt-cli/bin/grunt /usr/local/bin/grunt` 来设置环境变量；
+ 通过运行 `grunt` 来查看是否已经安装好grunt.
