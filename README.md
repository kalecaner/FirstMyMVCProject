# 🏗 FirstMyMVCProject  
_First MVC Project Example for Learning and Practice_

Bu proje, **ASP.NET MVC** mimarisi ile geliştirilmiş bir örnek uygulamadır.  
Eğitim ve kişisel gelişim amacıyla hazırlanmıştır.  
This project is an example application built with **ASP.NET MVC** architecture.  
It is developed for educational and personal development purposes.

---

## 🎯 Projenin Amacı / Project Purpose

**TR**  
- MVC mimarisi ile uygulama geliştirme pratiği kazanmak  
- Controller, Model, View kavramlarını kavramak  
- Veri akışı, yönlendirme (routing), View bileşenleri ile çalışmak  
- Basit CRUD işlemlerini uygulamak  

**EN**  
- Gain hands-on experience building applications with MVC architecture  
- Understand Controller, Model, and View concepts  
- Work with data flow, routing, and view components  
- Implement simple CRUD operations  

---

## 🏛 Mimari / Architecture

**TR**  
- **Model**: Veri modelleri (entity sınıfları)  
- **View**: Razor ile HTML + veri gösterimi  
- **Controller**: İş mantığı, HTTP isteklerini karşılayan aksiyon metodları  
- **DAL / Repository (opsiyonel)**: Veri erişim (Entity Framework, Dapper vb.)  
- **ViewModel / DTO**: Görünüm için özel veri taşıyıcıları  

**EN**  
- **Model**: Data models (entity classes)  
- **View**: Razor views combining HTML + data  
- **Controller**: Business logic, action methods responding to HTTP requests  
- **DAL / Repository (optional)**: Data access (EF, Dapper etc.)  
- **ViewModel / DTO**: Data carriers for views  

> Bu yapı **eğitim amaçlıdır**; gerçek projelerde güvenlik, validasyon, hata yönetimi, logging gibi özellikler eklenmelidir.  
> This structure is for **educational purposes**; production projects should include security, validation, error-handling, logging, etc.

---

- `Controllers/` → Uygulama isteklerini karşılayan sınıflar  
- `Models/` → Uygulamadaki veri modelleri  
- `Views/` → Razor sayfaları  
- `Data/` → DB bağlantısı, repository’ler  
- `ViewModels/` → View’lar için özel modeller  
- `wwwroot/` → Stil dosyaları, scriptler, görseller  

---

## 🛠 Teknolojiler / Technologies

- ASP.NET Core MVC (veya klasik ASP.NET MVC, hangisi kullanıldıysa)  
- Entity Framework Core ya da başka ORM / veri erişim  
- Bootstrap / CSS / JavaScript  
- Razor View Engine  
- (İsteğe bağlı) Identity / Authentication  

---

## 🚀 Kurulum & Çalıştırma / Setup & Running

### 1. Depoyu Klonla / Clone the Repository  
```bash
git clone https://github.com/kalecaner/FirstMyMVCProject.git
cd FirstMyMVCProject


## 📂 Proje Yapısı / Project Structure

