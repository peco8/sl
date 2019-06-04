# sl

## How to run

1. Run.
```
# on local
docker run --name <name>_sl -d -p 8080:8080 peco8/sl

# on CF
cf push <name>_sl -d <domain> --docker-image peco8/sl
```

2. Try it on your browser.
 - `http://localhost:8080`
 - `http://<host-ip>:8080`
