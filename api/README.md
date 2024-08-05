### Build Image

```sh
docker build -t image_name -f api/Dockerfile .
```

### Run Container

```sh
docker run --env-file ./api/.env -p 8000:8000 image_name
```
