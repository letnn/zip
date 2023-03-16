# zip管理组件

zip压缩解压功能封装

# 开始使用

#### 安装
使用 composer 命令进行安装或下载源代码使用。

```
composer require letnn/zip
```

#### 调用示例
```php
use letnn\Zip;

//压缩文件或文件夹
Zip::zipCreate("./assets", "./assets.zip");

//zip解压缩
Zip::zipExport("./assets.zip", null, true);
```
