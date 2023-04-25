# Database-demo
I. Topic and Introduction
Topic: Fresh fruit juice store
Introduction: Modern people live in a busy life and often have no time to supplement vitamins. For the purpose of helping people quickly obtain vitamins, the fresh fruit juice store makes a variety of fruits into juices, bringing people organic products, so that people have sufficient nutrition.

II. System function description
1. Order online
+ Present nutritional information
+ Recommend juices with the proper nutritional content for the parts of your body that need nutritional supplements
+ Show fruit source and shelf life
2. Choose a shipping method: Daily delivery
3. Choose payment method: cash on delivery, credit card, bank transfer
4. Comments

III. Data Requirements
1. Juice (Product)
2. Customer
3. Transaction record (Transaction)
4. Feedback

These four entity types have the following properties:
• Juice information (Product): record the product number (pNo), product name (pName), category (catalog), production date (productionDate), expiration date (expirationDate), production place (productionPlace), selling price ( unitPrice). The product number and product name are unique.
• Customer information (Customer): Contains the customer's name (name), customer number (cId), telephone number (phone), address (address), and birthday (birthday) of the purchased juice. Where the customer number is unique.
• Transaction records (Transaction): including invoice number (tNo), transaction date (transTime), transaction payment (payment), payment method (method), delivery number (dNo), delivery time (deliveryTime). The invoice number and shipping number are unique.
• Transaction payment includes: bank name (bankName), bank number (bankId), card type (cardType), card number (cardId), and date (dueDate).
• Delivery time includes: morning (morning) and afternoon (afternoon).
• Product quantity (amount) and unit price (unitPrice) of a transaction record product
• Increase the function of customer evaluation (Feedback), so that customers can write (Writes) suggestions to leave comments (Comments) on completed transactions. A proposal is written by a client, and a client can write the proposal multiple times. Evaluation functions include suggestions （suggestion）.

#中文版

I.	專題題目與簡介

題目：鮮果果汁專賣店
介紹：現代人生活在忙碌的生活中，常常沒有時間補充維生素。鮮果果汁專賣店出於幫助人們快速獲得維生素的目的，將多種水果制作成果汁，給予人們帶來有機（Organic）的產品，讓人們擁有充足的營養。

II.	系統功能說明

1. 線上訂購：
+ 提出營養訊息
+ 針對需要營養補充劑的身體部位，推薦具有適當營養成分的果汁
+ 顯示水果來源跟保存期限
2. 選擇運送方式：按日交貨
3. 選擇支付方式：貨到付款、信用卡、銀行轉賬
4. 評價與提出意見

III.	資料需求說明

1.	果汁(Product)
2.	客戶(Customer)
3.	交易紀錄(Transaction)
4.	評價反饋(Feedback)

這四個實體型態有以下的性質：
•	果汁資料(Product)：紀錄果汁店提供的產品編號（pNo）、產品名稱(pName)、種類(catalog)、生產日期(productionDate)、有效日期(expirationDate)、生產地(productionPlace)、售價(unitPrice)。其中產品編號與產品名稱是唯一的。
•	客戶資料(Customer)：包含購買的果汁的客戶名字（name）、客戶編號(cId)、電話號碼(phone)、 住址(address)、 生日(birthday)。其中客戶編號是唯一的。
•	交易紀錄(Transaction)：包含發票編號（tNo）、交易日期(transTime)、交易付款（payment）、付款方式（method）、運送編號（dNo）、運送時間（deliveryTime）。其中發票編號及運送編號是唯一的。
•	交易付款包含：銀行名稱（bankName）、銀行編號（bankId）、卡的種類（cardType）、卡的編號（cardId）、日期（dueDate）。
•	運送時間包含：早上（morning）及下午（afternoon）。
•	一個交易記載產品的產品數量（amount）及單價（unitPrice）
•	增加客戶評價（Feedback）的功能，讓客戶可以寫（Writes）建議, 來針對已完成的交易留下評論（Comments）。一個建議由一個客戶寫，一個客戶可以寫這個建議多次。評價功能包括建議（suggestion）。
