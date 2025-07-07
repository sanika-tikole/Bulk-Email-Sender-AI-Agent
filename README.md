# Bulk-Email-Sender-AI-Agent
# 📬 AI Email Agent

A Streamlit-based application to send **bulk personalized emails** for various purposes such as **marketing**, **interview scheduling**, or **custom messages** using Excel contact lists and optional PDF attachments.

---

# 🚀 Features

- 📁 Upload Excel sheet with `Name` and `Email` columns , job role should also present if you want send interview link 
- ✉️ Compose and send:
  - Marketing Emails with social links
  - Interview Invitations with job role and meeting link
  - Custom Bulk Emails
- 🔐 Secure Gmail App Password-based login
- 📎 Attach optional PDF files with each email
- 📊 Real-time status logs for sent emails
- 🎨 Built with [Streamlit](https://streamlit.io/) for a simple web UI

---

# 🧰 Tech Stack

- **Frontend:** Streamlit
- **Backend:** Python
- **Email Protocol:** SMTP (Gmail)
- **File Handling:** pandas, openpyxl
- **Attachments:** email.mime
- **Security:** SSL encryption

---
**🔐 Gmail App Password Setup**  
Enable 2-Step Verification for your Google Account.  
Go to App Passwords  
Generate an app password for "Mail" and "Other" app.  
Use this password in the app (not your real Gmail password).  

---

# Example

**Marketing Email Example:**
Hi John,

We’re excited to share our latest product with you!

Follow us:
LinkedIn: https://linkedin.com/company/mybrand
Instagram: https://instagram.com/mybrand

---

**📄 Interview Email Example**

Dear John,

You have been shortlisted for an interview for **Software Engineer** position.

We look forward to meeting you and discussing your qualifications further.

Meeting Link: https://meet.google.com/example-link  
Time: Monday, 8 July 2025 at 11:00 AM

Please be on time.  
Best regards,  
HR Team
---

**🛠️ Custom Bulk Email Example**

Dear Alice,

We hope this message finds you well.

This is a gentle reminder about the upcoming community event scheduled for this weekend.  
Your participation would mean a lot to us.

Feel free to reach out for any queries.  
Best regards,  
Event Coordination Team


**📊 Excel Format**  
Your Excel file should contain the following columns:

| Name        | Email              | Job Role (Optional)   |
|-------------|--------------------|------------------------|
| John Smith  | john@example.com   | Software Engineer      |
| Alice Brown | alice@example.com  | Data Analyst           |

📝 **Note:** The **`Job Role`** column is **optional** and used only when sending **Interview Emails**.

---
# Screenshots
 this consists all email sender block
![image](https://github.com/user-attachments/assets/0aaf5a78-7210-4c65-8dc3-c8cc594e634e)
# interview email
![image](https://github.com/user-attachments/assets/b657f850-9fd2-4067-b3a5-63d337b60c13)
# marketing email
![image](https://github.com/user-attachments/assets/070cefff-da93-4c31-8b56-b7e5cde1e0b9)
# custom email 
![image](https://github.com/user-attachments/assets/0a582ec8-4a52-4ad3-a512-6cfabfc63c76)

---

**✅ Use Cases**

- 🚀 Product marketing campaigns  
- 💼 HR interview scheduling  
- 🎓 College project or academic mailer  
- 🔔 Notification systems for small teams
  
---
🙌 Credits
Developed by [Sanika Tikole] 
