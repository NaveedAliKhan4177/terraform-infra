# 🌍 Terraform AWS Infrastructure Project

This project provisions **AWS Infrastructure** using **Terraform** — making deployment **easy, repeatable, and scalable** 🚀.

## 📦 Provisioned AWS Resources

- 🌐 **VPC** – Virtual Private Cloud for secure networking  
- 🖥 **EC2 Instance** – Compute resource for hosting applications  
- 📂 **S3 Bucket** – Scalable object storage for files & backups  

---

## 🛠 How to Use

1️⃣ **Initialize Terraform**  

terraform init
2️⃣ Review the Execution Plan


terraform plan
3️⃣ Apply the Configuration


terraform apply
4️⃣ Destroy Resources (Optional)


terraform destroy

📊 Project Architecture (Visual)
        ┌────────────────────┐
        │      Terraform     │
        └─────────┬──────────┘
                  │
        ┌─────────▼──────────┐
        │        AWS         │
        └───────┬─┬──────────┘
                │ │
         ┌──────▼ ▼──────┐
         │     VPC       │
         └──────┬────────┘
                │
     ┌──────────▼──────────┐
     │     EC2 Instance    │
     └──────────┬──────────┘
                │
     ┌──────────▼──────────┐
     │     S3 Bucket       │
     └─────────────────────┘


📌 Prerequisites
Before you begin, ensure you have:

✅ Terraform installed

✅ AWS CLI configured with credentials (aws configure)

✅ An AWS account

👨‍💻 Author
Naveed Ali Khan
💬 Feel free to connect and share your feedback!

📜 License
This project is licensed under the MIT License – free to use, modify, and distribute.

⭐ If you found this useful, consider giving it a star on GitHub!
