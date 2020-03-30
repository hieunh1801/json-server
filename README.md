# json-server
json server

### scrips
```bash
# install
npm install -g json-server

# run
json-server --watch --port 3000 db.json
```
### query
```txt
-- get all
http://localhost:3000/users

-- query on field
http://localhost:3000/users?first_name="Hieu"

-- full text search
http://localhost:3000/users?q=sona

-- get by id
http://localhost:3000/users/1

-- order
http://localhost:3000/users?_sort=id&_order=DESC

-- pagination
http://localhost:3000/users?_limit=5&_page=2

-- post
http://localhost:3000/users

-- put
http://localhost:3000/users/1

-- delete
http://localhost:3000/users/1
```