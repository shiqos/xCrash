# Develop

## 背景
目前 xCrash 很久没更新, 其中存在一些兼容性问题:
1. 对 AAB 或 android:extractNativeLibs=false flag的支持
2. Android 15 anr 捕获
3. Android 15 page 16K
等等

在官方暂无更新的基础上，我们在自己仓库继续开发 xCrash，希望能够帮助到更多的开发者。

## 目标
修复 xCrash 中的一些问题

## 计划
| 功能                  | 是否支持 | 支持版本  |
|---------------------|------|-------|
| AAB支持               | 是    | 3.1.1 |
| Android 15 anr      | 否    | -     |
| Android 15 page 16K | 否    | -     |

## 使用
```
implementation("io.github.shiqos:xcrash-android-lib:<version>")
```

初始化参考: [README.md](https://github.com/iqiyi/xCrash/blob/master/README.md)