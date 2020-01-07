# go-yolo
使用golang调用darknet接口

>备注: darknet官方,有python调用接口的脚本噢

### 快速开始
假设你已经完成了darknet的编译安装
1. 切换到darknet的工作目录,然后执行命令:
    ```
    cd darknet && git clone https://github.com/bzyy/go-yolo.git  && cd go-yolo
    ```

2. 执行: `go run detector.go`
![demo](https://raw.githubusercontent.com/bzyy/go-yolo/master/demo.gif)

### 更新日志
> 使用过程中,发现有内存溢出bug,暂未解决。 在 `go-yolo.h` 的第56行 `dets[j].prob[i]`. prob[i]可能为空  
推荐使用官方提供的python接口

### 参考资料
+ https://github.com/yummybian/go-yolo
+ https://github.com/gyonluks/go-darknet
