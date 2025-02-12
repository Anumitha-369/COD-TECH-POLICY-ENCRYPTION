# COD-TECH-POLICY-ENCRYPTION

---
- **COMPANY** : CODTECH IT SOLUTIONS 
- **NAME** : ANUMITHA J 
- **INTERN ID** : CT6WGUL
- **DOMAIN** : " CLOUD COMPUTING " 
- **BATCH DURATION** : January 5th 2025 to February 20th 2025. 
- **MENTOR NAME** : SANTHOSH NEELA
---

<u>**TASK DESCRIPTION** :</u>

IMPLEMENT IAM POLICIES, SECURE STORAGE, AND DATA ENCRYPTION ON A CLOUD PLATFORM

<u>**DELIVERABLE:**</u>

CONFIGURED SECURITY POLICIES AND A REPORT DETAILING THE SETUP

**REPORT LINK** : https://docs.google.com/document/d/1-ziH61_TvJbXMBI0EpxlB0ga55dajTCU/edit?usp=drive_link&ouid=102703516643704836876&rtpof=true&sd=true



---

<u>**## Getting Started**</u>

Follow these steps to create **IAM policies** , **Secure Storage** and **Data Encryption** on a Cloud Platform .

---

Here's a streamlined version for creating **" IAM POLICY "** :

**STEP 1** : Sign in to the **AWS Management Console.**

**STEP 2** : Go to the **IAM** section.

**STEP 3** : Choose **Policies** and click **Create policy**.

**STEP 4** : Define **permissions** using the Visual Editor or **JSON Editor**.

Permissions setup must defined for , 

1 .  **Services**

2 . **Actions** 

3 . **Resources**  

4 . **Request Conditions**

**STEP 5** : **Review** and **create** the **policy**.

**STEP 6** : Attach the policy to a **user, group, or role**.

**STEP 7** : Test the policy to ensure it works as intended.

---

<U>**IAM POLICY CREATED :**</U>

![Image](https://github.com/user-attachments/assets/7ec2a710-131d-4f0e-b203-f3848dec44b3)

---

<U>**IAM USER POLICY CREATED :**</U>

![Image](https://github.com/user-attachments/assets/3d18f658-a82b-47bf-ab66-bd8e6ac8e013)

---
Creating the secure storage: 
**" Data Encryption using SSE-S3 and KMS-key "** :

SSE - Server-side-encryption 
SSE-S3 - Server-side-encryption for Buckets 
KMS - Key Management Service 

---

<U>**Data Encryption using SSE-S3 ( AES - 256 )**</U>

**STEP 1** : Sign in to the **AWS Management Console** and open the **S3** section.

**STEP 2** : Select your bucket.

**STEP 3** : Go to the **Properties** tab.

**STEP 4** : **Enable** default encryption and choose **Amazon S3 key (SSE-S3)**.


**STEP 5** : Upload your files – they’ll be automatically encrypted.

---

<U>**ENCRYPTED BUCKET :**</U>

![Image](https://github.com/user-attachments/assets/b1b3d041-924f-43f3-8a9c-5897836aea9b)

---

<U>**ENCRYPTED BUCKET POLICY :**</U>

![Image](https://github.com/user-attachments/assets/15b0e4c8-f71a-4e6b-9010-803ce2160b1c)

---


<U>**ERROR: FILE UPLOAD BLOCKED BY ENCRYPTION RULES**</U>

Here , It denied Object To Be Uploaded in Bucket as it is an Unencrypted File which does not satisfy The Condition of SSE-S3.


![Image](https://github.com/user-attachments/assets/6894b9b0-1e7c-4d31-8d6d-4c18adf717bd)

---


<U>**KMS KEY**</U>

- Storing the data as Cryptographic Keys - AWS KMS-Key .

- Here we will call the Keys For Encryption and as well as Decryption

- For Securing the Data like PI(Personal Identification , Bank Details Ets )

---

<U>**KMS POLICY :**</U>

![Image](https://github.com/user-attachments/assets/06046a7d-fdc3-4222-8e2e-e28e1061045e)

---

<U>**KMS-USER POLICY :**</U>

![Image](https://github.com/user-attachments/assets/3d982cc6-53aa-4021-8a48-f9faae8f6e1f)

---

<U>**KMS - ACCESS KEY  POLICY :**</U>

![Image](https://github.com/user-attachments/assets/4e13aea8-5353-42b7-ad3f-33d59a99f692)

---

<u>**Take Away Knowledge** </u> :

1 . **Stronger Security**: Use IAM policies and encryption to protect your data and control access.

2 . **Data Safety**: Encryption ensures your data is secure, even if someone gets unauthorized access.

3 . **Compliance**: Helps you meet legal and industry requirements.

4 . **Better Access Control**: Manage who can do what in your cloud environment.

5 . **Less Risk**: Reduces the chance of security problems.

---







