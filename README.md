# lambda crud
## install
- npm install

## deploy
- sls deploy

## end points
### index
- curl https://url/todos
### show
-	curl https://url/{id}
### create
- curl -X POST https://url/todos --data '{"key" : "data"}'
### update
- curl -X PUT https://url/todos/{id} --data '{"key" : "data"}'
### delete
- curl -X DELETE https://url/todos/{id}
