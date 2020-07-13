# 環境構築
## 前提
docker,docker-composeが利用できる

## setup
### imageビルド
`$ docker-compose build`

### database.yml作成
`$ cp config/database.yml.default config/database.yml`

### db作成
`$ docker-compose run --rm web rails db:create`

### up
`$ docker-compose up -d --build`

### stop
`$ docker-compose stop`

### container delete
`$ docker-compose down`
