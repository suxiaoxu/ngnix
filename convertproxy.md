## 反向代理 ###

    location ~ \.jsp ${
       proxy_pass http://192.168.0.105:8080
    }