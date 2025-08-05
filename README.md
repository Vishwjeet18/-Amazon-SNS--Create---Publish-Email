# -Amazon-SNS--Create---Publish-Email


 Here’s a **step-by-step guide** to:

> ✅ **Create an Amazon SNS Topic**
> ✅ **Create an Email Subscription**
> ✅ **Send a Verification Email**
> ✅ **Send a Test Email using SNS**

---

### ✅ Step 1: Go to SNS Console

1. Open AWS Management Console
2. Search for and open **Simple Notification Service (SNS)**
3. Click on **Topics** from the left sidebar
4. Click on **Create topic**

---

### ✅ Step 2: Create a Topic

1. Choose **Standard** type
2. **Name:** Enter a topic name (e.g., `MyEmailTopic`)
3. Leave other settings as default
4. Click **Create topic**

---

### ✅ Step 3: Create Email Subscription

1. After the topic is created, click on it to open
2. Click **Create subscription**
3. **Protocol:** Choose **Email**
4. **Endpoint:** Enter the email address where you want to receive messages

   > Example: 'vishwjeetbidkar1805@gmail.com '
5. Click **Create subscription**

---

### ✅ Step 4: Confirm Subscription (Verify Email)

1. Open the email inbox you used
2. You will receive a **confirmation email from AWS SNS**
3. Click on the **confirmation link** inside the email
4. Once confirmed, the subscription status will change from `PendingConfirmation` to `Confirmed` in the SNS dashboard

---

### ✅ Step 5: Send a Test Email (Publish Message)

1. Go back to the **SNS Topic**
2. Click **Publish message**
3. **Subject:** (e.g., `Holiday`)
4. **Message body:** Write your message (e.g., `📢 Please note that our office will remain closed on Rakshabhandhan, [09-08-2025], in observance of the holiday..`)
5. Click **Publish message**

📩 You will receive the email in your inbox!



---

Let me know if you want the same steps in **Marathi**, or with **screenshots**, or using **Python (boto3)**.
