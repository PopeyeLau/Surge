# Surge

- [人人视频去广告+原画](./rrtv.js) ([勋章列表](./response.dump))



---

> 增加配置如下

```
[Script]
http-response ^https:\/\/api\.rr\.tv(\/user\/profile|\/ad\/getAll) script-path=https://raw.githubusercontent.com/popeyelau/Surge/master/rrtv.js

[MITM]
hostname = api.rr.tv
```


---
[Surge Scripting](https://manual.nssurge.com/http-processing/scripting.html)


