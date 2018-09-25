# gcp-chacher
nginxでgcpにリバースプロキシし、ファイルをキャッシュする

# quote
* [docker-nginx/mainline/alpine at ddbbbdf9c410d105f82aa1b4dbf05c0021c84fd6 · nginxinc/docker-nginx](https://github.com/nginxinc/docker-nginx/tree/ddbbbdf9c410d105f82aa1b4dbf05c0021c84fd6/mainline/alpine)
* [Nginx as Google Cloud Storage Cache](https://gist.github.com/touhonoob/5364f6c9099609c826a4)

# start
`$ docker-compose up`

# comfirm jpg
`http://localhost:5555/test/test_180801222701.jpg`

# TODO
* `ngx_cache_purge` をインストールしてキャッシュファイルの削除機構を実装