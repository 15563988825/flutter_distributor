# exe

## 必要条件

* [`Inno Setup 6`](https://jrsoftware.org/isinfo.php)``

## 用法

将 `make_config.yaml` 添加到你的项目 `windows/packaging/exe` 目录。

```yaml
// AppId 的值唯一标识此应用。
// 不要在其他应用的安装程序中使用相同的 AppId 值。
appId: 5B599538-42B1-4826-A479-AF079F21A65D
appPublisher: LeanFlutter
appPublisherUrl: https://github.com/leanflutter/flutter_distributor
```

运行：

```
flutter_distributor package --platform windows --targets exe
```

> PowerShell 暂未支持，请使用 Git Shell 并执行 `flutter_distributor.bat`。

## 相关链接

[https://jrsoftware.org/isinfo.php](https://jrsoftware.org/isinfo.php)
