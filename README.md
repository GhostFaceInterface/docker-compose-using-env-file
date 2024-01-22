# Docker Compose using Env File for Drupal

Bu depo, Docker Compose kullanarak Drupal yazılımını çalıştırmak için gerekli olan servisleri kuracak bir YAML dosyasını içerir.

## Servisler

1. **Drupal Image Adı:** `bitnami/drupal:latest`
2. **DB Image Adı:** `bitnami/mariadb:latest`
3. **Web Sunucusu Image Adı:** `nginx`

## Mariadb Parametreleri

Mariadb'nin parametre değerlerini aşağıdaki gibi yapınız ve bir ENV dosyasına yazınız.

```env
USER=LinuxSistem
PASSWORD=<Sizin Öğrenci Numaranız>       Not: Eğer hala kavrayamayıp "Sizin Öğrenci Numaranız" yazan olursa 😡 
DATABASE=<DoğduğunuzAy(Yazı ile)>
```

## Kurulum Adımları

1. Bu repo'yu klonlayın:

   ```bash
   git clone https://github.com/kullanici_adi/repo_adi.git
   docker-compose up -d
