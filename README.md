ProductAPI-WebService

📌 Proje Özeti
Bu proje, temel ürün yönetimi işlemlerini gerçekleştiren bir RESTful API’dir.
Kullanıcılar API üzerinden ürünleri listeleyebilir, belirli bir ürünü görüntüleyebilir ve iş kurallarına uygun şekilde ürün verilerini yönetebilir.

🎯 Amaç / Problem
Bir ürün servisinde aşağıdaki temel ihtiyaçlar bulunmaktadır:
Ürünlerin listelenebilmesi.
Ürün detaylarının görüntülenebilmesi.
İş kurallarına uygun veri yönetimi.
Bu ihtiyaçlara cevap verebilecek sade ve sürdürülebilir bir backend servisine ihtiyaç duyulmuştur.

💡 Çözüm Yaklaşımı
Bu ihtiyaçlar doğrultusunda ASP.NET Core Web API kullanılarak:
Controller, Service ve Model katmanları birbirinden ayrıştırıldı.
Bağımlılıklar interface’ler aracılığıyla soyutlandı.
Temiz, okunabilir ve sürdürülebilir bir mimari yapı kuruldu.

🛠️ Kullanılan Teknolojiler
C#
ASP.NET Core Web API
.NET(Core)10.0.101

📌 Nasıl Çalışır
1. Repo’yu klonla  
2. `dotnet restore`  
3. `dotnet run`  
4. REST endpoint’leri test et (ör. GET /api/products)

📌 Geliştirme Durumu
Proje aktif olarak geliştirilmektedir.  
İlerleyen aşamalarda veritabanı entegrasyonu, ek endpoint’ler ve iş kurallarının genişletilmesi hedeflenmektedir.
