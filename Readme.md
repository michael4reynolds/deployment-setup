```sh
# local
docker build -t node-dep-example-1 .
docker tag node-dep-example-1 michael4reynolds/node-example-1
docker push michael4reynolds/node-dep-example-1:latest

# remote
docker run -d --rm -p 80:80 michael4reynolds/node-example-1
```

# Adjust EC2 security group in EC2 console to allow http.
