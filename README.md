This repo is used for devops training by Dirane TAFEN (diranetafen@yahoo.com)
# déploiement monolithique
cd docker \
vagrant up \
ssh vagrant@ip \

1- installation maven :
sudo yum install -y maven
2- contruction d'un livrable applicatif :
mvn clean install
3- déployer le livrable 
java --jar target/monolitic-1.4*.jar
4- test dans le navigateur: 
http://<ip_enp0s8>

# installation du fontend pour consommer le back-end
5-  sudo yum install -y httpd
6-  sudo copy  test.php /var/www/html/index.html

