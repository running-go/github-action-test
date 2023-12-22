# github-action-test
github action test dev


# node-js add user to mongo 
## node本地服务启动
```shell
node ./app.js
```
## docker容器方式启动


添加用户
```shell
curl -XPOST -H 'Content-Type:application/json' 'http://localhost:3001/api/user' -d '{"username":"hello","address":"爷爷泡的茶"}'
```
查看当前用户
```shell
curl -XGET -H 'Content-Type:application/json' 'http://localhost:3001/api/users'
```