# Stok ve Satış Takip Sistemi

Bu proje, küçük ve orta ölçekli işletmelerde ürün, müşteri ve satış süreçlerinin yönetilmesi amacıyla geliştirilmiş bir **masaüstü uygulamasıdır**.  
Bu uygulama kurum içi kullanım amacıyla geliştirilmiş olup stok takibini düzenli hale getirmek, satış işlemlerini kayıt altına almak ve detaylı raporlar oluşturmak için tasarlanmıştır.

Proje, **C# WinForms**, **MySQL** ve **N Katmanlı Mimari** kullanılarak geliştirilmiş olup, aynı zamanda **OOP prensiplerini** uygulamalı olarak göstermektedir.

---

## 🎯 Projenin Amacı

- Stokların düzenli ve kontrollü şekilde yönetilmesi  
- Satış işlemlerinin düzenli biçimde kaydedilmesi  
- Kullanıcı rollerine göre yetkilendirme sağlanması  
- Detaylı raporlama ekranları ile işletme kararlarını desteklemek  

---

## 👥 Kullanıcı Rolleri

- **Yönetici**
  - Tüm işlemleri yapabilir
  - Raporlama ekranlarına erişebilir

- **Satış Personeli**
  - Satış işlemlerini gerçekleştirir
  - Ürünleri ve Müşterileri görüntüler

- **Depo Görevlisi**
  - Yeni ürün ekler
  - Stok giriş ve çıkış işlemlerini yapar

---

## 🛠️ Kullanılan Teknolojiler

- Programlama Dili: **C#**
- Arayüz: **Windows Forms**
- Veritabanı: **MySQL**
- Mimari: **N Katmanlı Mimari**
- IDE ve Araçlar:
  - Visual Studio

---

## 🧱 Katmanlı Mimari Yapısı

Proje, aşağıdaki katmanlardan oluşmaktadır:

### DAL (Data Access Layer)
- MySQL veritabanı bağlantıları
- SQL sorguları
- CRUD işlemleri

### BLL (Business Logic Layer)
- İş kuralları
- Veri doğrulama
- Stok kontrolü (örneğin stok miktarının 0’ın altına düşmemesi)

### UI (User Interface Layer)
- WinForms ekranları
- Kullanıcı etkileşimleri
- Veri giriş ve görüntüleme işlemleri

---

## 🖥️ Uygulamada Bulunan Temel Ekranlar

### Giriş Ekranı (LoginForm)
- Kullanıcı adı ve şifre ile giriş
- Kullanıcı rolüne göre menü yetkilendirmesi

### Ürün Yönetimi (ProductForm)
- Ürün ekleme, güncelleme ve silme
- Minimum stok uyarı sistemi

### Müşteri Yönetimi (CustomerForm)
- Müşteri ekleme ve listeleme
- Müşteri türü seçimi (Perakende / Toptan)

### Satış Ekranı (SalesForm)
- Tarih seçimi
- Müşteri seçimi
- Ürün ekleme ve miktar belirleme
- Veritabanına kaydetme ve satış sonrası stok güncelleme

### Raporlama Ekranı (ReportForm)
- Aylık satış raporları
- En çok satılan ürünler
- Müşteri bazlı satış raporları
- Kâr ve zarar analizi
- Minimum stok raporları

---

## 📊 Raporlama Özellikleri

- **Aylık Satış Raporu**  
  Toplam satış sayısı, ciro ve indirim tutarları

- **En Çok Satılan Ürünler**  
  Satış miktarına göre ürün sıralaması

- **Müşteri Bazlı Satış Raporu**  
  Müşterilerin toplam alışveriş tutarları

- **Kâr / Zarar Raporu**  
  Satış fiyatı ve maliyet farkına göre analiz

- **Minimum Stok Raporu**  
  Stok eşiğinin altına düşen ürünlerin listesi

---

## 🔄 Uygulama Akışı

1. Kullanıcı sisteme giriş yapar  
2. Giriş bilgileri BLL üzerinden doğrulanır  
3. Kullanıcı rolüne göre ana menü açılır  
4. Ürün, müşteri veya satış işlemleri gerçekleştirilir  
5. Satış işlemi onaylanır  
6. İşlem sonucu kullanıcıya bildirilir  
7. Raporlama ekranları üzerinden analiz yapılır  

---

## 📸 Ekran Görüntüleri

(Ekran görüntülerini buraya ekleyiniz)
![alt text](?raw=true)

---

## ▶ YouTube Proje Tanıtım Videosu

Proje tanıtım videosu için:  
[Tiklayin]()

---

## 🚀 Kurulum ve Çalıştırma

1. Repository klonlanır  
2. Proje Visual Studio üzerinden açılır  
3. MySQL bağlantı ayarları yapılandırılır  
4. Uygulama çalıştırılır  

---

## ✨ Proje Hedefi

- Katmanlı mimariyi gerçek bir senaryo üzerinden uygulamak  
- Temiz, sürdürülebilir ve okunabilir kod yazmak  
- Gerçek hayatta kullanılabilecek bir stok ve satış sistemi geliştirmek  
---

## 📞 İletişim

- **Ad**: Muhammad Gavin
- **soyad**: Ragazzo
- **Tel No**:+90 506 581 49 15
- **E-posta**: gavin.ragazzo@gmail.com
