# d7-jenkins
d7-jenkins

 history
curl
lsb_release -dc
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
nvm --version
command -v nvm
node
exit
nvm
command -v nvm
nvm --version
nvm install --lts
npm --version
node --version
sudo apt-get install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
sudo apt-get install docker-ce
sudo gpasswd -a $USER docker
echo $USER
exit
echo $USER
sudo gpasswd -a $USER docker
sudo apt-get install docker-ce
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
sudo apt-get install docker-ce
sudo gpasswd -a $USER docker
sudo service docker start
docker run hello-world
id
exit
id
docker run hello-world
docker ps -a
docker stop e6a4c64d9273
docker image ls
docker image rm feb5d9fea6a5
docker rm e6a4c64d9273
docker image rm feb5d9fea6a5
docker ls -a
docker image ls
docker ps -a
docker image ls
cd /etc/docker/
ls -ltra
cat key.json
sudo cat key.json
vi daemon.json
ls -ltr
sudo vi daemon.json
ls -ltr
sudo service docker restart
docker ps -a
sudo apt-get install postgresql-10
sudo apt-get install postgresql-12
psql
pg_lsclusters
sudo pg_ctlcluster 9.6 main start
sudo pg_ctlcluster 12 main start
pg_lsclusters
sudo service postgresql restart
psql
sudo -u postgres -i
sudo -u postgres createuser --superuser $USER; sudo -u postgres createdb $USER
psql
sudo -u postgres createdb movie_catalog
psql
sudo -u postgres deletedb mukul
sudo -u postgres dropdb mukul
psql
sudo -u postgres createuser --superuser $USER;
psql movie_catalog
curl -s http://localhost:3000/titles?s=Fight+Club
curl -s http://localhost:3000/titles/tt0137523
exit
psql
pg_lsclusters
sudo service postgresql restart
pg_lsclusters
psql
sudo -u postgres createdb movie_catalog
psql movie_catalog
cd /mnt/c/mproj/vscode/movie-catalog/
npm init
node -v
git status
git diff
ls -ltr
mkdir src
cd src/
cd ..
npm install sequelize@4.43.0 pg@7.8.1
npm install express@4.16.4 cors@2.8.5 body-parser@1.18.3
npm test
npm start
node ./src/index.js
pg_lsclusters
npm start
psql movie_catalog
id
psql movie_catalog
sudo -u postgres dropdb movie_catalog
psql movie_catalog#
psql
npm start
psql movie_catalog#
psql movie_catalog
psql
psql -u postgres
psql --username=postgres
psql --username=muku;
psql --username=mukul
psql \d
psql \l
psql --username=pgadmin --list
psql list
psql
psql -h
psql --help
psql --list
sudo -u postgres createdb movie_catalog
psql --list
psql
psql movie_catalog
psql --username=pgadmin --list
npm start
psql movie_catalog
npm install dotenv@6.2.0 node-fetch@2.3.0
npm start
psql -v
psql --version
npm start
ls -ltr
npm start
npm install --save pg pg-hstore # Postgres
npm install --save sequelize # Postgres
node install add sequelize-cli -D
npm install add sequelize-cli -D
npm install sequelize-cli -D
npm sequelize-cli init
npx sequelize-cli init
npx sequelize-cli db:create
psql
psql --username=postgres
psql --username=mukul
sudo -u postgres psql
npx sequelize-cli db:create
psql --list
sudo -u postgres dropdb movie_catalog
sudo -u postgres dropdb database_development
npx sequelize-cli db:create
psql --list
npx sequelize-cli model:generate --name User --attributes firstName:string,lastName:string,email:string,password:string
npx sequelize-cli db:migrate
psql --list
psql movie_catalog
npx sequelize-cli db:seed:all
npx sequelize-cli seed:generate --name user
npx sequelize-cli db:seed:all
psql movie_catalog
npm start
psql movie_catalog
npm start
psql
npm
npm -v
id
sudo apt install mysql-server
mysql
sudo mysql_secure_installation
sudo service mysql start
ls /var/run/mysqld/mysqld.sock
ls -ltr /var/run/mysqld/mysqld.sock
mysql
sudo mysql_secure_installation
sudo mysql
mysql -u sammy -p
mysql -u mukul -p
systemctl status mysql.service
sudo systemctl status mysql.service
sudo systemctl start mysql
sudo mysqladmin -p -u sammy version
sudo mysqladmin -p -u mukul version
mysql
mysql -u mukul -p
clear
mysql -u mukul -p
ps aux |grep mysql
ps aux |grep postgres
service postgresql status
service mysql status
service mysql start
sudo service mysql start
service mysql status
sudo service mysql stop
sudo usermod -d /var/lib/mysql/ mysql
sudo service mysql start
service mysql status#
mysql -u mukul -p
show tables;
mysql -u mukul
mysql -u mysql
mysql -u mysql -p
sudo mysqladmin -p -u mukul version
mysql -u mysql -p
sudo mysqladmin -p -u mukul version
mysql
mysql -u mysql -p
mysql -u mukul -p
docker
docker -v
docker ps
docker build
docker build -t .
pwd
ls -ltr
docker build .
docker ps
systemctl
systemctl start docker
sudo service docker start
docker ps
sudo service --status-all
docker ps
history
