# Build
```
docker build -t cannin/pushbullet-cli .
```

# Run
```
docker run --name pb --rm -e PUSHBULLET_KEY=KEY -t cannin/pushbullet-cli pb push 'hello world'
```
