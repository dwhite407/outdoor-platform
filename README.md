# Outdoor Platform

Multi-tenant SaaS storefront platform for outdoor and fishing equipment businesses.

This application allows outdoor equipment companies to subscribe and manage their own storefronts, upload products, and connect with customers within a centralized marketplace platform.

---

## 🚀 Project Goals

This project serves two primary purposes:

### 1. Real Business Application
- Built to support a family-operated outdoor equipment business  
- Designed to scale into a subscription-based B2B storefront platform  

### 2. Technical Skill Development
- Preparation for a software engineering internship  
- Focus on TypeScript, Python, AWS (Lambda, S3), and production deployment practices  

---

## 🏗️ Tech Stack (Current & Planned)

### Frontend
- Next.js (App Router)
- TypeScript
- Tailwind CSS

### Backend
- Next.js API routes
- Prisma ORM
- PostgreSQL (local → AWS RDS planned)

### Cloud / DevOps (Planned)
- AWS S3 (product image storage)
- AWS Lambda (image processing & background jobs)
- AWS SES (email notifications)
- CloudWatch (logging)

### Tooling
- VS Code
- ESLint
- Prettier
- Git

---

## 📂 Project Structure (Early Stage)

outdoor-platform/
│
├── src/
│ └── app/
│ ├── page.tsx
│ └── admin/
│ └── page.tsx
│
├── prisma/
│ └── schema.prisma
│
├── package.json
└── README.md


---

## 🧠 Architecture Vision

This application is being built as a **multi-tenant SaaS platform**, meaning:

- Multiple businesses can subscribe  
- Each business manages its own storefront  
- Role-based access control:
  - Platform Admin
  - Business Admin
  - Public Users  
- Products are isolated per business  
- Subscription gating controls storefront visibility  

---

## 🛠️ Current Status

- ✅ Next.js project initialized  
- ✅ TypeScript configured  
- ✅ Admin route created  
- 🔄 Prisma database schema in development  
- 🔄 Local PostgreSQL setup pending  
- 🔜 AWS integration planned  

---

## 🔮 Future Roadmap

- [ ] Multi-tenant database schema
- [ ] Authentication + role-based access
- [ ] Product CRUD system
- [ ] Image uploads (AWS S3)
- [ ] Lambda image processing pipeline
- [ ] Subscription management
- [ ] Deployment to production
- [ ] CI/CD pipeline

---

## 📌 Why This Project Matters

This project is intentionally structured to simulate real-world SaaS development, including:

- Cloud integration  
- Multi-tenant data modeling  
- Role-based security  
- Infrastructure planning  
- Scalable backend architecture  

It is being developed with long-term maintainability and production deployment in mind.

---

## 👤 Author

Drew White  
Computer Science Student  
Focused on full-stack and cloud development  

---

## 📄 License

Private project – all rights reserved.
