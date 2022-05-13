<h2 align="center"><span><strong>2022 İBB Sürdürülebilir Şehirler Hackathonu</strong></span></h2>

19 Mayıs Atatürk’ü Anma Gençlik ve Spor Bayramı kapsamında; İstanbul Büyükşehir Belediyesi ve Microsoft Türkiye iş birliği ile, Coderspace organizasyonu ile gerçekleşen ‘Sürdürülebilir Şehirler Hackathon’u projelerini içermektedir. Hackathon detayları için : https://surdurulebilirsehirler.ist/

### Proje Adı
- QR Receipt

### Takım Adı & Üyeleri
- Takım Üyesi 1 Ferhat Ali Tokuç
- Takım Üyesi 2 Muzaffer Tolga Yakar
- Takım Üyesi 3 Çetin Kaan Taşkıngenç
- Takım Üyesi 4 Emre Özkal

### Problem
- Fişlerin geri dönüştürülememesi (Termal kağıt)

- Görme engelli bireylerin fişleri okuyamaması / okuyabilmesi için tasarlanan OCR teknolojisinin efektif olmaması

- Fiş/Fatura kağıtlarının  çok çabuk deforme olabilmesi ( Garanti / iade sorunları)

- Fiş/fatura arşivi yapmanın çok zor olması (Arşivleme veya aradığınız belgeyi bulabilme)

- Muhasebecilerin fiş veya faturaları sisteme geçmesinin çok zor ve efektif olmaması

- Kredi kartı / fatura gibi belgelerin atılması sonucu oluşan güvenlik açıkları 

- Ürünlerin gelecekteki fiyatlarının belirsizliği yüzünden insanların ihtiyaçlarından daha fazla ürün alarak stok sorunları ortaya çıkarması

- Kişilerin bütçe analizini otomatik yapan sistemlerin bulunmaması

### Çözüm ve Son Kullanıcı Deneyimi
- Fişlerin yerine qr kod kullanımı saymış olduğumuz tüm sorunları çözmektedir.

- Qr kod sayesinde geri dönüşümü olmayan termal kağıt kullanımı son bulacaktır.

- Görme engelli bireyler  "text to voice " teknolojisi sayesinde harcamalarına kısa saniye içinde erişebilir, bilgilerin doğrulunu teyit edebilirler.

- Kişilerin fiş/fatura bilgileri online bir veri merkezinde tutulduğu için fiş/faturaların deforme olması ve arşivlenmesi sorunları çözülecektir.

- Harcamalar Microsoft Excel gibi bilgisayar formatlarında dışarı aktarılabileceği için muhasebe gibi bölümlerin gereksiz iş yükleri ortadan kalkacaktır.

- Atık fişlerden/ faturalardan dolayı ortaya çıkan güvenlik sorunları yok olacaktır.

- Ürünlerin fiyat bilgisi sistem tarafından tutulduğu için kişiler o ürünün gelecek gün, hafta veya ayda tahmini fiyatını öğrenebilecek ve ona göre alışverişini daha  doğru bir şekilde yapabilecektir.

- Kişilerin harcamaları sistem tarafından tutulduğu için kişilerin günlük , haftalık ,aylık veya yıllık bütçelerini hangi kategorilerde harcadıklarını görüp bütçe planmasını daha efektif bir şekilde yapabileceklerdir.


### Hedef Kitle
Genel Kitle:
- Akıllı telefon kullanan tüm bireyler
Spesifik Kitle:
- Görme engelli bireyler

### Prototip
- Prototip Açıklaması 1

### Teknoloji / Veri Kaynakları / Teknik Mimari

**Teknoloji**


1.Azure Cloud

2.Azure Machine Learning

3.Azure Key Vault

4.Power Bi

5.Node.js 

6.React.js

7.TypeScript

8.React-Native

9.MongoDB

10.Docker

**Veri Kaynakları**

1.İBB Açık Veri Portalı

2.Türkiye İstatisik Kurumu

**Teknik Mimari**


![Ekran görüntüsü 2022-05-13 081606](https://user-images.githubusercontent.com/65132520/168215814-8d497e4f-c015-42e8-af47-fbeaebc88d4c.png)




### Prototip
- Prototip Açıklamaları

### Detaylar (İsteğe Bağlı)
- Veri tabanı için MongoDB kullandık. MongoDB yi Docker ile çalıştırdık.

- Docker contaıner run -d -p 27017:27017 --name mongodb-server mongo.

- Container oluşturduktan sonra MongoDBCompass uygulamaı ile bir hackathon adında bir veri tabanı oluşturduk. (.env dosyasın da database ayarları mevcut).

- Programlama dili olarak TypeScript kullandık kütüphane olarak express, mongoose, qrcode, multer, body-parser, cors, http-status, nodemon, @types/node, dotenv, morgan, helmet

- Projenin frontend kısmını erken erişim olduğu için yüklemedik. Frontend framework olarak React kullandık, geliştirmeye devam etmektyiz.

![Project Summary - Template](https://user-images.githubusercontent.com/65132520/168214921-f354f742-c38b-4c4a-bd1e-104e34d7d787.jpg)


