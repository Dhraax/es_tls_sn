
#Deploy IN DEV

Run docker-compose -f docker-compose.setup.yml run --rm certs
Run docker-compose up -d


#docker-compose.production

Run docker-compose -f docker-compose.setup.yml run --rm certs
Run docker-compose -f docker-compose.production.yml up
Run docker-compose down or press ctrl + x/c
Run docker-compose -f docker-compose.setup.yml run --rm certs (again)
Run docker-compose -f docker-compose.production.yml up -d (again)
