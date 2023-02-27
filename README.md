

# Playground

```
 # Starting.
docker run --rm --name njs_example  -v $(pwd)/conf/playground.conf:/etc/nginx/nginx.conf:ro -v $(pwd)/njs/:/etc/nginx/njs/:ro -p 80:80 -p 443:443 -d nginx
  
# Stopping.
docker stop njs_example
```