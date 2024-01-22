# docker-compose-using-env-file

Docker compose kullanarak Drupal yazılımı çalıştırmak için aşağıdaki servisleri kuracak bir yml dosyası yazınız.

1 - Drupal image name: bitnami/drupal:latest
2 - DB image name: bitnami/mariadb:latest
3 - Webserver image name: nginx


Mariadb nin parametre değerini aşağıdaki şekilde yapınız ve bir ENV dosyasına yazınız.

USER = LinuxSistem
PASSWORD = <Sizin Öğrenci Numaranız>       Not : Eğer yandaki anlatımı HALA kavrayamayıp "Sizin Öğrenci Numaranız" yazan olursa 😡 
DATABASE = <DoğduğunuzAy(Yazı ile)>
Kurulumları sunucunuzda  docker compose ile yapıp aşağıdaki aşamaları gerçekleştiriniz
