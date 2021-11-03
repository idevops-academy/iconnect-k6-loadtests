# iconnect-k6-loadtests

### Require nodejs
git clone repourl
npm intall
npm run test


### Run Using Docker Compose
docker-compose up -d influxdb grafana
docker-compose run -v $PWD/samples:/scripts k6 run /scripts/k6-script.js -e appurl={{insertappurl}}
