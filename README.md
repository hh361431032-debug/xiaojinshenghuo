# 小金生活

静态 PWA：菜谱、采购、餐厅、高德地图。

## 配置
编辑 `config.js`，填写高德 Web JS API 的 `key` 和 `securityJsCode`。

## 本地运行
```powershell
python -m http.server 8080
```
打开 http://localhost:8080

## 默认账号
admin / 123456
wife / 123456

数据目前保存在浏览器 localStorage，各账号独立。