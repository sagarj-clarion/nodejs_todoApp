$ npm install  
$ DEBUG=todoApp ./bin/www

--------------------------------------------------------------------------
Post  
http://localhost:3000/todos  
i/p: {"name":"test","completed":"true","note":"test"}  
o/p: {
"__v": 0
"name": "test"
"completed": true
"note": "test"
"_id": "568e2e2c456c46fe31ddb930"
"updated_at": "2016-01-07T09:21:48.578Z" }

--------------------------------------------------------------------------
Get  
http://localhost:3000/todos/568e2e2c456c46fe31ddb930  
o/p: {
"_id": "568e2e2c456c46fe31ddb930"
"name": "test"
"completed": true
"note": "test"
"__v": 0
"updated_at": "2016-01-07T09:21:48.578Z" }

--------------------------------------------------------------------------
Put  
http://localhost:3000/todos/568e2e2c456c46fe31ddb930  
i/p: {"name":"testa","completed":"true","note":"test"}  
o/p: {
"_id": "568e2e2c456c46fe31ddb930"
"name": "testa"
"completed": true
"note": "test"
"__v": 0
"updated_at": "2016-01-07T09:21:48.578Z" }

--------------------------------------------------------------------------
Delete  
http://localhost:3000/todos/568e2e2c456c46fe31ddb930  
o/p: {
"_id": "568e2e2c456c46fe31ddb930"
"name": "testa"
"completed": true
"note": "test"
"__v": 0
"updated_at": "2016-01-07T09:21:48.578Z" }
