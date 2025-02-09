# **🏦 Banking App**  
A modern Fintech Bank Application.

---

## **📋 Table of Contents**
- 🤖 Introduction  
- ⚙️ Tech Stack  
- 🔋 Features  
- 🤸 Quick Start  
- 🕸️ Code Snippets to Copy  
- 🔗 Links  
- 🚀 More  

---

## **🤖 Introduction**  
Built with Next.js, this is a financial SaaS platform that connects multiple bank accounts, displays transactions in real-time, allows users to transfer money to other platform users, and manage their finances efficiently.  

---

## **⚙️ Tech Stack**
- **Next.js**  
- **TypeScript**  
- **Appwrite**  
- **Plaid**  
- **Dwolla**  
- **React Hook Form**  
- **Zod**  
- **TailwindCSS**  
- **Chart.js**  
- **ShadCN**  

---

## **🔋 Features**
✅ **Secure Authentication:** Fully secure SSR authentication with proper validations and authorization.  
✅ **Bank Connectivity:** Integrates with Plaid to link multiple bank accounts.  
✅ **Dashboard Overview:** Displays total balance, recent transactions, and category-wise expenditure.  
✅ **Transaction History:** Paginated and filtered transaction history from different banks.  
✅ **Fund Transfers:** Enables users to transfer funds securely via Dwolla.  
✅ **Real-time Updates:** Automatically updates UI upon new bank connections.  
✅ **Fully Responsive:** Works seamlessly across desktop, tablet, and mobile.  

---

## **🤸 Quick Start**
### **Prerequisites**
Ensure you have the following installed:  
- **Git**  
- **Node.js**  
- **npm (or yarn)**  

### **Cloning the Repository**
```bash
git clone https://github.com/anilkumarraut/Banking_app.git
cd Banking_app
```

### **Installation**
```bash
npm install
```

### **Set Up Environment Variables**
Create a **`.env`** file in the root directory and add the following credentials:

```
#NEXT
NEXT_PUBLIC_SITE_URL=

#APPWRITE
NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
NEXT_PUBLIC_APPWRITE_PROJECT=
APPWRITE_DATABASE_ID=
APPWRITE_USER_COLLECTION_ID=
APPWRITE_BANK_COLLECTION_ID=
APPWRITE_TRANSACTION_COLLECTION_ID=
APPWRITE_SECRET=

#PLAID
PLAID_CLIENT_ID=
PLAID_SECRET=
PLAID_ENV=
PLAID_PRODUCTS=
PLAID_COUNTRY_CODES=

#DWOLLA
DWOLLA_KEY=
DWOLLA_SECRET=
DWOLLA_BASE_URL=https://api-sandbox.dwolla.com
DWOLLA_ENV=sandbox
```
🔹 Replace the placeholders with your actual credentials.

### **Running the Project**
```bash
npm run dev
```
Open **http://localhost:3000** in your browser to view the project.

---

## **🕸️ Code Snippets**
Some useful code snippets from this project:

- **`.env.example`**
- **`exchangePublicToken.js`**
- **`user.actions.ts`**
- **`dwolla.actions.ts`**
- **`bank.actions.ts`**
- **`BankTabItem.tsx`**
- **`BankInfo.tsx`**
- **`Copy.tsx`**
- **`PaymentTransferForm.tsx`**
- **`BankDropdown.tsx`** *(Missing from the video tutorial)*
- **`Pagination.tsx`**
- **`Category.tsx`**

---

## **🔗 Links**
- Official **Documentation**: [Appwrite](https://appwrite.io/), [Plaid](https://plaid.com/), [Dwolla](https://www.dwolla.com/)
- **GitHub Repository**: [Banking App](https://github.com/anilkumarraut/Banking_app)

---

## **🚀 More**
If you found this project helpful, consider contributing or exploring more advanced Next.js concepts.

---

### **👤 About the Developer**
This project is maintained by **Anil Kumar Raut**.  
🔗 GitHub: [github.com/anilkumarraut](https://github.com/anilkumarraut)  

