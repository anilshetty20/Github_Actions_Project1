# Github_Actions_Project1
Automatic Python App Testing

Pipeline Flow (What Actually Happens)

When you push code:

git push origin main

GitHub pipeline runs:

Trigger workflow
↓
Create runner (Ubuntu VM)
↓
Checkout code
↓
Install Python
↓
Install dependencies
↓
Run tests
↓
Show result in Actions tab
