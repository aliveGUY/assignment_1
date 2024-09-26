
### Build
```bash
docker build -t blazorapp-img .
```

### Run
```bash
docker run -it -p 8088:8088 --name blazorapp-cnt blazorapp-img
```