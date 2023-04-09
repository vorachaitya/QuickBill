<h1 align="center">
  <a href="https://github.com/vorachaitya/QuickBill">
    <img src="https://user-images.githubusercontent.com/90527884/230767377-218e9e23-c22c-4f7f-bd21-28a7b8f16ca1.png" alt="QuickBill" width="300" height="250">
  </a>
  <br>
</h1>
<div align="center">
  I2C2 hack || Team AutoBots
</div>

### 🤔 Problem Statement
Whenever we pay bills at shop, we get a bill's paper receipt which although is short in length but eventually when put together globally results in huge amount of paper loss.Also, we usually tend to throw away the bill receipts as it is difficult to file them, thereby refraining us to refer past bill details in future.

At times, it becomes difficult for shop owner to keep a track of his current available stock manually.There are chances of the bills being tampered by third party as well.

### 🚀 Solution
Thus, we have developed ***QuickBill***, a system wherein hardcopy of bills, i.e, paper bills are not generated at any point of time thereby making it environment friendly to save trees.

To make life of shop owner further easier, we have developed an inventory management portal for them wherein they can keep track of their product stock easily.Now, the entire bill generation and payment system will be carried out smoothly. Entire process can be further understood as shown below:

### 😊 Flowchart
<img src="https://user-images.githubusercontent.com/90527884/230767329-560e5ad6-371d-44cd-ae9c-a864fdb07b53.jpeg" alt="BillEase" width="1000" height="550">

### ✨Features
QuickBill is splitted into parts: **web app** and **mobile app**. It has two access levels - **shop owner** and **customer**.
- ***Web Application***
  - Used by shop owners to access inventory management.
  - Supports addition of product, details, price, quantity to database
  - Barcode is generated and assigned to each newly added product 
  - Updation and deletion of products from inventory
  - Overall items of inventory are displayed and an excel sheet is generated
- ***Mobile Application***
This has two access levels:
 1. **Shop owner**
    - Uploads an excel sheet containing details of products present in inventory
    - Scans barcode of products purchased by customer and generates a bill(pdf format)
    - To ensure security and authorization, bill is stored on **IPFS** (Inter-Planetary File System) where it becomes immutable and cannot be tampered by third-party       - QR-code for bill payment is generated which is sent to respective customer
    - Updates inventory after selling of products
    - View line chart depicting customers with their purchase ranges in order to have better understanding of customer choices and make plans to increase thier sales accordingly
 2. **Customer**
    - Buys products whose barcodes are scanned by owner and bill is sent to them
    - Can either pay in cash or UPI
    - Recieves QR-code for payment for UPI payment
    - Can access his/her bill history for future use
    - View line chart depicting bill amount with thier dates in order to analyse thier expenditure and take necessary actions
    
###  🤖Resources
- [Demo Video](https://www.youtube.com/watch?v=D03AIRtRgEw)
- [GitHub Repository](https://github.com/vorachaitya/QuickBill)
- [Hosted Website Link](https://billweb.harshilshah99.repl.co/)
- [Devfolio Submission](https://devfolio.co/projects/quickbill-6fb4)
- [APK Link](https://drive.google.com/file/d/1nfLXcerYDjP64WUwogYJWWnq26dBmPr_/view?usp=sharing)

### ⚙️ Tech Stack
1. **Web Development**
- Frontend : React.js ,TailwindCSS ,Bootstrap
- Backend : Firebase
2. **App Development**
- Frontend :Flutter, Dart
- Backend : Firebase

### 🔍 Future Scope!
- Reward customer with scratch cards for each payment done
- Payment via modes like debit/credit cards, internet banking
- Track user behaviour and predict about their future purchases

### 👨‍💻 Team Members
- [Harshil Shah](https://github.com/harshilshah99)
- [Ananya Bangera](https://github.com/ananya-bangera)
- [Chaitya Vora](https://github.com/vorachaitya)
