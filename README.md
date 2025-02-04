# Next - Dodo Payments Minimal Boilerplate

A minimal boilerplate to integrate [Dodo Payments](https://dodopayments.com/) with [Next](https://nextjs.org/).

## 🚀 Getting Started

Follow these steps to set up and run the project.

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/dodopayments/dodo-next-minimal-boilerplate.git
cd dodo-next-minimal-boilerplate
```

### 2️⃣ Get API Credentials
Obtain the **API Key** and **Webhook Signing Key** from your Dodo Payments dashboard while in Test Mode:
- **API Key:** [Get it here](https://app.dodopayments.com/developer/api-keys)
- **Webhook Key:** [Get it here](https://app.dodopayments.com/developer/webhooks)

### 3️⃣ Configure Environment Variables
Create a `.env` file in the root directory (where `.env.example` exists):
```sh
touch .env
```
Copy the contents from `.env.example` and update the following values with your keys from Dodo Payments:
```ini
DODO_API_KEY_TEST=your_api_key_here
DODO_PAYMENTS_WEBHOOK_KEY=your_webhook_key_here
```


### 4️⃣ Install Dependencies
```sh
npm install
```

### 5️⃣ Run the Project
```sh
npm run dev
```

## 🎉 You're all set!
Your Next js project is now configured with Dodo Payments. Happy coding! 🚀