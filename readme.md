git clone https://github.com/hammadali6096/docker_app

cd node-bulletin-board/bulletin-board-app


docker build --tag bulletinboard:1.0 .

docker run --publish 8000:8080 --detach --name bb bulletinboard:1.0

npm install

npm start
