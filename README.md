# Lab 4-IAM-RECOVER-PASSWORD-OF-USER

https://www.youtube.com/watch?v=NsFmpvNKknM

IAM LAB 5 – Recover Password for IAM User

# Part 1: Create User (Without Finalizing Password for Use)

Log in to AWS Console (root/admin)

Go to IAM (Identity and Access Management)

Click Users → Create user

User Setup

Enter User name (example: test-user)

Select:
✅ Provide user access to the AWS Management Console

Choose either:

Auto-generated password (but don’t download/forget it)
OR

Skip noting the custom password

Keep:
✅ User must create a new password at next sign-in

👉 Click Next → Skip permissions → Create user

Situation Now

User exists

But password is unknown / not available

User cannot log in

# Part 2: Assign New Password (Admin Reset)

Go to IAM

Click Users

Select your user (test-user)

Go to Security Credentials

Click Security credentials tab

Set New Console Password

Under Console password → Click Manage

Choose:
✅ Enable console access (if not already enabled)

Select:
✅ Custom password

Enter a new temporary password

Tick:
✅ User must create a new password at next sign-in

👉 Click Apply

# Part 3: User Login (Incognito Window)

Open Incognito / Private window

Use IAM login URL

Enter:

Username

New temporary password

Part 4: Force Password Change

AWS will prompt:

Enter Current password (temporary one)

Enter New password

Confirm new password

👉 Click Change password

# Final Result

User recovered without old password

Admin assigned new password

User successfully logged in

Password updated securely

# Key Concept (Important)

Admin can reset password anytime

Old password is not required
