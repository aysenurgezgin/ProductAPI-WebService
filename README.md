ProductApı-WebService

📌 Proje Özeti

Bu proje, basit bir ürün yönetimi API’si sağlar.  
Kullanıcılar ürünleri listeleyebilir, belirli ürünü görebilir ve iş kurallarına göre filtreleme yapabilirler.

🎯 Problem

Bir ürün servisinin temel REST API özellikleriyle sunulması ihtiyacı vardı:
- Ürünlerin listelenmesi
- Ürün detaylarının alınması
- Basit iş kurallarının uygulanması

 💡 Çözüm

ASP.NET Core Web API kullanılarak:
- Controller, Service ve Model yapısı ayrıştırıldı
- Bağımlılıklar interface kullanılarak soyutlandı
- Temiz ve sürdürülebilir mimari tasarlandı

🛠️ Kullanılan Teknolojiler

- C#  
- ASP.NET Core  
- .NET 10.0.101 

📌 Nasıl Çalışır

1. Repo’yu klonla  
2. `dotnet restore`  
3. `dotnet run`  
4. REST endpoint’leri test et (ör. GET /api/products)
