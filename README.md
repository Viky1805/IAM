# IAM

# EX - 6 Implementation Of Identity Management (Amazon IAM) For Your Team

## Name : Vignesh S
## Reg No : 212224110061
## Date : 28-08-2026

---

## Aim

To implement identity and access management (IAM) in AWS to securely control access to resources by creating and managing IAM users, groups, roles, and policies for team collaboration.

---

## Algorithm

1. Sign in to the AWS Management Console.
2. Navigate to the IAM service.
3. Create IAM groups with defined policies (e.g., Admin, Developer).
4. Create IAM users and assign them to appropriate groups.
5. Create IAM roles if cross-account or service-based access is needed.
6. Attach permissions using managed or custom policies.
7. Enable MFA (Multi-Factor Authentication) for users.
8. Monitor access using IAM Access Analyzer and CloudTrail.

---

## Procedure

### 1. Access IAM

- Go to *AWS Console* → *Services* → *IAM*.

### 2. Create IAM Groups

- Click *Groups* → *Create New Group*.
- Name the group (e.g., Admins, Developers).
- Attach predefined or custom policies (e.g., AmazonEC2FullAccess).

### 3. Create IAM Users

- Click *Users* → *Add Users*.
- Enter usernames and choose *Programmatic access* and/or *AWS Management Console access*.
- Assign users to the appropriate group.

### 4. Create IAM Roles (if needed)

- Go to *Roles* → *Create Role*.
- Select use case (AWS service, another AWS account).
- Attach necessary permissions.

### 5. Apply Policies

- Use AWS managed policies or create custom JSON-based policies.
- Assign them to users, groups, or roles.

### 6. Enable MFA

- For each user, go to *Security credentials*.
- Click *Manage MFA* → Choose *Virtual MFA device* (e.g., Google Authenticator).

### 7. Monitor IAM Usage

- Use *IAM Access Analyzer* to detect unused permissions.
- Use *CloudTrail* for auditing user activity.

---

### Output

## 1.IAM Group Creation

<img width="1917" height="1087" alt="image" src="https://github.com/user-attachments/assets/4b6e33a6-c13b-490e-8f0d-53843a4fa485" />


## 2.Attach an IAM Policy to the group

<img width="1917" height="1091" alt="image" src="https://github.com/user-attachments/assets/eea5cd0d-abe0-443f-88f1-6075cfe29c19" />

## 3.Create an IAM User

<img width="1917" height="1096" alt="image" src="https://github.com/user-attachments/assets/7cdaa3e7-f5d9-4a3b-830c-2c0b09d6625c" />

## 4.Add The user to the IAM Group

<img width="1917" height="1095" alt="image" src="https://github.com/user-attachments/assets/8d7e6f27-3b3c-4571-8f66-23fb78710064" />

## 5.Verify user Permissions

<img width="1917" height="1092" alt="image" src="https://github.com/user-attachments/assets/7eab34b2-901b-4057-9757-331baf0ac543" />

## 6.Verify Least-Privilege Access

<img width="1920" height="1200" alt="6" src="https://github.com/user-attachments/assets/c47de2dc-5dce-4ecb-b6d4-55cb3ab01f19" />


---


---

## Result

Successfully implemented identity and access management using Amazon IAM for secure team collaboration and controlled access to AWS resources.
