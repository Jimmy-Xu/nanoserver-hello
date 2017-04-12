# FAQ

## FAQ 1
```
编译后的exe直接复制到nanoserver中，执行后直接退出，且无任何输出
```

## 原因：
```
nanoserver中可能缺少动态链接库
```

## 解决：
```
git bash下用ldd命令查看exe依赖的dll，然后将这些dll复制到nanoserver中，即可正常运行exe
```
