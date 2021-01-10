# lambda crud
## install
- npm install

## deploy
- sls deploy

## end points
### index
- curl https://url/voootes
### show
-	curl https://url/{id}
### create
- curl -X POST https://url/voootes --data '{"key" : "data"}'
### update
- curl -X PUT https://url/voootes/{id} --data '{"key" : "data"}'
### delete
- curl -X DELETE https://url/voootes/{id}
