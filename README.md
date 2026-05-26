# CIS 288 — Lab 02: Cloud Account Setup (AWS | Azure | GCP)

**
ACCIDENTALLY MADE A REPO WITHOUT FORKING ASSIGNMENT. ITS STILL UP
**


**Course:** CIS 288 Cloud Computing — Community College of Philadelphia
**Due:** Sunday, May 25, 2026 by 11:59 PM
**Points:** 10

---

## Why This Lab Matters

Before you can do anything hands-on in this course, you need active accounts on all three cloud platforms — AWS, Azure, and Google Cloud (the Three Landlords). This lab walks you through setting up each one, verifying access, and documenting your work.

**Estimated time:** 45–60 minutes total | Complete before Week 3 class.

> 💳 **Important Note on Credit Cards:** Both AWS and Azure require a credit or debit card when signing up — even on free plans. **This is identity verification only. You will NOT be charged** as long as you use your credits responsibly. AWS charges a temporary $1 hold that is immediately refunded. GCP requires NO credit card (your $50 education coupon covers everything).

---

## Part 1 — AWS: Amazon Web Services
> `console.aws.amazon.com` | $100 in credits for new accounts | Credit card required (identity verification only)

| What You Get | Details |
|---|---|
| **$100 in AWS Credits** | Automatically applied to your account on signup. Covers EC2, S3, RDS, Lambda, and most services. |
| **Credit Validity** | 6 months from account creation date. Use them or lose them. |
| **Always Free Services** | Lambda (1M requests/month), DynamoDB (25GB), CloudWatch, and 30+ other services — free forever within limits. |
| **Credit Card Required?** | Yes — for identity verification only. AWS charges a $1 temporary hold that is immediately refunded. |
| **⚠️ Changed from 2025** | Before July 15, 2025, new accounts received '750 EC2 hours/month free for 12 months.' That model no longer exists. New accounts now receive $100 in credits instead. |

### Steps:
1. Go to [aws.amazon.com](https://aws.amazon.com) and click **Create a Free Account**
2. Enter your email address and choose a password
3. Enter your name and choose **Personal** account type
4. Enter a credit or debit card — required for identity verification. **You will NOT be charged while your $100 credit balance remains.**
5. Verify your phone number via text message
6. Choose the **Basic Support plan** (free)
7. Sign in to the AWS Management Console at [console.aws.amazon.com](https://console.aws.amazon.com)
8. Confirm your account name appears in the top-right corner
9. ⚠️ **Always set the region to `us-east-1 (N. Virginia)`** for all labs unless told otherwise

> ✅ **Confirm your $100 credit:** Go to **Billing Dashboard → Credits** to confirm your $100 promotional credit is applied. Set up a billing alert: **Billing → Budgets → Create Budget → set $5 threshold**.

### AWS Screenshots Required:
| Screenshot | Your Filename |
|---|---|
| AWS Console home page — logged in (account name visible top-right) | AWS Homepage |
| Billing → Credits page showing $100 promotional credit applied | AWS Credit |

---

## Part 2 — Microsoft Azure
> `portal.azure.com` | $100 credit valid for 30 days | Credit card required (identity verification only)

| What You Get | Details |
|---|---|
| **$100 Free Credit** | Valid for 30 days from account creation. Covers most Azure services. |
| **Free Services (12 months)** | 25+ services free for 12 months including VMs (750 hrs/month), Blob Storage (5GB), SQL Database. |
| **Always Free Services** | 55+ services always free — including Azure Functions, Cosmos DB, App Service. |
| **Credit Card Required?** | Yes — for identity verification only. You will NOT be charged during your free period. |

### Steps:
1. Go to [azure.microsoft.com/free](https://azure.microsoft.com/free) and click **Start free**
2. Sign in with a Microsoft account (personal Outlook or Hotmail works fine)
3. Fill in your profile information
4. Enter a credit or debit card — **you will NOT be charged during your free period**
5. Complete phone verification
6. Click **Go to Azure Portal** — you will land at [portal.azure.com](https://portal.azure.com)
7. Confirm your $100 credit: Go to **Subscriptions → Azure subscription 1 → Overview**

### Azure Screenshots Required:
| Screenshot | Your Filename |
|---|---|
| Azure Portal home page — logged in (your name visible top-right) | AZURE Homepage |
| Subscriptions → Azure subscription 1 showing $100 credit balance | AZURE Credit |

---

## Part 3 — Google Cloud Platform (GCP)
> `console.cloud.google.com` | $50 CCP Education Credit | No credit card required for coupon redemption

> 🎟️ Your GCP coupon has been pre-approved by Professor Chang through Google Cloud Education Grants — **at no cost to you and no credit card required for the coupon itself.**

### Step 1: Request Your $50 CCP Coupon Code
1. Click this link: [https://gcp.secure.force.com/GCPEDU?cid=n4gFp5Psw4Pl2WKpAdA3MAcx2%2FKarlEJvrG9JDR%2BAZt4KuYCEtEXCIDQgtxRWmkj/](https://gcp.secure.force.com/GCPEDU?cid=n4gFp5Psw4Pl2WKpAdA3MAcx2%2FKarlEJvrG9JDR%2BAZt4KuYCEtEXCIDQgtxRWmkj/)
2. Enter your **First Name, Last Name**, and your **@student.ccp.edu email address** — personal Gmail will not work here
3. Click **Submit** — check your @student.ccp.edu inbox for a confirmation email from Google
4. Save your coupon code — you will redeem it in Step 2

> 📌 One coupon per student email address. Do not click Submit more than once. **Redeem by: June 25, 2026. Valid through: February 25, 2027.**

### Step 2: Create Your GCP Account and Redeem Coupon
1. Go to [console.cloud.google.com](https://console.cloud.google.com) and sign in with your Google account (Gmail is fine here)
2. Complete account setup. A credit card may be required by Google to create the account.
3. Go to **Navigation Menu (☰) → Billing → Credits → Redeem a coupon**
4. Paste your coupon code. Confirm your $50 CCP Education Credit appears.
5. Create a new project called **CIS288-YourLastName** (e.g., CIS288-Chang). Always work inside this project for all labs.

### GCP Screenshots Required:
| Screenshot | Your Filename |
|---|---|
| GCP Console home — logged in showing your project name (CIS288-YourName) | GCP Homepage |
| Billing page showing your $50 CCP promotional credit applied | GCP Credit |
| Confirmation email from Google with coupon code (blur the actual code) | GCP email conf |
 
---

## Part 4 — Verify All Three Consoles

Fill in the verification table in your `.docx` submission file:

| Platform | Console URL | Logged In? | Credit / Status |
|---|---|---|---|
| **AWS** | console.aws.amazon.com | Yes / No | $100 Credits Active |
| **Azure** | portal.azure.com | Yes / No | $100 Credit Active |
| **GCP** | console.cloud.google.com | Yes / No | $50 Education Credit |

---

## Part 5 — How to Submit to This GitHub Repo

> **No terminal needed. Use the GitHub web interface.**

1. Download and complete the Word doc: **`CIS288_Lab02_CloudAccountSetup.docx`** (in this repo)
2. Rename your completed file: **`CIS288_Lab02_YourName.docx`** (e.g., `CIS288_Lab02_JohnSmith.docx`)
3. Make sure all your screenshot image files are saved on your computer
4. Come back to **this repo** in your browser
5. Click **Add file → Upload files**
6. Drag and drop your `.docx` **and all screenshot images** into the upload area
7. Scroll down and type a commit message: `lab02 complete - Your Name`
8. Click **Commit changes**
9. Verify all your files are visible in the repo ✅

---

## Grading Rubric — 10 Points

| Criterion | Points |
|---|---|
| AWS account created — console screenshot attached | 2 pts |
| Azure account created — console screenshot attached | 2 pts |
| GCP coupon redeemed — billing credit screenshot attached | 3 pts |
| All 3 consoles verified in Part 4 table | 1 pt |
| Uploaded to GitHub Classroom (completed .docx + screenshots) | 2 pts |
| **TOTAL** | **10 pts** |

---

## Troubleshooting

| Problem | Fix |
|---|---|
| AWS requires a credit card | This is normal. AWS uses your card for identity verification only. You will NOT be charged while your $100 credit balance remains. |
| Azure requires a credit card | Same as AWS — required for identity verification only. Your $100 Azure credit covers all charges. |
| GCP coupon email never arrived | Check your spam folder. Make sure you used your @student.ccp.edu email — personal Gmail will not work for the coupon request. |
| GCP coupon already used | Each student gets one coupon per email. If you used a different email by mistake, contact Professor Chang at schang@ccp.edu. |
| Azure portal shows no credit | Go to Subscriptions → Azure subscription 1 → Overview to see your credit balance. |
| Cannot find GitHub repo | Make sure you completed Lab 00 first. Check your email for the Lab 02 acceptance link, or use the link in Canvas Week 2 module. |

---

**Lab 02 complete — you now have accounts with all Three Cloud Landlords. Keep your login credentials safe. You will use all three accounts throughout this semester.**
