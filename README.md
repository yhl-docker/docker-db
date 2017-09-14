# docker-db
database

# mongo认证设置
- 进入docker
- `mongo admin`
- `db.createUser({user:'user', pwd:'password', roles:[{role:'userAdminAnyDatabase', db:'admin'}]});`