# laravel-admin-demo

`laravel-admin-demo` 一个调试的 demo.

# 安装

```
composer require encore/laravel-admin "dev-master"
```

在`config/app.php`加入`ServiceProvider`:

```
Encore\Admin\Providers\AdminServiceProvider::class
```

然后运行下面的命令完成安装：

```
php artisan vendor:publish --tag=laravel-admin
php artisan admin:install
```

最后在浏览器打开 `http://localhost/admin/` ,使用用户名 `admin` 和密码 `admin`登陆.

# 相关链接
[laravel-admin](https://raw.githubusercontent.com/z-song/laravel-admin/)
