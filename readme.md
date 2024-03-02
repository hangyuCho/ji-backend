### Run the app
```bash
docker-compose up
```

### Test the app
```bash
curl http://localhost:3000
```

### Stop the app
```bash
docker-compose down
```

### Clean up
```bash
docker-compose down --volumes
```

## Dockerize a Node.js app

### Create a Node.js app
```bash
mkdir node-docker
cd node-docker
npm init -y
npm install express
```

### Create a simple Express app
```javascript