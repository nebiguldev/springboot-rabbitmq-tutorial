# springboot-rabbitmq-tutorial
rabbitMQ tutorial 
RabbitMQ Mini Tutorial Projesi
Bu proje, RabbitMQ ile hem string hem de JSON veri gönderme ve alma işlevlerini nasıl gerçekleştireceğinizi gösterir. Proje, Docker üzerinde RabbitMQ ve Spring Boot kullanılarak oluşturuldu.


Docker ile RabbitMQ'nun Kurulumu:
docker pull rabbitmq
docker run -d --hostname my-rabbit --name some-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:management

Spring Boot Projesinin Oluşturulması:
start.spring.io adresine gidin.
Gerekli bağımlılıkları ekleyin (Örneğin: RabbitMQ, Web vb.).
Projenizi indirin ve zip dosyasını çıkarın.


RabbitMQ Konfigürasyonları:
application.properties veya application.yml dosyasına RabbitMQ ayarlarınızı ekleyin
spring.rabbitmq.host=localhost
spring.rabbitmq.port=5672
spring.rabbitmq.username=guest
spring.rabbitmq.password=guest

RabbitMQ ile iletişim kurmak için gerekli servis ve kontroller 
