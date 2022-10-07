# Blocking User 

### Описание:

#### Introduction
Блокирование пользователя по UUID

#### Authentication
Авторизация через Berear token

#### Error Codes
- 401, 403
- Нет никаких exception, данная функция void

#### Описание запроса
- Request method: Post
- Url: http://localhost:8087/api/users/block?userUuid={userUuid}
- Params: userUuid
- Authorization: Berear Token
- Expected Responce: Status Code 200

#### Example of postman request:
- Request method: Post
- Url: http://localhost:8087/api/users/block?userUuid=dc145f72-462b-11ed-b878-0242ac411567
- Authorization: Berear Token "eyJhbGciOiJSUzI1NiIsInR5cCIgOiAiSldUIiwia2lkIiA6ICI5V0R1M0VjM0t4aFdjS1o5TU5kWVR4d0ZadkVzcGNYajNLTVctSmhLTkRRIn0"
- Responce: Status Code 200
