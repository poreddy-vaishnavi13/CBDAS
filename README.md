# CBDAS
# Role-Based Access Control using AWS IAM for EC2 Management

## 1. Create IAM Group
- Go to Amazon Web Services Console
- Navigate to IAM → User groups
- Click Create group
- Enter group name:
- Click Next
---

## 2. Attach Policies (S3 + EC2 Full Access)
In Attach permissions policies:

### Search and select:
- AmazonS3FullAccess
- AmazonEC2FullAccess
- Click Next → Create group

✔️ Now this group has full access to:
- Amazon S3
- Amazon EC2
---

## 3. Create IAM User
- Go to IAM → Users
- Click Create user
- Enter username 
### Select access type:
- AWS Management Console access
- Programmatic access (optional)
- Click Next

---

## 4. Assign User to Group
### Choose:
- Add user to group
### Select:
- EC2-S3-FullAccess-Group
- Click Next → Create user

✔️ User now inherits permissions from the group (RBAC concept)

---

## 🚀 Conclusion
- Create Group → Attach Policies → Add Users
### Policies used:
- AmazonEC2FullAccess
- AmazonS3FullAccess
- This is Role-Based Access Control (RBAC) in IAM
## Live DEMO:
Link: N_xhW7nWJD4

