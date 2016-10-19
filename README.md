# csharp-seed-server

## data base installation

Projects runs with entity framework.

## services resume

Base URL **"http://localhost:????/api"**

Header **Content-Type: application/json**

Header **x-access-token:||token||**

## public

POST **/p1/login** _OBJECT_

## private

POST **/v1/logout** _OBJECT_

GET **/v1/users** _ARRAY_

POST **/v1/users** _OBJECT_

GET **/v1/users/:user_id** _OBJECT_

DELETE **/v1/users/:user_id** _OBJECT_

PUT **/v1/users/:user_id** _OBJECT_

## especial

**Content-Type: multipart/form-data**

POST **/p1/files** *excel*
Form ['file_name']
