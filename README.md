## Parcel

### 安装


```javascript
    npm

    npm install -g parcel-bundler
```

### 运行

```javascript
    
    parcel index.html

    或者

    //package.json
    "script": {
        "dev": "parcel index.html"
    }

    修改端口
    "script": {
        "dev": "parcel index.html -p <port>"
    }

```

### 服务端渲染

如果在自己构建的服务器下运行 在watch模式下运行Parcel 更改文件时候 Parcel依然会热替换文件 只是不启动web服务器


```javascript
    //package.json
    "script": {
        "dev": "parcel watch index.html"
    }
```

