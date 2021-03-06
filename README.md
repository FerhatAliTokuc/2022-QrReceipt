<h2 align="center"><span><strong>2022 İBB Sürdürülebilir Şehirler Hackathonu</strong></span></h2>

19 Mayıs Atatürk’ü Anma Gençlik ve Spor Bayramı kapsamında; İstanbul Büyükşehir Belediyesi ve Microsoft Türkiye iş birliği ile, Coderspace organizasyonu ile gerçekleşen ‘Sürdürülebilir Şehirler Hackathon’u projelerini içermektedir. Hackathon detayları için : https://surdurulebilirsehirler.ist/

![Project Summary - Template](https://user-images.githubusercontent.com/65132520/168225424-56e2eb45-a33c-4274-9dce-cf34655fd1eb.png)


### Proje Adı
- QR Receipt

### Takım Adı & Üyeleri
- Takım Üyesi 1 Ferhat Ali Tokuç ( Architecture , Designer , Developer)
- Takım Üyesi 2 Muzaffer Tolga Yakar (Front-end , Back-end)
- Takım Üyesi 3 Çetin Kaan Taşkıngenç (Front-end , Back-end)
- Takım Üyesi 4 Emre Özkal ( Tester - Developer )

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
- Ürünümüz erken geliştirme aşamasındadır. Yazılımın öncelikli olarak back-end kısmıyla ilgilendiğimiz için ilerleyen sürümlerde front-end tarafına öncelik verilerek çok ciddi görsel iyileştirmeler yapılacaktır.

![WhatsApp Image 2022-05-13 at 03 17 42](https://user-images.githubusercontent.com/65132520/168217047-196f7914-6d4d-4510-8060-0e18012168fd.jpeg) ![WhatsApp Image 2022-05-11 at 02 54 51](https://user-images.githubusercontent.com/65132520/168217089-40cdf403-015c-42ae-b012-4a4523718099.jpeg)


![WhatsApp Image 2022-05-13 at 05 25 55](https://user-images.githubusercontent.com/65132520/168217064-667bf3dd-06cc-4e06-b1ef-656e42f048d6.jpeg)


![WhatsApp Image 2022-05-13 at 00 10 38](https://user-images.githubusercontent.com/65132520/168217074-ecf02bdc-802f-40fc-b14e-51a4087ddf2e.jpeg)






![fiyat 2](https://user-images.githubusercontent.com/65132520/168217620-2abed08b-7dd4-4364-84b9-9b01c823ff6a.png)





### Teknoloji / Veri Kaynakları / Teknik Mimari

**Teknoloji**


1.Azure Cloud

2.Azure Machine Learning

3.Azure Key Vault

4.Power BI

5.Node.js 

6.React.js

7.TypeScript

8.React-Native

9.MongoDB

10.Docker

**Veri Kaynakları**

1.İBB Açık Veri Portalı
https://data.ibb.gov.tr/dataset/gorme-engelli-birey-bilgileri

2.Türkiye İstatisik Kurumu

Hanehalkı Tüketim Harcaması İstatistikleri
https://biruni.tuik.gov.tr/medas/?kn=84&locale=tr

3.Kaggle

https://www.kaggle.com/datasets/nickwong64/corn2015-2017

**Teknik Mimari**


![Ekran görüntüsü 2022-05-13 081606](https://user-images.githubusercontent.com/65132520/168215814-8d497e4f-c015-42e8-af47-fbeaebc88d4c.png)




### Prototip
 **Prototip Açıklamaları**

- Veri tabanı için MongoDB kullandık. MongoDB yi Docker ile çalıştırdık.

- Docker contaıner run -d -p 27017:27017 --name mongodb-server mongo.

- Container oluşturduktan sonra MongoDBCompass uygulamaı ile bir hackathon adında bir veri tabanı oluşturduk. (.env dosyasın da database ayarları mevcut).

- Programlama dili olarak TypeScript kullandık kütüphane olarak express, mongoose, qrcode, multer, body-parser, cors, http-status, nodemon, @types/node, dotenv, morgan, helmet

- Projenin frontend kısmını erken erişim olduğu için yüklemedik. Frontend framework olarak React kullandık, geliştirmeye devam etmektyiz.

### Detaylar (İsteğe Bağlı)
-Projenin uygulanabilirlik oranı bir hayli yüksektir.Kolay bir şekilde entegre edilebilir ve kullanılabilir. Şuan halihazırda qr pos ile ödeme alan sistemler gerekli yazılım güncellemeleri ile qr fiş basar haline gelebilir. Bunu yapacak teknolojik alt yapıya sahip olmayan pos cihazları yenileri ile değiştirebilir yada maliyeti düşük ucuz bir ekran temin edilebilir.




