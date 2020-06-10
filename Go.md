# Go

package：同一个文件夹内的源文件，不同源文件的导出符号在package内部可见，类比于C/C++的编译单元。

module：包含多个package。

repository：包含一个或多个module，使用go.mod声明modules路径：module内的package import前缀