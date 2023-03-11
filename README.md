# Weather&Activity API 

## Installation

1. Open Command Prompt.

2. Clone Git repo:
```
git clone https://github.com/redarmyman/activity-app-enviroment.git activity
```
3. Go to newly created directory:
```
cd activity
```
4. Execute:
```
docker-compose up -d --build
```
5. Enter application container:
```
docker-compose exec php /bin/bash
```
6. Install necessary libraries:
```
composer install
```

Swagger documentation should be available at: http://localhost:8080/v1/doc
