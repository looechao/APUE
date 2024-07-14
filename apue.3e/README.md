## 环境配置

系统环境以Fedora 40为例

### 下载随书资源

[随书资源](http://www.apuebook.com/code3e.html)

解压
```bash
tar src.3e.tar.gz
```
### 配置库文件

```bash
sudo yum install libbsd libbsd-devl
cd apue.3e
make
......
sudo cp ./include/apue.h /usr/include/
sudo cp ./lib/libapue.a /usr/lib/
```

### 编译
```bash
gcc filename.c -lapue
```

