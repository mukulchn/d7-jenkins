# d7-jenkins
d7-jenkins

 history
1  curl
2  lsb_release -dc
3  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
4  nvm --version
5  command -v nvm
6  node
7  exit
8  nvm
9  command -v nvm
10  nvm --version
11  nvm install --lts
12  npm --version
13  node --version
14  sudo apt-get install apt-transport-https ca-certificates curl software-properties-common
15  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
16  sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
17  sudo apt-get install docker-ce
18  sudo gpasswd -a $USER docker
19  echo $USER
20  exit
21  echo $USER
22  sudo gpasswd -a $USER docker
23  sudo apt-get install docker-ce
24  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
25  sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
26  sudo apt-get install docker-ce
27  sudo gpasswd -a $USER docker
28  sudo service docker start
29  docker run hello-world
30  id
31  exit
32  id
33  docker run hello-world
34  docker ps -a
35  docker stop e6a4c64d9273
36  docker image ls
37  docker image rm feb5d9fea6a5
38  docker rm e6a4c64d9273
39  docker image rm feb5d9fea6a5
40  docker ls -a
41  docker image ls
42  docker ps -a
43  docker image ls
44  cd /etc/docker/
45  ls -ltra
46  cat key.json
47  sudo cat key.json
48  vi daemon.json
49  ls -ltr
50  sudo vi daemon.json
51  ls -ltr
52  sudo service docker restart
53  docker ps -a
54  sudo apt-get install postgresql-10
55  sudo apt-get install postgresql-12
56  psql
57  pg_lsclusters
58  sudo pg_ctlcluster 9.6 main start
59  sudo pg_ctlcluster 12 main start
60  pg_lsclusters
61  sudo service postgresql restart
62  psql
63  sudo -u postgres -i
64  sudo -u postgres createuser --superuser $USER; sudo -u postgres createdb $USER
65  psql
66  sudo -u postgres createdb movie_catalog
67  psql
68  sudo -u postgres deletedb mukul
69  sudo -u postgres dropdb mukul
70  psql
71  sudo -u postgres createuser --superuser $USER;
72  psql movie_catalog
73  curl -s http://localhost:3000/titles?s=Fight+Club
74  curl -s http://localhost:3000/titles/tt0137523
75  exit
76  psql
77  pg_lsclusters
78  sudo service postgresql restart
79  pg_lsclusters
80  psql
81  sudo -u postgres createdb movie_catalog
82  psql movie_catalog
83  cd /mnt/c/mproj/vscode/movie-catalog/
84  npm init
85  node -v
86  git status
87  git diff
88  ls -ltr
89  mkdir src
90  cd src/
91  cd ..
92  npm install sequelize@4.43.0 pg@7.8.1
93  npm install express@4.16.4 cors@2.8.5 body-parser@1.18.3
94  npm test
95  npm start
96  node ./src/index.js
97  pg_lsclusters
98  npm start
99  psql movie_catalog
100  id
101  psql movie_catalog
102  sudo -u postgres dropdb movie_catalog
103  psql movie_catalog#
104  psql
105  npm start
106  psql movie_catalog#
107  psql movie_catalog
108  psql
109  psql -u postgres
110  psql --username=postgres
111  psql --username=muku;
112  psql --username=mukul
113  psql \d
114  psql \l
115  psql --username=pgadmin --list
116  psql list
117  psql
118  psql -h
119  psql --help
120  psql --list
121  sudo -u postgres createdb movie_catalog
122  psql --list
123  psql
124  psql movie_catalog
125  psql --username=pgadmin --list
126  npm start
127  psql movie_catalog
128  npm install dotenv@6.2.0 node-fetch@2.3.0
129  npm start
130  psql -v
131  psql --version
132  npm start
133  ls -ltr
134  npm start
135  npm install --save pg pg-hstore # Postgres
136  npm install --save sequelize # Postgres
137  node install add sequelize-cli -D
138  npm install add sequelize-cli -D
139  npm install sequelize-cli -D
140  npm sequelize-cli init
141  npx sequelize-cli init
142  npx sequelize-cli db:create
143  psql
144  psql --username=postgres
145  psql --username=mukul
146  sudo -u postgres psql
147  npx sequelize-cli db:create
148  psql --list
149  sudo -u postgres dropdb movie_catalog
150  sudo -u postgres dropdb database_development
151  npx sequelize-cli db:create
152  psql --list
153  npx sequelize-cli model:generate --name User --attributes firstName:string,lastName:string,email:string,password:string
154  npx sequelize-cli db:migrate
155  psql --list
156  psql movie_catalog
157  npx sequelize-cli db:seed:all
158  npx sequelize-cli seed:generate --name user
159  npx sequelize-cli db:seed:all
160  psql movie_catalog
161  npm start
162  psql movie_catalog
163  npm start
164  psql
165  npm
166  npm -v
167  id
168  sudo apt install mysql-server
169  mysql
170  sudo mysql_secure_installation
171  sudo service mysql start
172  ls /var/run/mysqld/mysqld.sock
173  ls -ltr /var/run/mysqld/mysqld.sock
174  mysql
175  sudo mysql_secure_installation
176  sudo mysql
177  mysql -u sammy -p
178  mysql -u mukul -p
179  systemctl status mysql.service
180  sudo systemctl status mysql.service
181  sudo systemctl start mysql
182  sudo mysqladmin -p -u sammy version
183  sudo mysqladmin -p -u mukul version
184  mysql
185  mysql -u mukul -p
186  clear
187  mysql -u mukul -p
188  ps aux |grep mysql
189  ps aux |grep postgres
190  service postgresql status
191  service mysql status
192  service mysql start
193  sudo service mysql start
194  service mysql status
195  sudo service mysql stop
196  sudo usermod -d /var/lib/mysql/ mysql
197  sudo service mysql start
198  service mysql status#
199  mysql -u mukul -p
200  show tables;
201  mysql -u mukul
202  mysql -u mysql
203  mysql -u mysql -p
204  sudo mysqladmin -p -u mukul version
205  mysql -u mysql -p
206  sudo mysqladmin -p -u mukul version
207  mysql
208  mysql -u mysql -p
209  mysql -u mukul -p
210  docker
211  docker -v
212  docker ps
213  docker build
214  docker build -t .
215  pwd
216  ls -ltr
217  docker build .
218  docker ps
219  systemctl
220  systemctl start docker
221  sudo service docker start
222  docker ps
223  sudo service --status-all
224  docker ps
225  history