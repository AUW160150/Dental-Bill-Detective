# Dental-Bill-Detective
Smart analysis for dental invoices using real pricing benchmarks and code-level comparisons.
# 🦷 Dental Bill Analyzer
Wesbite: https://medical-debt-analyzer.replit.app/
Demo Video: https://drive.google.com/file/d/10oENI09gIJUY11RMzCkIn75edDlDkdP0/view?usp=sharing

**AI-powered dental bill review tool that helps patients understand charges, detect overpricing, and generate negotiation-ready outputs.**

---

## 🎯 Target

Build a practical, real-world tool that helps patients:

- Understand confusing dental bills  
- Detect overcharges and billing errors  
- Compare prices against fair benchmarks  
- Generate scripts and appeal letters  
- Take action instead of blindly paying  

This project focuses on **patient leverage** — turning a dental invoice into clear, actionable insights.

---

## 🧠 What This Project Does

The Dental Bill Analyzer reads itemized dental bills and performs:

- CDT code extraction  
- Price comparison vs benchmark datasets  
- Error detection (duplicates, unbundling, inflated pricing)  
- Savings estimation  
- Negotiation script generation  
- Appeal letter generation  

It converts messy bill text into a structured, easy-to-understand report.

User uploads bill text / image
↓
AI extracts CDT codes + prices
↓
Benchmarks against pricing dataset
↓
Detects overcharges & errors
↓
Calculates fair price vs billed price
↓
Generates negotiation scripts & letters
↓
Actionable savings summary


---

## 🛠 Tech Stack

- Replit environment  
- Node.js  
- BEM extracted file 
- AI-based text parsing for dental code extraction  
- Custom pricing datasets  
- OCR pipeline for bill images  
- Local processing for privacy  

---

## 🔍 Key Features

### Smart Code Extraction
Reads unstructured dental bills and identifies CDT procedure codes automatically.

### Fair Price Analysis
Compares billed amounts to benchmark pricing from curated datasets and treatment records.

### Error Detection
Flags:
- Duplicate charges  
- Unbundled procedures  
- Suspicious markups  
- Out-of-range pricing  

### Savings Estimate
Shows:
- Total billed  
- Fair value estimate  
- Potential savings  
- % markup  

### Negotiation Toolkit
Auto-generates:
- Phone negotiation scripts  
- Appeal letters  
- Questions to ask billing departments  

---

## 🔒 Privacy Approach

- No bill data stored permanently  
- PII redaction pipeline  
- Local processing where possible  
- Designed for secure analysis  

---

## 📊 Example Output

Your dental bill is 52% above fair pricing.
Potential savings: $1,240

Detected issues:

Duplicate X-ray charge

Cleaning priced 2.3× benchmark

Unbundled exam code

Recommended action:
Call billing department and request adjusted rate using provided script

---

## 🧪 Current Status

This is an **active build + experiment** focused on:

- Improving CDT extraction accuracy  
- Expanding pricing datasets  
- Testing real-world bills  
- Refining negotiation output quality  
- Making the tool usable for non-technical patients  

---

## 🧭 Why This Exists

Dental billing lacks transparency.  
Patients rarely know if prices are fair.  
Most overpay without realizing it.

This project aims to give patients:

**clarity → leverage → savings**

---

## 📌 Next Steps

- Expand pricing benchmark datasets  
- Improve OCR accuracy  
- Add insurance-aware analysis  
- UI polish for public use  
- Deploy hosted version  
- Add report export  

---

## ⚠️ Note

This tool provides analysis and guidance only.  
It does not replace professional financial or legal advice.

---

## 💡 Vision

A future where patients can upload any healthcare bill  
and instantly know:

**“Is this price fair — and what should I do about it?”**


---

## 🚀 Core Workflow

```mermaid
flowchart TD

A[User uploads dental bill<br/>Text / PDF / Image]
B[Privacy Layer<br/>PII redaction]
C[AI Extraction<br/>Identify CDT codes + prices]
D[Structured Data<br/>Clean bill format]
E[Benchmark Lookup<br/>Pricing dataset + records]
F[Error Detection<br/>Duplicates / unbundling / markups]
G[Fair Price Calculation<br/>Compare billed vs benchmark]
H[Savings Estimate<br/>Potential overcharge]
I[Generate Outputs<br/>Scripts + appeal letters]
J[Actionable Report<br/>What to do next]

A --> B
B --> C
C --> D
D --> E
E --> F
F --> G
G --> H
H --> I
I --> J
