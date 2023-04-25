# Database-demo
I. Topic and Introduction
Topic: Fresh fruit juice store
Introduction: Modern people live in a busy life and often have no time to supplement vitamins. For the purpose of helping people quickly obtain vitamins, the fresh fruit juice store makes a variety of fruits into juices, bringing people organic products, so that people have sufficient nutrition.

II. System function description
- Order online
+ Present nutritional information
+ Recommend juices with the proper nutritional content for the parts of your body that need nutritional supplements
+ Show fruit source and shelf life
- Choose a shipping method: Daily delivery
- Choose payment method: cash on delivery, credit card, bank transfer
- Comments

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
