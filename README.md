# WebAPIAsService
将WebAPI作为服务运行



## 创建服务：

```
sc create WebAPIAsService binPath={绝对路径}\WebAPIAsService.exe
```

## 启动服务：

```
sc start WebAPIAsService
```

## 停止服务：

```
sc stop WebAPIAsService
```

## 删除服务：

```
sc delete WebAPIAsService
```



## 访问：
访问 [http://localhost:5000/weatherforecast](http://localhost:5000/weatherforecast) 返回一段 Json 即为服务部署正常；
