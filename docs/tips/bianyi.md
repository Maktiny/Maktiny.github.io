## c语言编译过程

### 预处理

1. 引入头文件，删除注释
```
 gcc -E a.c -o a.i 

```

### 编译
1. 生成汇编代码
```
 gcc -S a.i -o a.s
```

### 汇编
1. 生成二进制机器代码
```
 gcc -c a.s -o a.o
```

### 链接
1. 链接生成可执行文件(二进制)
```
gcc a.o -o a
```
