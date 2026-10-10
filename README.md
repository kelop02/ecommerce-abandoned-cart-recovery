# eCommerce Abandoned Cart Recovery - n8n + AI

An automated recovery system that recovers lost sales by sending AI-personalized recovery messages via Email and WhatsApp after cart abandonment.

## 🧠 How it Works
![System Architecture](assets/workflow-diagram.png)

**Flow:**
1.  **Trigger:** Shopify / WooCommerce Webhook fires on Abandoned Cart Event
2.  **Wait:** Wait 1 Hour (gives customer time to return naturally)
3.  **AI Writer:** AI Personalized Email Writer generates recovery copy using cart items & customer details
4.  **Actions:**
    -   4A: Send Recovery Email
    -   4B: Send Recovery WhatsApp Message

## ⚙️ n8n Workflow
![n8n Workflow](assets/n8n-screenshot.png)

## 🎥 Demo Video
[Watch Full Demo Here](your-loom-link)

## 🚀 Setup
-   Import `workflow.json` into n8n
-   Connect Shopify / WooCommerce Webhook
-   Connect OpenAI for AI Email Writer
-   Connect Email (SMTP/Gmail) & WhatsApp (Twilio/WhatsApp API) credentials
-   Activate workflow

## 📂 Files
-   `workflow.json` - Importable n8n workflow
-   `assets/workflow-diagram.png` - Architecture diagram

## 💰 Business Value
Recovers 15-25% of abandoned carts automatically. Direct ROI for eCommerce stores.
