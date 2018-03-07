 ### 要点

 1. 如下例子，传非数字类型，均按照字符对应的ASCII对应的十进制值进行计算。
 
 
    package main    
    import "fmt"
    
    func add(x int, y int) int {
    	return x + y
    }
    
    func main() {
    	fmt.Println(add(0, 13))
    }
     