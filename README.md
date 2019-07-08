# hello
#编写第一个go
package main
import "fmt"
func main () {
   fmt.Printf("hello.world\n")
}
#执行go install，此命令会构建 hello 命令，产生一个可执行的二进制文件。
go 工具只有在发生错误时才会打印输出，因此若这些命令没有产生输出， 就表明执行成功了。 
若你已经将 $GOPATH/bin 添加到 PATH 中了，只需输入该二进制文件名即可：
[root@master hello]# hello
hello.world
