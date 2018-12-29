# main.m
从 main.m 开始

## 声明
版本号 Xcode 10.1

## 简介
main.m 里面是什么？

```
int main(int argc, char * argv[]) {
    @autoreleasepool {
        return UIApplicationMain(argc, argv, nil, NSStringFromClass([AppDelegate class]));
    }
}
```

这是什么？

## 预告
0. 自动释放池的前世今生
0. C 语言和 OC 的关系
0. main 函数
0. UIApplication类
0. 编译 Runtime 源码

## 参考
[自动释放池的前世今生 ---- 深入解析 autoreleasepool](https://www.jianshu.com/p/b901d7fcb57a)
[autoreleasepool探究](https://www.jianshu.com/p/b901d7fcb57a)
[编译Runtime源码](https://blog.csdn.net/wotors/article/details/54426316)

