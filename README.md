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



---

<U>**IAM USER POLICY CREATED :**</U>

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

---

<U>**ENCRYPTED BUCKET POLICY :**</U>

---


<U>**ERROR: FILE UPLOAD BLOCKED BY ENCRYPTION RULES**</U>

Here , It denied Object To Be Uploaded in Bucket as it is an Unencrypted File which does not satisfy The Condition of SSE-S3.


picture

---


<U>**KMS KEY**</U>

- Storing the data as Cryptographic Keys - AWS KMS-Key .

- Here we will call the Keys For Encryption and as well as Decryption

- For Securing the Data like PI(Personal Identification , Bank Details Ets )

---

<U>**KMS POLICY :**</U>

---

<U>**KMS-USER POLICY :**</U>

---

<U>**KMS - ACCESS KEY  POLICY :**</U>

---

<u>**Take Away Knowledge** </u> :

1 . **Stronger Security**: Use IAM policies and encryption to protect your data and control access.

2 . **Data Safety**: Encryption ensures your data is secure, even if someone gets unauthorized access.

3 . **Compliance**: Helps you meet legal and industry requirements.

4 . **Better Access Control**: Manage who can do what in your cloud environment.

5 . **Less Risk**: Reduces the chance of security problems.

---






