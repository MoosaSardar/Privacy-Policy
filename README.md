# Privacy Policy for Industrial Stores

**Effective Date:** October 24, 2024  
**Last Updated:** October 24, 2024  

---

## 1. Introduction

Welcome to **Industrial Stores** ("we," "our," or "us"). We are committed to protecting your privacy and ensuring that your personal data is handled securely and transparently.

This Privacy Policy describes how we collect, use, store, share, and protect your personal information when you use our mobile application, **Industrial Stores** (the "App"), as well as your rights regarding your personal data—including how you can easily access, edit, or **delete your account and data directly within the App on your own**.

By downloading, accessing, or using the App, you agree to the collection and use of information in accordance with this Privacy Policy. If you do not agree with this policy, please do not use the App.

---

## 2. Information We Collect

We collect information to provide, improve, and secure our industrial marketplace services for buyers, sellers, and store owners.

### A. Personal Information You Provide to Us
* **Account Registration:** Full Name, Email Address, Password (encrypted via Firebase Auth), User ID (UID).
* **Business & Profile Information:** Store/Company Name, Contact Phone Number, WhatsApp Number, Physical Address, City, Country, Profile Photo, and Store Banner/Cover Image.
* **Product Listings & Posts:** Descriptions, categories, machinery specs, prices, and product images uploaded for sale or inquiry.
* **Business Advertisements & Promotions:** Promotional ad banners, footer ads, target links, ad images, and duration requested for business promotion.

### B. In-App Communications & Audio Data
* **Chat Messages:** Text messages, image attachments, and timestamps exchanged between buyers and sellers.
* **Audio / Voice Notes:** Voice recordings made when using the audio message recording feature within the chat screen.
  > **Note on Audio Data:** Audio recording is captured **only** when you actively press and hold or use the voice recording button in the chat interface. Audio files are processed solely to send voice messages to the designated recipient in your chat conversation.

### C. Financial & Payment Information
* **Google Play Billing Transactions:** Order ID, Purchase Token, Product ID, Transaction Amount, and Timestamp for in-app ad promotion payments.
  > **Note on Financial Data:** All financial transactions (credit card, debit card, or Google Pay details) are processed directly and securely by **Google Play Billing**. We **do not** collect, receive, or store your raw financial account numbers or credit card details on our servers.

### D. Automatically Collected Device & Technical Information
* **Push Notification Tokens:** Firebase Cloud Messaging (FCM) device tokens used to deliver real-time notifications for new chat messages, inquiries, and app updates.
* **Device & Usage Details:** Device model, operating system version, unique device identifiers, IP address, app crash logs, and performance metrics.

---

## 3. App Permissions Requested

To provide full app functionality, the App requests access to certain device permissions:

| Permission | Purpose |
| :--- | :--- |
| `RECORD_AUDIO` | Required **only** to allow you to record and send voice notes/audio messages directly to other users in the chat. |
| `POST_NOTIFICATIONS` | Required to send real-time notification alerts for new buyer/seller messages, post status updates, and app alerts. |
| **Camera & Media / Storage Access** | Required to allow you to select or capture photos for profile pictures, store banners, product listings, ad banners, or chat image attachments. |

---

## 4. How We Use Your Information

We use the collected information for the following business and operational purposes:
1. **Provide and Maintain the App Services:** Facilitate product listings, store management, buyer-seller connections, and in-app messaging.
2. **Account Management & Authentication:** Verify your identity and maintain secure access to your account via Firebase Authentication.
3. **Facilitate Communications:** Deliver chat messages, voice notes, and push notifications to users.
4. **Process Business Advertisements:** Verify and activate paid business promotion ads via Google Play Billing integration.
5. **Customer Support & Service Optimization:** Address user support inquiries, troubleshoot technical issues, fix bugs, and optimize app performance.
6. **Security & Fraud Prevention:** Protect users against fraudulent activities, unauthorized access, spam, and violations of our Terms of Service.

---

## 5. Self-Service Data Deletion & Your Data Rights

We strongly believe in user control over personal data. You have the right to access, modify, export, or **permanently delete your data on your own at any time**.

### A. How to Delete Your Entire Account & Data On Your Own (Self-Service)
You can permanently delete your entire account and all associated data directly inside the App without needing to submit a support request or wait for manual approval.

**Step-by-step instructions to delete your account:**
1. Open the **Industrial Stores** App and sign in to your account.
2. Go to the **Main Menu / Settings / Profile** screen.
3. Tap on **"Delete Account"**.
4. A confirmation dialog will appear explaining that account deletion is permanent and cannot be undone.
5. Type **`delete`** into the text field to confirm your intent.
6. Tap the **"Delete Account"** button.

**What happens when you delete your account:**
* **Profile & User Records:** Your user profile, seller records, buyer profile, and contact details are immediately and permanently removed from our active database (Firestore `users`, `sellers`, and `buyers` collections).
* **Published Listings & Posts:** All product listings and posts published by your account are permanently deleted.
* **Business Ads:** Any active or pending advertisement promotions associated with your account are deleted.
* **Authentication Account:** Your login credentials and authentication record in Firebase Authentication are permanently deleted.
* **Stored Files:** Uploaded profile photos, store banners, and product images stored in Firebase Cloud Storage are deleted.

---

### B. Deleting Specific Data (Posts, Ads, Messages) On Your Own
You do not need to delete your whole account to remove specific items:
* **Delete Individual Posts:** Go to your store or post list, tap the options menu (**⋮**) on the post, and select **"Delete Post"**.
* **Delete Business Advertisements:** Go to **Promote Business**, select your advertisement, and tap **"Delete"**.
* **Delete Chat Messages & Voice Notes:** In any chat screen, select message(s) and tap the **Delete** icon; or swipe/delete the entire conversation from the Messages list.
* **Update Profile Info:** You can edit, remove, or clear your phone number, address, business name, or profile image anytime via the **Edit Profile** screen.

---

### C. Requesting Manual Data Deletion (Web / External Request)
If you cannot access the App or wish to request manual data deletion externally:
* Send an email to our privacy team at: **`industrialstores101@gmail.com`**
* Subject Line: **`Account & Data Deletion Request - [Your Registered Email]`**
* We will verify your identity and complete the deletion of your account and data within **30 days** of receiving your request.

---

## 6. Data Storage, Retention, and Security

### A. Data Storage & Third-Party Infrastructure
Your data is securely processed and stored using industry-leading cloud infrastructure provided by **Google Firebase** (Google Cloud Platform). Data centers adhere to strict global security standards (ISO 27001, SOC 2, GDPR compliance).

### B. Data Retention
* Active Account Data is retained as long as your account remains active.
* Once you delete your account or specific content, it is deleted immediately from our active database. Backup copies (kept solely for disaster recovery) are automatically overwritten within standard backup rotation cycles (up to 30 days).

### C. Security Measures
We use administrative, technical, and physical security measures to safeguard your personal data, including:
* HTTPS / TLS encryption for all data transmitted between the App and our backend servers.
* Strict database access rules and token-based user authentication.
* Restricted administrative permissions.

---

## 7. Third-Party Services We Use

We integrate trusted third-party service providers to power specific app functionality. These third parties have access to your data only to perform specific tasks on our behalf and are obligated not to disclose or use it for any other purpose:

1. **Google Firebase Authentication & Cloud Firestore / Storage:**
   * Used for user authentication, cloud database, and image/file hosting.
   * [Google Privacy Policy](https://policies.google.com/privacy)
2. **Firebase Cloud Messaging (FCM):**
   * Used for delivering push notifications.
   * [Firebase Privacy & Security](https://firebase.google.com/support/privacy)
3. **Google Mobile Ads (AdMob):**
   * Used to serve in-app advertisements. AdMob may collect device advertising IDs and location/network signals to serve relevant ads.
   * [How Google uses information from apps](https://policies.google.com/technologies/partner-sites)
4. **Google Play Billing:**
   * Used to process securely in-app payments for advertisement promotion packages.
   * [Google Play Terms of Service](https://play.google.com/about/play-terms/)

---

## 8. Children's Privacy

Our App is designed exclusively for business users, industrial store owners, and commercial buyers/sellers. It is **not directed to children under the age of 13** (or under 16 in the European Union). We do not knowingly collect personal information from children. If we discover that a child under 13 has provided us with personal information, we will delete it immediately.

---

## 9. International Data Transfers & Rights (GDPR / CCPA / CPRA)

If you are accessing the App from the European Economic Area (EEA), the United Kingdom, California (USA), or other regions with specific data privacy laws, you possess the following rights:
* **Right to Access / Know:** The right to request copies of the personal data we hold about you.
* **Right to Rectification:** The right to correct inaccurate or incomplete data.
* **Right to Erasure (Right to be Forgotten):** The right to delete your personal data (available directly in-app or via request).
* **Right to Restrict or Object to Processing:** The right to limit or object to how we process your data.
* **Right to Data Portability:** The right to request a copy of your data in a structured, machine-readable format.

---

## 10. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the **"Last Updated"** date at the top of this document. You are advised to review this Privacy Policy periodically for any changes.

---

## 11. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your data privacy, please contact us at:

* **App Name:** Industrial Stores
* **Email:** `industrialstores101@gmail.com`
* **Phone / WhatsApp:** `+923246663831`
* **Address:** `H#s335 street#4 Boley-jhugi Faisalabad Pakistan`
