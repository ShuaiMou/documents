# 1.数据类型，变量常量，类型判断，拼接字符串

```swift
import UIKit
//单行注释

/*
 多行注释
 */


//变量
var a:String = "hello world"
var b:Int = 10
var c:Float = 1.2
var d:Double = 1.5
var e:Bool = true
var f:Character = "H"

//常量
let g:Int = 12

//类型推断
var str = "推断出是字符串"

//判断数据类型
type(of: str)

//输出语句
print(a,b,e)

//拼接字符串
print(a + str)

print(a + " \(b)")

print("\(true) - \(100) - \(1.5) - " + a)

```

# 2.类型别名，类型转换

```swift
//类型别名
typealias dog = Int
var a:dog = 10
var b:Int = 30
print(a, b)

//类型转换和 ?? 语法
var c = 40
print("值等于 = " + "\(c)")
print("值为 = " + String(c))

print("值为 = " + String(true))

var d = "78"
var e = "hsuhu"
print(Int(d) ?? 100)
print(Int(e) ?? 100)

print(Int(100.5))
print(Bool(1))  //非0都是 true

```



# 3.可选类型和解析值

```swift
//可选类型
var a:Int? = nil
var b:Int? = 10
print(a)  //nil
print(b) // Optional(10)

print(a ?? 200) //200
print(b ?? 100) //10

print(b!) // 10

var str:String? = "hello world"

if str==nil {
    print("str 没有值")
}else{
    print("str 的值 = \(str!)")
    
    print("str 的值为 = " + String(str!))
}
```



# 4.元组类型

```swift

```



# 5.基础运算符

# 6.if语句，可选类型绑定，隐式展开

# 7.switch case 和 fallthrough 穿透

# 8.区间运算符，for in 循环 continue 和 break

# 9.while 循环和 repeat while循环

# 10.String基础操作

# 11.Array 数组

# 12.set 集合

# 13.dictionary 字典集合

# 14.函数定义，函数参数，assert 断言

# 15.guard 语句

# 16.inout 关键字，函数类型

# 17.匿名函数作为函数的参数

# 18.函数作为返回值，内嵌函数

# 19.匿名函数的简写方式

# 20.定义枚举，设置枚举值

# 21.枚举相关值，遍历枚举

# 22.结构体定义使用

# 23.计算属性的使用

# 24.属性观察的使用 willset 和 didset

# 25.下标语法 subscript

# 26.类的定义使用，类的实例是传引用

# 27.类中使用属性计算，属性观察，下标语法

# 28.any 和 anyobject 类型

# 29.类的继承

# 30.向下类型转换

# 31.方法重载

# 32.重写方法，final 禁止继承重写

# 33.属性计算观察和下标的继承和重写

# 34.多态调用方法和属性的问题

# 35.类型判断处理，对象相等性判断

# 36.扩展 extension，泛型

# 37.协议 protocol

# 38.延迟属性 lazy

# 39.普通初始化器，可失败初始化器

# 40.必要初始化器，结构体成员初始化器，闭包设置属性值

# 41.自动内存释放，反初始化器

# 42.循环强引用，弱引用 weak

# 43.无主引用 unowned

# 44.闭包循环引用，定义捕获列表

# 45.可选链展开

# 46.尾随闭包

# 47.错误捕获和处理

# 48.泛型类型限定，协议关联类型

# 49.访问权限简单说明

# 50.总结