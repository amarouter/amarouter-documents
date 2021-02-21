## Overall Description (Section 2)

Bu bölümde ürünün teknik arayüzlerinden bahsedilir.
Ayrıca üründe gerçekleşebilecek operasyonlar da bu bölümde ele alınır.

### Product Perspective

#### System Interfaces
1. Frontend sistemi Rest API mimarisi üzerinden Backend ile haberleşir.
2. Backend sistemi gerekli veritabanları ile iletişim halindedir.

#### User Interfaces
1. Kullanıcı arayüzleri MVP(Minimum Viable Product) versiyonunda Frontend Web Application üzerinden sağlanır.
2. Kullanıcı arayüzleri tüm güncel tarayıcılarda aynı şekilde hizmet vermelidir.
3. MVP versiyonunda 5 arayüz ekranı olmalıdır:
    1. Landing Page
    2. Dashboard
    3. Rehberler
    4. Video Kurslar
    5. Blog

#### Hardware Interfaces
1. Frontend sistemi Firebase üzerinden sunulur.
2. Backend sistemi AWS üzerinden sunulur.
3. Veritabanı sistemi AWS üzerinden sunulur.

#### Software Interfaces
1. Frontend Web Application sistemi React ile yazılır.
2. Backend sistemi Django Rest Framework ile yazılır.
3. Veritabanı sistemi olarak PostgreSQL kullanılır.

#### Communication Interfaces
Haberleşme arayüzü olarak Rest API mimarisi kullanılır ve JSON tipinde veri iletimi tercih edilir.

#### Operations
Sistemde kullanılacak olan operasyonlar aşağıda sıralanmıştır.
- Giriş yapılabilmeli.
- Rehberler sayfasına gidilebilmeli.
- Video kurslar sayfasına gidilebilmeli.
- Blog sayfasına gidilebilmeli.

#### Apportioning of Requirements
- Kullanıcıların bir kısmı Amarouter olabilmeli.
- Amarouter'lar sistemi geliştirebilmeli.