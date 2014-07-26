iVoter
========
>To be or NOT to be ? 真的猛士，也从来不畏惧艰难选择。

iVoter是一个专门用来克制集体恐惧症的工具。从班委选举到科技节作品方案，它可以通过计票的形式帮助你或者你的班级做出决定。班主任也再也不怕计票同学数错票了。

你还可以通过`AirPlay镜像`功能将计票界面投影到大屏幕上，实现集体监票。

##知识点
> UITableView 和 UITableViewCell的数据源、委托和事件响应
> UIButton按钮事件和UILabel文本修改
> 条件判断
> 自定义类（Class）、数组（Array）和方法（func）

开始之前，我们需要先了解下面的一些简单语法
```swift
//定义类“car”
class car{
    var numberOfWheel = 1 //定义属性，初始值1，类型推导为Int
    //定义方法，功能为打印属性的内容
    func print(){
        println("有\(numberOfWheel)个轮子")
    }
}

let myCar = car() //实现类car，生成对象myCar
myCar.numberOfWheel = 4 //定义myCar的属性
myCar.print() //调用myCar方法，打印属性
```

##升级APP
  你可以下载源代码来升级APP的功能。例如：

- 定义投票对象名称
- 计票结束后显示胜出参选人
- 增加减票功能

##截图预览

![截图1](https://github.com/Beiyi/vote/blob/master/preview/ScreenShot1.png)
=======
![截图2](https://github.com/Beiyi/vote/blob/master/preview/ScreenShot2.png)

