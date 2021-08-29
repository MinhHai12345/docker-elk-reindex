## Copy file .env
	cp .env.example .env
## Run elasticsearch + kibana local docker-compose-elasticsearch-local.yml
	docker-compose -f docker-compose-elasticsearch-local.yml up -d
## Run losgtash 
	docker-compose up -d
