# YFS Delivery – Shopify Integration Guide

This guide explains how to integrate your Shopify store with **YFS Delivery** as your delivery partner.

You will share your store domain with the YFS team, install the YFS Delivery app, and configure testing to complete the integration.

---

## 🧩 Step 1: Share Your Shopify Store Domain

1. In your Shopify Admin, go to:

   **Settings → Domains**

2. You will see your Shopify domain in the format:

your-store-name.myshopify.com

![Step 1](https://middleware-s3.s3.eu-west-1.amazonaws.com/shopify/screenshot1.png)

3. Copy this **myshopify domain** and share it with the **YFS Delivery Team**.

This allows the YFS team to generate a secure installation link for your store.

---

## 🔗 Step 2: Install the YFS Delivery App

1. The YFS team will provide you with a **Custom App Install Link**.

![Step 2](https://middleware-s3.s3.eu-west-1.amazonaws.com/shopify/screenshot2.png)

2. Click the installation link.

![Step 3](https://middleware-s3.s3.eu-west-1.amazonaws.com/shopify/screenshot3.png)

3. Shopify will open the app installation screen.

4. Click **Install app**.

![Step 4](https://middleware-s3.s3.eu-west-1.amazonaws.com/shopify/screenshot4.png)

5. Once installation is completed, you will see:

✅ **YFS Delivery Connected Successfully**

![Step 5](https://middleware-s3.s3.eu-west-1.amazonaws.com/shopify/screenshot5.png)

> ⚠️ If you see any error during installation, please contact the **YFS Delivery Team**.

---

## ⚙️ Permissions & Configuration

The YFS Delivery app automatically configures all required permissions and webhook subscriptions during installation.

No manual configuration is required.

The app enables access to:

- Orders (Read & Write)
- Fulfillments (Read & Write)
- Merchant Managed Fulfillment Orders (Read & Write)
- Order update and cancellation webhooks

![Step 6](https://middleware-s3.s3.eu-west-1.amazonaws.com/shopify/screenshot6.png)

---

## 🧪 Step 3: Testing the Integration

Once the app is installed:

1. Create a test order in your Shopify store.

2. Update the order tags to include the keyword: **YFS**
  ![Step 7](https://middleware-s3.s3.eu-west-1.amazonaws.com/shopify/screenshot7.png)

3. The YFS system will automatically process the order.

4. Verify that your test order appears in your **YFS Dashboard**.

5. After the order is picked up or handed over to YFS, you can mark your order as **Fulfilled** in Shopify.
  ![Step 8](https://middleware-s3.s3.eu-west-1.amazonaws.com/shopify/screenshot8.png)

6. Once fulfilled, the order in Shopify will automatically be updated with a tracking link.

7. After the order is delivered by YFS, you will see a **Delivered** tag added to the order.

> 💡 If the test succeeds, your integration is complete.

---

## ✅ Summary

| Step | Action |
|------|--------|
| 1 | Share your `myshopify.com` domain with YFS |
| 2 | Install YFS Delivery using the provided install link |
| 3 | App automatically configures permissions and webhooks |
| 4 | Create a test order and add tag `YFS` |
| 5 | Verify order in YFS dashboard |

---

> 📄 **Document maintained by YFS Delivery Integration Team**  
> Version: February 2026
