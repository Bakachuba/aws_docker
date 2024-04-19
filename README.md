# Security: 
- Unprivileged user (instead of root)
- Real env replaced to samples

```
envsubst < 
/etc/nginx/default.conf.tpl > 
/etc/nginx/conf.d/default.conf
```
