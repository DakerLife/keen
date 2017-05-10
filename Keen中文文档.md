# Keen 中文文档

### 获取源码

源码地址：[Github](https://github.com/DakerLife/keen)

``` git clone https://github.com/DakerLife/keen.git ```

### 环境要求

PHP : 5.6+
MYSQL : 5.6+

### 安装Composer
``` curl -sS https://getcomposer.org/installer | php ```

### 进入项目目录
``` cd moell-blog ```

### 安装项目依赖
``` composer install ```

### 配置数据库信息

创建数据库，将数据库信息填写至``` /core/config/database.php ```

### 设置目录权限

```
chown -R www:www  log/
chmod -R 755 log/ 
```

框架实例 ：[keen.skill86.com](keen.skill86.com)

