 ### 要点

 1. 如下例子，当x不定义类型时，传非数字类型，均按照字符对应的ASCII对应的十进制值进行计算。
 
 ``
    package main    
    import "fmt"
    
    func add(x, y int) int {
    	return x + y
    }
    
    func main() {
    	fmt.Println(add(0, 13))
    }
     
 2. 