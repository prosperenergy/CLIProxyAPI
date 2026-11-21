# Valkey

This repo speaks the Redis/Valkey RESP protocol for usage subscriptions (`internal/redisqueue` and `internal/api/redis_queue_protocol.go`). It does not run a Redis or Valkey server of its own.

- Clients can use `valkey-cli` or any Redis OSS client against the protocol endpoint.
- `github.com/redis/go-redis` remains an indirect client library and is Valkey-compatible.
- There is no `redis:*` compose image to swap here.
