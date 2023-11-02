<h2 align="center"><span><strong>The 2022 Istanbul Metropolitan Municipality Sustainable Cities Hackathon</strong></span></h2>

As part of the May 19th Commemoration of Atatürk, Youth and Sports Day, the 'Sustainable Cities Hackathon' organized in collaboration with Istanbul Metropolitan Municipality and Microsoft Turkey, in partnership with Coderspace, includes their projects. For more details about the hackathon: https://surdurulebilirsehirler.ist/

![Project Summary - Template](https://user-images.githubusercontent.com/65132520/168225424-56e2eb45-a33c-4274-9dce-cf34655fd1eb.png)


### Project Name
- QR Receipt

### Team Members
- Team Member 1: Ferhat Ali Tokuç (Architecture, Designer, Developer)
- Team Member 2: Muzaffer Tolga Yakar (Front-end, Back-end)
- Team Member 3: Çetin Kaan Taşkıngenç (Front-end, Back-end)
- Team Member 4: Emre Özkal (Tester - Developer)

### Problem
- The inability to recycle paper receipts (thermal paper).
-  Ineffectiveness of the designed OCR technology for visually impaired individuals to read receipts.
-  Rapid deformation of receipts and invoice papers (warranty/return issues).
-  Difficulty in archiving receipts and invoices (archiving or finding the required document).
-  Inefficiency of accountants in entering receipts or invoices into the system.
-  Security vulnerabilities resulting from the disposal of documents like credit card statements and invoices.
-  Stock problems arising from people buying more products than they need due to the uncertainty of future product prices.
-  Lack of automated systems for budget analysis by individuals.

### Solution and User Experience

-  Using QR codes instead of paper receipts solves all the mentioned problems.
-  The use of non-recyclable thermal paper will be eliminated thanks to QR codes.
-  Visually impaired individuals can access their expenses within seconds through the "text-to-voice" technology and verify the accuracy of the information.
-  Storing receipt/invoice information in an online data center will solve the issues of document deformation and archiving.
-  Since expense data can be exported in computer formats like Microsoft Excel, the unnecessary workload of departments like accounting will be eliminated.
-  Security issues arising from discarded receipts/invoices will disappear.
-  Since the system stores product price information, individuals can learn the estimated price of a product for the next day, week, or month and make more accurate shopping decisions accordingly.
-  With expenses being tracked by the system, individuals can see where they spend their daily, weekly, monthly, or yearly budgets and plan their budgets more effectively.


### Target Audience

General Audience:
- All individuals who use smartphones.
Specific Audience:
- Visually impaired individuals.

### Prototype
- Our product is in the early development stage. Since we are primarily focused on the back-end of the software, significant visual improvements will be prioritized in the upcoming versions, giving priority to the front-end.

![WhatsApp Image 2022-05-13 at 03 17 42](https://user-images.githubusercontent.com/65132520/168217047-196f7914-6d4d-4510-8060-0e18012168fd.jpeg) ![WhatsApp Image 2022-05-11 at 02 54 51](https://user-images.githubusercontent.com/65132520/168217089-40cdf403-015c-42ae-b012-4a4523718099.jpeg)


![WhatsApp Image 2022-05-13 at 05 25 55](https://user-images.githubusercontent.com/65132520/168217064-667bf3dd-06cc-4e06-b1ef-656e42f048d6.jpeg)


![WhatsApp Image 2022-05-13 at 00 10 38](https://user-images.githubusercontent.com/65132520/168217074-ecf02bdc-802f-40fc-b14e-51a4087ddf2e.jpeg)






![fiyat 2](https://user-images.githubusercontent.com/65132520/168217620-2abed08b-7dd4-4364-84b9-9b01c823ff6a.png)





### Technology / Data Sources / Technical Architecture

**Technology**


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

**Data Sources**

1.Istanbul Metropolitan Municipality Open Data Portal
https://data.ibb.gov.tr/dataset/gorme-engelli-birey-bilgileri

2.Turkish Statistical Institute

Household Consumption Expenditure Statistics
https://biruni.tuik.gov.tr/medas/?kn=84&locale=tr

3.Kaggle

https://www.kaggle.com/datasets/nickwong64/corn2015-2017

**Technical Architecture**
- Since it's a hackathon project, the architecture has been simplified for presentation purposes only

![Ekran görüntüsü 2022-05-13 081606](https://user-images.githubusercontent.com/65132520/168215814-8d497e4f-c015-42e8-af47-fbeaebc88d4c.png)




### Prototype
 **Prototype Descriptions**

- We used MongoDB for the database. We ran MongoDB with Docker.

-  After creating the container, we created a database named "hackathon" using the MongoDB Compass application (database settings are available in the .env file).

-  We used TypeScript as the programming language and libraries such as express, mongoose, qrcode, multer, body-parser, cors, http-status, nodemon, @types/node, dotenv, morgan, helmet.

-  We haven't uploaded the frontend part of the project as it's in early access. We used React as the frontend framework and will continue development.

- Projenin frontend kısmını erken erişim olduğu için yüklemedik. Frontend framework olarak React kullandık, geliştirmeye devam etmektyiz.






