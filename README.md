# rose-gin-embed

## How to use

```go
    router := gin.New()
	
    router.Use(rge.Serve("/", rge.Embed(web.UIStatic)))
```