# Yapay Zeka Destekli Java Backend Geliştirici Yol Haritası

Backend geliştirme öğreniminin geleceğine hoş geldin. Bu yol haritası, uygulamalı projeler, gerçek dünya mimarileri ve ChatGPT gibi yapay zekâ araçlarının gücünü bir araya getirerek sana özel rehberlik, örnekler ve geri bildirimler sunar.

### 🔍 Bu Yol Haritası Nasıl Kullanılır
- **Her bölüm**, öğrenilmesi gereken temel konuları, geliştirilecek küçük bir uygulamayı ve ChatGPT’ye yapıştırabileceğin hazır yapay zekâ komutlarını içerir.
- **Bu komutları kullanarak**, kavramları netleştirebilir, kod örnekleri alabilir ve en iyi uygulamaları etkileşimli şekilde keşfedebilirsin.
- **Kendi hızında ilerle** — bu yol haritası modüler ve esnektir.
- **Daha fazla rehberliğe mi ihtiyacın var?** ChatGPT’ye şunları sorabilirsin: *"[konu] sonrasında ne öğrenmeliyim?", "[konu] hakkında bana bir quiz hazırlar mısın?", "Kodumu gözden geçirebilir misin?"*

Haydi başlayalım!


## 1. Prompt Engineering'e İlk Adımlar

**Öğren:**
- Prompt Engineering nedir ve geliştiriciler için neden önemlidir?
- Prompt türleri: zero-shot, few-shot, rol tabanlı ve bağlamsal (contextual) promptlar
- Prompt Chaining ve yapay zekâyı adım adım yönlendirme
- Sonuçlar yeterli olmadığında AI promptlarını hata ayıklama (debugging)

**Mini Uygulama:**
> Kod Görevleri için Prompt Oluşturucu  
> - CLI aracı ya da web formu olarak, backend özelliklerine yönelik prompt şablonları oluşturan bir uygulama geliştir  
> - Kod üretimi, hata düzeltme, optimizasyon gibi varyasyonları dahil et

**Yapay Zeka Komutları (AI Prompts):**
```
Zero-shot ve few-shot promptlar nedir? Her birine örnek ver.
```
```
Bir yapay zekâyı (örneğin ChatGPT) Java'da CRUD API oluşturması için adım adım nasıl yönlendirebilirim?
```
```
JWT ve refresh token ile güvenli bir giriş (login) API'si oluşturan bir prompt yaz.
```
```
Kod üretimi için yazılan yapay zekâ promptlarını hata ayıklarken veya iyileştirirken dikkat edilmesi gereken en iyi uygulamalar nelerdir?
```

Bu yol haritası, projeler üzerinden öğrenmek isteyen modern backend geliştiriciler için tasarlanmıştır. Yapay zekâ desteğiyle gerçek zamanlı geri bildirim alabilir, uygulamalı beceriler geliştirebilirsin. Statik bir konu listesi takip etmek yerine, her adımda mini projeler ve ChatGPT komutlarıyla etkileşimli bir öğrenme deneyimi yaşayacaksın.

---

## 2. Web Nasıl Çalışır?

**Öğren:**
- DNS, IP ve Domain sistemleri
- HTTP, HTTPS protokolleri
- Tarayıcı - Sunucu iletişimi
- Request/Response döngüsü 
- Web sunucuları (Nginx, Apache)

**Mini Uygulama:**
> `curl` ve `Postman` kullanarak istekleri simüle et ve yanıtları incele

**Yapay Zeka Komutları (AI Prompts):**
```
Bir kullanıcı tarayıcıya bir URL yazdığında adım adım ne olur?  
HTTP, DNS, TCP/IP ve HTTPS süreçlerini dahil et.
```
```
HTTP durum kodları nelerdir?  
2xx, 3xx, 4xx, 5xx için örnekler ver.
```
```
CORS nedir?  
Frontend ve Backend iletişiminde neden CORS hataları alırız?
```
```
CDN nasıl çalışır?  
Ne zaman ve neden bir CDN kullanmalıyım?
```


---

## 3. Git ve Sürüm Kontrolü

**Öğren:**
- Git temelleri: `init`, `clone`, `add`, `commit`, `push`, `pull`, `merge`
- Branching stratejileri 
- `.gitignore`, rebase, stash kavramları

**Mini Uygulama:**
> Backend projen için bir Git deposu başlat, özellik geliştirmeleri için branch’ler kullan

**Yapay Zeka Komutları (AI Prompts):**
```
Git merge çatışması (conflict) nasıl çözülür?
```
```
Git rebase ile merge arasındaki farkı bir örnekle açıkla.
```


---

## 4. Java ve OOP Temelleri

**Öğren:**
- Java sözdizimi ve türler (primitives, wrappers)
- Sınıflar ve Nesneler (Classes and Objects)
- Kalıtım (inheritance), çok biçimlilik (polymorphism), kapsülleme (encapsulation), soyutlama (abstraction)
- İstisna yönetimi (Exception handling): try-catch-finally, özel istisnalar
- Java Koleksiyonları (List, Set, Map)
- Arayüzler (interfaces) vs soyut sınıflar (abstract classes)
- Java erişim denetleyicileri (public, private, protected)
- Yapıcılar (constructors), `this` ve `super` anahtar kelimeleri
- Overloading ve Overfitting kavramları
- Static ve instance üyeler
- Final anahtar kelimesinin kullanımı
- Java Bellek Modeli (stack ve heap temel farkları)

**Mini Uygulamalar:**
> 1. `Öğrenci Yönetim Konsol Uygulaması` — Koleksiyonları kullanarak öğrenci ekle, listele ve sil
> 2. `Basit Hesap Makinesi` — Farklı işlemler için yöntem aşırı yüklemesi (method overloading) kullan
> 3. `Banka Sistemi` — Hesap, TasarrufHesabı gibi sınıflarla kalıtımı (inheritance) göster
> 4. `Kütüphane Sistemi` — `Searchable`, `Borrowable` davranışları için arayüzler (interfaces) kullan

**Yapay Zeka Komutları (AI Prompts):**
```
Bu sınıf tasarımı SOLID prensiplerine uygun mu? İyileştirme önerileri sun.
```
```
Java'da istisnaları (exceptions) nasıl düzgün bir şekilde yönetmeliyim?
```
```
Java'da arayüzler (interfaces) ve soyut sınıflar (abstract classes) ne zaman kullanılmalı? Örnekler ver.
```
```
Overloading ve Overfitting nasıl çalışır? Örneklerle açıkla.
```
```
Java'nın bellek modeli nesne oluşturma ve çöp toplama (object creation and garbage collection) üzerinde nasıl bir etki yapar?
```
```
HashMap, LinkedHashMap ve TreeMap arasındaki farkları ve kullanım senaryolarını karşılaştır.
```
```
OOP prensiplerine göre küçük bir kütüphane sistemi için UML sınıf diyagramı oluşturabilir misin? İyileştirme önerileri sun.
```


---

## 5. Spring Boot ile REST API'leri Oluşturma

**Öğren:**
- Spring Boot temelleri (otomatik yapılandırma, açıklamalar/annotasyonlar)
- Controller-Service-Repository yapısı
- RESTful tasarım: HTTP fiilleri (verbs), durum kodları, URI isimlendirmesi
- `@RequestBody`, `@PathVariable`, `@RequestParam` ile veri bağlama
- ResponseEntity ve özel yanıtlar
- Spring Data ile sayfalama (pagination) ve sıralama (sorting)
- SpringDoc ile Swagger/OpenAPI belgeleri
- REST API'leri için exception yönetimi

**Mini Uygulamalar:**
> 1. `Kitapçı API` — Kitaplar için tam CRUD işlemleri
> 2. `Görev Takip API` — Sıralama, sayfalama ve filtreleme ekleyin
> 3. `İletişim Yönetim API` — İç içe kaynaklar, örneğin: /users/{id}/contacts

**Yapay Zeka Komutları (AI Prompts):**
```
Kitapları yönetmek için GET, POST, PUT, DELETE uç noktalarını (endpoints) içeren RESTful bir API tasarımı yap.
```
```
Spring Boot'ta ResponseEntity kullanarak özel durum kodu ve gövde (body) nasıl döndürebilirim?
```
```
Spring Boot API'si için Swagger belgelendirmesi oluştur.
```
```
Spring Boot'ta layered architecture yapılandırmak için en iyi uygulama nedir?
```
```
Spring Data ile bir REST endpoint'inde sayfalama ve sıralama nasıl uygulanır?
```
```
@ControllerAdvice kullanarak REST API'de hata yönetimini nasıl yapabilirim?
```

**Öğren:**
- Spring Boot temelleri
- MVC yapısı: controller, service, repository
- REST prensipleri

**Mini Uygulama:**
> `Kitapçı REST API` — CRUD işlemleri

**Yapay Zeka Komutları (AI Prompts):**
```
Spring Boot'ta temiz REST controller'ları nasıl tasarlarım?
```
```
Spring API'm için Swagger belgelendirmesi oluştur.
```


---

## 6. Veritabanları ve JPA

**Öğren:**
- SQL temelleri: SELECT, INSERT, UPDATE, DELETE
- İleri düzey sorgular: JOIN'ler, GROUP BY, subqueries, indexes
- PostgreSQL / MySQL kurulumu ve CLI araçları
- Veritabanı tasarımı: normalizasyon, ER diyagramları, ilişkiler
- Spring Data JPA entegrasyonu
- JPA entity ilişkileri: OneToMany, ManyToMany, OneToOne
- Lazy vs Eager loading
- İşlemler (transactions), izolasyon seviyeleri ve ACID prensipleri
- Sorgu optimizasyonu (Query optimization ) ve indeksleme stratejileri

**Mini Uygulama:**
> `Kütüphane Yönetim Sistemi`
> - Varlıklar: Kitap, Yazar, Ödünç Alan, Ödünç
> - Tabloları ve ilişkileri oluştur
> - Spring Data JPA ile özel sorgular kullan

**Yapay Zeka Komutları (AI Prompts):**
```
Kitaplar, yazarlar ve ödünç alanlar için bir Kütüphane Yönetim Sistemi için ER diyagramı tasarla.
```
```
SQL örnekleriyle inner join, left join ve full join arasındaki farkı açıkla.
```
```
JPA'da Lazy ve Eager fetching arasında nasıl seçim yaparım?
```
```
Spring Data JPA'da @Query kullanarak tüm gecikmiş ödünçleri getiren özel bir SQL sorgusu yaz.
```
```
İşlemler (transactions ilişkisel veritabanlarında) nasıl çalışır? İzolasyon seviyelerini gerçek dünya örnekleriyle açıkla.
```
```
PostgreSQL'de nasıl bir indeks oluştururum ve ne zaman kullanmalıyım?
```

**Öğren:**
- SQL sorguları: SELECT, JOIN, GROUP BY, vb.
- PostgreSQL / MySQL temelleri
- Spring Data JPA
- Entity ilişkileri: OneToMany, ManyToMany
- İşlemler ve entity yaşam döngüsü

**Mini Uygulama:**
> `İlişkisel yapıya sahip Kütüphane Yönetim Sistemi`

**Yapay Zeka Komutları (AI Prompts):**
```
JPA'da ilişkileri (OneToMany, ManyToMany) nasıl tanımlarım?
```
```
Hibernate'de N+1 sorununu nasıl çözerim?
```
```
Bu SQL sorgusunu performans için nasıl optimize edebilirim?
```


---

## 7. Kimlik Doğrulama ve Güvenlik

**Öğren:**
- Kimlik doğrulama (Authentication) ve yetkilendirme (Authorization) prensipleri
- Spring Security mimarisi
- FilterChain, SecurityContext, AuthenticationManager
- UserDetailsService ve PasswordEncoder
- Stateless kimlik doğrulama JWT (JSON Web Token) ile
- Refresh token stratejisi
- Rol tabanlı ve izin tabanlı erişim kontrolü
- Yöntemlere güvenlik eklemek için anotasyonlar (`@PreAuthorize`, `@Secured`)
- CSRF koruması, güvenli API'lerde CORS
- OAuth2 temelleri (isteğe bağlı ileri seviye)

**Mini Uygulama:**
> `Güvenli Kitap Mağazası API'si`
> - Kayıt/giriş uç noktaları ile BCrypt hashing
> - JWT token oluşturma + doğrulama
> - Sadece admin ve sadece kullanıcı rotaları
> - Refresh token implementasyonu (isteğe bağlı)

**Yapay Zeka Komutları (AI Prompts):**
```
Spring Security filter chain'i, gelen bir isteği nasıl işler?
```
```
JWT ve BCrypt kullanarak Spring Boot'ta bir giriş ve kayıt kontrolörü oluştur.
```
```
Belirli bir kontrolör metodunu sadece ADMIN kullanıcıları için nasıl güvence altına alırım?
```
```
Stateless ve stateful kimlik doğrulama arasındaki fark nedir?
```
```
Spring Boot JWT kimlik doğrulama sisteminde refresh token'ları nasıl implement edebilirim?
```
```
Güvenli bir Spring Boot backend'de CORS'u nasıl yapılandırır ve test ederim?
```

**Öğren:**
- Spring Security
- JWT tabanlı kimlik doğrulama
- BCrypt ile parola hashing

**Mini Uygulama:**
> `JWT Login/Kayıt API'si` rol tabanlı erişim ile

**Yapay Zeka Komutları (AI Prompts):**
```
Spring Security filter chain'i nasıl çalışır?
```
```
JWT kimlik doğrulama ve refresh token'ları nasıl implement ederim?
```


---

## 8. Docker ve CI/CD

**Öğren:**
- Java ve Spring Boot için Dockerfile yazma
- Yerel geliştirme için docker-compose kullanma
- Konteynerleri bağlama (Spring Boot + PostgreSQL)
- Çok aşamalı Docker build işlemleri
- Temel Docker ağ yapısı ve volümleri
- GitHub Actions iş akışları oluşturma
- CI/CD pipeline'larında testleri çalıştırma
- GitHub Actions ile Heroku, Render veya DigitalOcean'a dağıtım yapma

**Mini Uygulamalar:**
> 1. `Dockerized Book Store API`
> 2. `docker-compose stack` — uygulama + DB + pgAdmin
> 3. `CI Pipeline` — test et, build et, ve GitHub Actions kullanarak dağıtım yap

**Yapay Zeka Komutları (AI Prompts):**
```
OpenJDK 17'de çalışan bir Spring Boot uygulaması için bir Dockerfile yaz.
```
```
Spring Boot uygulamamı PostgreSQL ile docker-compose kullanarak nasıl bağlarım?
```
```
Testleri çalıştırmak ve prodüksiyona dağıtım yapmak için bir GitHub Actions iş akışı oluştur.
```
```
Docker'da çok aşamalı build işlemlerinin amacı nedir?
```
```
Konteynerlere ortam değişkenlerini güvenli bir şekilde nasıl geçiririm?
```

**Öğren:**
- Dockerfile ve docker-compose
- Spring Boot ve DB için Docker kullanma
- CI/CD için GitHub Actions

**Mini Uygulama:**
> API'nizi konteynerleştirip PostgreSQL konteyneriyle bağlayın

**Yapay Zeka Komutları (AI Prompts):**
```
Spring Boot uygulaması için optimize edilmiş bir Dockerfile oluştur.
```
```
Bir Java backend'i build edip dağıtmak için GitHub Actions iş akışını göster.
```


---

## 9. Loglama, Doğrulama ve Hata Yönetimi

**Öğren:**
- SLF4J & Logback ile yapılandırılmış loglama
- Log seviyeleri: INFO, WARN, ERROR, DEBUG, TRACE
- Spring Boot'ta istisna yönetimi desenleri
- `@ControllerAdvice` ile global hata yöneticisi
- Bean Validation ile giriş doğrulama (`@Valid`, `@NotNull`, `@Size` vb.)
- Özel doğrulayıcılar ve kısıtlama mesajları
- Hassas verileri güvenli bir şekilde loglama
- Doğrulama mesajları için uluslararasılaştırma (i18n) (isteğe bağlı)

**Mini Uygulamalar:**
> 1. `Doğrulama ile Login API` — giriş hatasında doğru mesajlar döndür
> 2. `Hata Loglama Demo` — kullanıcı davranışlarını ve başarısız işlemleri logla
> 3. `Özel Doğrulayıcı Örneği` — e-posta domainleri veya şifreler için doğrulayıcı yaz

**Yapay Zeka Komutları (AI Prompts):**
```
Spring Boot'ta bir request DTO'sunda @Valid ve Bean Validation anotasyonlarını nasıl kullanırım?
```
```
@ControllerAdvice kullanarak global bir hata yöneticisi nasıl oluştururum?
```
```
Bir backend uygulamasında loglama için en iyi uygulamalar nelerdir?
```
```
Şifreler gibi hassas bilgilerin loglanmasını nasıl engellerim?
```
```
Kullanıcı adının sadece küçük harfler içerip içermediğini kontrol etmek için bir özel doğrulayıcı yaz.
```
```
Spring Boot'ta doğrulama hata mesajlarını nasıl uluslararasılaştırırım?
```

**Öğren:**
- SLF4J & Logback ile loglama
- `@ControllerAdvice` ile global hata yönetimi
- Hibernate Validator ile giriş doğrulama

**Mini Uygulama:**
> `Login API` — özel hata yanıtları ve doğrulama ile

**Yapay Zeka Komutları (AI Prompts):**
```
Spring Boot'ta hataları ve kullanıcı işlemlerini nasıl loglarım?
```
```
Gelen request body'lerini doğrulamanın en iyi yolu nedir?
```


---

## 10. Test Etme ve Mocking

**Öğren:**
- Birim testi prensipleri: arrange-act-assert
- Entegrasyon testi vs birim testi (Integration vs unit testing)
- JUnit 5 ile test yazma
- Bağımlılıkları mock'lamak için Mockito kullanımı
- Spring bileşenlerini test etme: controller'lar, servisler, repository'ler
- Spring Boot test anotasyonları: `@WebMvcTest`, `@DataJpaTest`, `@SpringBootTest`
- Test kapsamı stratejileri ve araçları (örneğin, JaCoCo)
- Test-Driven Development (TDD)
- Parametreli ve uç durum testleri yazma

**Mini Uygulama:**
> `Book Store Test Suite`
> - Servis metotları için birim testleri yaz, mock'ları kullan
> - API endpoint'leri için entegrasyon testleri yaz
> - Veritabanı davranışlarını `@DataJpaTest` ile doğrula
> - `TestRestTemplate` veya `MockMvc` kullanarak API çağrılarını simüle et

**Yapay Zeka Komutları (AI Prompts):**
```
JUnit 5'te bir toplam sipariş fiyatı hesaplayan metot için birim testi nasıl yazılır?
```
```
Spring servisi testinde Mockito kullanarak bir repository nasıl mock'lanır? Örnek ver.
```
```
Spring Boot'ta `@SpringBootTest` ve `@WebMvcTest` ne zaman kullanılmalı?
```
```
Spring Boot REST controller'ında hata senaryolarını (örneğin, 404, 500) nasıl test ederim?
```
```
Kullanıcı kayıt girişini doğrulayan bir metot için test edilmesi gereken uç durumlar (edge case'ler) öner.
```
```
Test kapsamını nasıl ölçerim ve backend uygulamaları için iyi bir hedef nedir?
```

**Öğren:**
- JUnit 5 temelleri
- Birim testi vs entegrasyon testi
- Mockito ile mocking

**Mini Uygulama:**
> `BookService` sınıfı için birim testleri yaz

**Yapay Zeka Komutları (AI Prompts):**
```
Bu Spring Boot servisi için Mockito kullanarak birim testleri yaz.
```
```
Controller endpoint'lerini nasıl test ederim?
```

---

## 11. Observability & Monitoring

**Öğren:**
- Spring Boot Actuator: yerleşik endpoint'ler ve sağlık kontrolleri
- Micrometer metrikleri: sayıcılar, zamanlayıcılar, göstergeler
- Prometheus entegrasyonu ile Spring Boot
- Prometheus & Grafana stack kurma
- İş mantığı için özel metrikler oluşturma
- Performans görselleştirme: yanıt süresi, istek oranı, hata oranı
- Prometheus ve Grafana'da uyarılar (örneğin, yüksek 500 hataları)
- Yapısal logging ve korelasyon ID'leri
- Zipkin ile dağıtık izleme temelleri (isteğe bağlı)

**Mini Uygulama:**
> `Monitoring-Enabled Book API`
> - Spring Boot Actuator endpoint'lerini ekle
> - Micrometer kullanarak Prometheus'a metrikler aç
> - Kullanıcı kayıtlarının sayısı için özel bir sayaç ekle
> - API metriklerini görselleştirmek için Grafana paneli oluştur
> - Hata oranı 1 dakikalık aralıkta %5'i aşarsa uyarı oluştur

**Yapay Zeka Komutları (AI Prompts):**
```
Spring Boot Actuator endpoint'lerini güvenli bir şekilde nasıl etkinleştirir ve açığa çıkarırım?
```
```
API sağlığını izlemek için en faydalı Micrometer metrikleri nelerdir?
```
```
Micrometer kullanarak kullanıcı kayıtları sayısı gibi özel bir metrik örneği ver.
```
```
Prometheus'u Spring Boot uygulamasından metrikleri alacak şekilde nasıl yapılandırırım?
```
```
Her endpoint için istek gecikmesini görselleştirmek için Grafana panosu oluştur.
```
```
Prometheus'ta HTTP 500 hata artışları için nasıl uyarı oluştururum?
```
```
Metrikler ile izleme arasındaki fark nedir? Dağıtık izlemeyi ne zaman kullanmalıyım?
```
```
Hizmetler arası istek izleme için loglara trace ID ve span ID'yi nasıl dahil ederim?
```

**Öğren:**
- Spring Boot Actuator endpoint'leri
- Prometheus & Grafana kurulumu
- Özel uygulama metrikleri

**Mini Uygulama:**
> API metriklerini Grafana panosunda açığa çıkar ve görselleştir

**Yapay Zeka Komutları (AI Prompts):**
```
Spring Boot uygulamamda Prometheus metriklerini nasıl eklerim?
```
```
Hata oranları ve yanıt sürelerini izlemek için Grafana'da bir pano oluştur.
```

---

## 12. Performans Optimizasyonu & Önbellekleme

**Öğren:**
- JVM performans ayarları (heap boyutu, GC ayarları)
- Garbage Collection türlerini anlama (Serial, G1, ZGC)
- JVM profil oluşturma (VisualVM, JFR, YourKit)
- Uygulama başlatma süresi ve bellek kullanımı ölçümü
- API yanıt süresi optimizasyon stratejileri
- Performans izleme için Spring Boot actuator metrikleri
- Önbellekleme (caching) kavramlarına giriş: bellek içi (in-memory) ve dağıtık (distributed)
- Caffeine ile önbellekleme (yerel, near-cache)
- Redis ile Spring Cache soyutlaması kullanarak önbellekleme
- Önbellek temizleme politikaları ve TTL ayarları

**Mini Uygulamalar:**
> 1. `Performans Ayarları Yapılmış Book API` — Yanıt süresi günlükleri, bellek kullanımı istatistikleri ekle
> 2. `Caffeine ile Önbelleğe Alınmış Ürün Servisi` — Fiyat aramaları için yerel önbellekleme
> 3. `Redis ile Önbelleğe Alınmış Kimlik Doğrulama` — Token doğrulama veya kullanıcı rollerini önbellek katmanı aracılığıyla yap

**Yapay Zeka Komutları (AI Prompts):**
```
Spring Boot performansı için JVM heap ve GC ayarlarını nasıl yapabilirim?
```
```
G1GC ile ZGC arasındaki farkları açıklayın. Her birini ne zaman kullanmalıyım?
```
```
VisualVM veya Java Flight Recorder kullanarak bir Java uygulamasını nasıl profil oluştururum?
```
```
Kullanıcı oturumları veya JWT verileri için en iyi önbellekleme uygulamaları nelerdir?
```
```
Spring Boot'ta Caffeine kullanarak metod düzeyinde önbellekleme nasıl uygulayabilirim?
```
```
Spring Boot uygulamasında @Cacheable ve TTL yapılandırmaları kullanarak Redis önbellekleme örneği ver.
```
```
Bellek içi (in-memory) ve dağıtık (distributed) önbellek arasındaki fark nedir? Artıları ve eksileri nelerdir?
```


## Öğrenmeye Devam Et

**Öğren:**
- Clean Architecture prensipleri: sorumlulukların ayrılması, katmanlar, kullanım senaryoları
- Domain-Driven Design (DDD) temelleri
- Event-driven architecture: asenkron mesajlaşma, event sourcing
- Apache Kafka veya RabbitMQ ile pub/sub sistemleri
- Mikroservisler: sınırlar, iletişim, servis keşfi
- API Gateway deseni ve araçları (ör. Spring Cloud Gateway)
- Circuit Breaker deseni ve Resilience4j veya Hystrix kullanımı
- Servis Kaydı (ör. Eureka), Yük Dengeleme ve Hata Toleransı
- Advanced deployment: Blue/Green, Canary sürümleri, Özellik bayrakları (Feature flags)
- Kubernetes (isteğe bağlı ileri seviye)
- **Prompt Engineering**: Yapay zeka destekli yazılım geliştirme için prompt oluşturmayı öğrenmek
  - Bağlamsal prompt tasarımı
  - Zero-shot vs few-shot prompting
  - Prompt zincirleme ve şablonlama
  - Rol promptları ve sistem talimatlarının kullanımı
  - Kod üretimi ve dokümantasyon için prompt hata ayıklama

**Mini Uygulama:**
> `Event-Driven Sipariş Yönetim Sistemi`
> - Sipariş servisi Kafka'ya yayın yapar
> - Stok servisi dinler ve stok günceller
> - API Gateway kullanarak kamuya açık uç noktalar sağlanır
> - Stok kontrol uç noktası için Circuit Breaker ekle
> - ChatGPT kullanarak tam özellikleri oluşturmak için prompt'ları yaz ve geliştir (ör. giriş akışı, Swagger belgeleri, Dockerfile)

**Yapay Zeka Komutları (AI Prompts):**
```
Clean Architecture yapısını pratik bir Java + Spring Boot örneği ile açıkla.
```
```
Mikroservis tabanlı bir e-ticaret sistemi tasarla, 3 ana servisi ve sorumluluklarını belirle.
```
```
Kafka nasıl çalışır? Ne zaman REST API'leri yerine Kafka kullanmalıyım?
```
```
API Gateway ile Service Registry arasındaki fark nedir?
```
```
Spring Boot'ta Resilience4j kullanarak Circuit Breaker nasıl implement edilir?
```
```
Etkinlik odaklı sistemlerin mikroservislerde nasıl decoupling sağladığını açıkla.
```
```
Üretime güncellemeleri güvenli bir şekilde dağıtmak için bazı stratejiler nelerdir?
```
```
Dağıtık bir sistemde mikroservisleri nasıl izlerim?
```
```
ChatGPT'ye güvenli bir giriş uç noktası oluşturması için kullanabileceğim bir prompt oluştur.
```
```
Spring Boot uygulaması için üretime uygun bir Dockerfile almak için nasıl etkili bir prompt yazabilirim?
```
```
Few-shot prompting nedir ve ne zaman kullanmalıyım?
```
```
Bir OpenAPI spesifikasyonu + controller + servis oluşturmak için çok adımlı bir prompt örneği ver.
```

## Öğren:

- Clean Architecture prensipleri: sorumlulukların ayrılması, katmanlar, kullanım senaryoları
- Domain-Driven Design (DDD) temelleri
- Event-driven mimari: asenkron mesajlaşma, event sourcing
- Apache Kafka veya RabbitMQ ile pub/sub sistemleri
- Mikroservisler: sınırlar, iletişim, servis keşfi
- API Gateway deseni ve araçları (ör. Spring Cloud Gateway)
- Circuit Breaker deseni ve Resilience4j veya Hystrix kullanımı
- Servis Kaydı (ör. Eureka), Yük Dengeleme ve Hata Toleransı
- İleri seviye dağıtım: Blue/Green, Canary sürümleri, Özellik bayrakları (Feature flags)
- Kubernetes (isteğe bağlı ileri seviye)


## Mini Uygulama:
> `Event-Driven Order Management System`
> - Sipariş verme servisi Kafka'ya yayın yapar
> - Envanter servisi dinler ve stoğu günceller
> - API Gateway kullanarak halka açık uç noktalar oluşturulur
> - Envanter kontrolü uç noktasına Circuit Breaker eklenir


**Yapay Zeka Komutları (AI Prompts):**
```
Clean Architecture yapısını pratik bir Java + Spring Boot örneğiyle açıklayın.
```
```
3 ana servisi ve bunların sorumluluklarını içeren mikro hizmet tabanlı bir e-ticaret sistemi tasarlayın.
```
```
Kafka nasıl çalışır? Ne zaman REST API'leri yerine kullanmalıyım?
```
```
API Gateway ile Service Registry arasındaki fark nedir?
```
```
Spring Boot'ta Resilience4j kullanarak bir Circuit Breaker nasıl implement edilir?
```
```
Olay odaklı sistemler, mikro hizmetlerde nasıl ayrıştırmaya yardımcı olur?
```
```
Üretim ortamına güncellemeleri güvenli bir şekilde dağıtmak için hangi stratejiler kullanılır?
```
```
Dağıtık bir sistemde mikro hizmetleri nasıl izlerim?
```

- Clean Architecture
- Olay Odaklı Sistemler (Kafka, RabbitMQ)
- Mikro Hizmetler (Microservices)
- API Gateway & Circuit Breakers

**AI Prompts:**
```
Clean Architecture yapısını bir Java örneğiyle açıklayın.
```
```
Mikroservisler ile monolitlerin avantajları ve dezavantajları nelerdir?
```

---

> Bu yol haritası statik değildir. İhtiyacınız olduğunda, ihtiyacınız olanı öğrenin. İnşa edin, sorun, yineleyin. Her adımda AI'nin rehberlik etmesine ve çalışmanızı gözden geçirmesine izin verin.

---

## Katkıda Bulun
Bu yol haritasını forklamaktan ve geliştirmekten çekinmeyin. Proje fikirlerinizi paylaşın, eksik içerikleri düzeltin ve sizin için iyi çalışan AI komutlarını önerin!
