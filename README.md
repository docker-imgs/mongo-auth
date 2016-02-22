## mongo-auth
A simple wrapper on top of mongo container adding root user and forcing authentication.

In order to use it PASSWD should be passed via env.
`docker run -d -e PASSWD=<your strong password here> zanjs/mongo-auth`

## mongo 用户认证连接


连接 root 用户 密码为您设置的密码

`docker run -d -e PASSWD=<设置数据库密码> zanjs/mongo-auth`
