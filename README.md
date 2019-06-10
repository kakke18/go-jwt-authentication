go-jwt-authentication
===
Implement jwt authentication in Go

## Reference
[Go言語で理解するJWT認証実装ハンズオン](https://qiita.com/po3rin/items/740445d21487dfcb5d9f)

## Usage
```
cp .env.example .env
gp run main.go

curl localhost:8080/public
curl localhost:8080/auth
curl localhost:8080/private "Authorization: Bearer {JWT token}"
```

## Link
[jwt](https://jwt.io/)

## Author
[kakke18](https://github.com/kakke18)
