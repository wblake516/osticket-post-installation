<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# **osTicket - Post-Install Configuration**
This guide provides a step-by-step walkthrough for configuring osTicket after installation.

---

## **Video Demonstration**
- ### [YouTube: How To Configure osTicket, Post-Installation](https://www.youtube.com)

---

## **Environments and Technologies Used**
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Protocol (RDP)
- Internet Information Services (IIS)

---

## **Operating System Used**
- Windows 10 (21H2)

---

## **Post-Install Configuration Objectives**
- Configure system settings
- Set up email piping and fetching
- Customize help desk settings
- Manage user roles and permissions
- Finalize security configurations

---

## **Configuration Steps**

### **Step 1: Configure System Settings**
After logging into the admin panel, navigate to **Admin Panel > Settings > System** and adjust the following:
- Set the Helpdesk Name and Default Email Address.
- Enable or disable system logging.
- Configure time zone settings.

### **Step 2: Set Up Email Fetching & Piping**
- Go to **Admin Panel > Emails > Settings**.
- Enable **IMAP/POP** or **SMTP** for email fetching.
- Configure email piping to automate ticket creation from email messages.

### **Step 3: Customize Help Desk Settings**
- Navigate to **Admin Panel > Help Topics**.
- Create custom help topics to categorize support requests.
- Define response templates for frequently asked questions.

### **Step 4: Manage User Roles and Permissions**
- Assign agents to departments and set access levels.
- Configure team roles to restrict or grant privileges.
- Define ticket assignment and workflow rules.

### **Step 5: Finalize Security Configurations**
- Enable reCAPTCHA for login security.
- Configure session timeout policies.
- Restrict system access by IP filtering.

---

## **Conclusion**
By following these steps, your osTicket system will be properly configured to handle support requests efficiently and securely.

