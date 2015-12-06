### Run this:
```
docker-compose up
```
**WARNING: localhost will actually be your `docker-machine ip default` on your machine.** 
### Grafana Configuration 
```
http://localhost:3000/
Credentials: admin/admin
```

### InfluxDb Configuration
``` 
host: http://localhost:8083/
Credentials: root/root
```

### Import some data
```
cpu_load_short,host=server02 value=0.67
cpu_load_short,host=server02,region=us-west value=0.55 1422568543702900257
cpu_load_short,direction=in,host=server01,region=us-west value=2.0 1422568543702900257
```
