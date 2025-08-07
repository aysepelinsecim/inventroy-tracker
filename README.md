# inventroy-tracker
Spring Boot tabanlı Mikroservis Projesi – Inventory ve Order işlemleri için RESTful servisler, kupon sistemi, Kafka entegrasyonu, test coverage optimizasyonu ve pagination özellikleri ile birlikte.


#  Inventory & Order Microservice - Spring Boot Application

Bu proje, Java 17 ve Spring Boot 3.5.3 ile geliştirilmiş, mikroservis mimarisine uygun bir envanter ve sipariş yönetim sistemidir.

##  Özellikler

- RESTful API ile ürün ekleme, silme, güncelleme ve listeleme
- Spring Data JPA ile H2 veritabanı bağlantısı
- Kupon kodu ile dinamik indirim hesaplama
- Kafka entegrasyonu ile servisler arası iletişim
- Pagination ile performanslı veri çekme
- Mockito + JUnit5 ile yüksek test coverage
- JaCoCo entegrasyonu (%90+ kapsama oranı)

##  Kullanılan Teknolojiler

- Java 17
- Spring Boot 3.5.3
- Spring Data JPA
- Spring Web
- Kafka
- Lombok
- H2 Database
- JUnit 5
- Mockito
- JaCoCo

## 📁 Modüller

- **InventoryService**: Ürün CRUD işlemleri + kuponla indirim hesaplama
- **OrderService**: Sipariş oluşturma ve durum güncelleme
- **Kafka Consumer/Producer**: Sipariş ve stok işlemleri arası mesajlaşma

## 🧪 Test ve Coverage

- Tüm controller ve service sınıfları unit test ile kapsanmıştır.
- `jacoco-maven-plugin` ile kapsam dışı bırakılan dosyalar filtrelenmiş ve %90+ test coverage sağlanmıştır.


