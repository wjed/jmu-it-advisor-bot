# 🧠 JMU IT Advisor Bot

A full-stack, serverless AI chatbot built for James Madison University’s Department of Information Technology. This project provides 24/7 access to academic advising, course planning, and department resources via an AI assistant powered by **Amazon Bedrock**, **OpenSearch**, and **AWS CDK**.

> 💡 Built by students, for students — this assistant automates common advising questions and helps scale departmental support.

---

## 🚀 Purpose

The JMU IT Advisor Bot is designed to:
- Provide **instant answers** to common academic questions (track requirements, course sequences, etc.)
- Help students **navigate the IT curriculum** and department opportunities
- Reduce advisor workload by offloading repetitive questions
- Serve as a **scalable prototype** that can be extended to other JMU departments

---

## 🧱 Tech Stack

| Layer         | Technologies Used                                             |
|---------------|---------------------------------------------------------------|
| Frontend      | React.js, Tailwind CSS, CloudFront, Route 53                  |
| Backend       | Python, FastAPI, AWS Lambda, Boto3                            |
| AI Integration| Amazon Bedrock (LLM + Knowledge Base), OpenSearch             |
| Storage       | Amazon S3 (files & static site), DynamoDB (chat/session logs) |
| APIs          | API Gateway                                                   |
| Infra as Code | AWS CDK (Python)                                              |
| Monitoring    | CloudWatch, IAM roles & permissions                           |

---

## 🌐 Features

- 💬 Natural language chatbot interface
- 📄 Document-grounded answers from syllabi, degree plans, etc.
- 🧠 Knowledge base powered by Bedrock + OpenSearch
- 🔒 Secure, scalable, and fully serverless (no servers to manage)
- 🛠️ Admin dashboard for uploading docs and monitoring usage
- 🧪 Built-in feedback + testing tools for students & faculty

---

## 📅 Project Timeline (Fall 2026)

| Month       | Milestones |
|-------------|------------|
| **August**  | Infra setup (CDK, S3, CloudFront, Lambda, API Gateway) |
| **September** | Bedrock Knowledge Base, OpenSearch domain, DynamoDB schema |
| **October** | Backend + frontend integration, document ingestion, RAG testing |
| **November** | MVP launch to ambassadors, admin dashboard, polish + feedback |
| **December** | Final testing, documentation, and presentation |

---

## 📁 Repository Structure (Planned)

jmu-it-advisor-bot/
├── frontend/ # React client (chat UI + admin portal)
├── backend/ # FastAPI handlers + Lambda interface
├── cdk/ # CDK infrastructure as code (Python)
├── docs/ # Syllabi, degree plans, FAQs for KB
├── scripts/ # Deployment + ingestion automation
└── README.md
