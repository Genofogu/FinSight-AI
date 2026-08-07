# FinSight AI

> **AI-Powered Smart Invoicing & Expense Intelligence Platform for Small Businesses**

FinSight AI is a modern AI-powered SaaS platform that helps freelancers, startups, and small businesses digitize invoices, automate expense tracking, and gain intelligent financial insights.

Instead of manually entering invoice details, users can upload receipts, invoices, or PDFs, and FinSight AI automatically extracts structured data using OCR and AI, organizes expenses, and provides actionable business insights.

---

## 👥 Project Team

| Role | Member |
|------|--------|
| Project Lead & Full Stack AI Developer | **Genofogu** |
| Full Stack Developer | **Anubhav Dubey** |
| Backend Developer | **Bhumika Goyal** |
| AI & Testing Engineer | **Vanshika** |
| Frontend Developer | **Shradha Sharma** |

#  Features

##  Smart Invoice OCR

- Upload Images
- Upload PDFs
- Drag & Drop Support
- Automatic OCR Extraction
- Editable Extracted Data
- Confidence Score
- Cloudinary Storage

---

##  AI Financial Assistant

Ask questions like:

- How much did I spend on fuel this month?
- Which vendors have pending payments?
- Compare July and August expenses.
- Show my highest business expenses.
- Generate monthly financial summaries.

Powered by Google Gemini.

---

##  Expense Analytics

- Monthly Expense Trends
- Revenue vs Expense
- Category Breakdown
- Vendor Analytics
- Cash Flow Dashboard
- Tax Summary
- Interactive Charts

---

##  Vendor & Customer Management

- Vendor Profiles
- Customer Profiles
- Invoice History
- Payment Status
- Outstanding Balances

---

##  Smart Notifications

- Email Reminders
- Upcoming Due Dates
- Overdue Invoice Alerts
- Payment Notifications

---

##  OCR Extraction

Extracts:

- Vendor Name
- Invoice Number
- Date
- Currency
- Tax
- Subtotal
- Total Amount
- Payment Method
- Line Items
- Confidence Score

---

##  File Support

- PNG
- JPG
- JPEG
- WEBP
- PDF

---

#  AI Workflow

```text
Upload Receipt
        │
        ▼
Cloudinary Storage
        │
        ▼
OCR Processing
        │
        ▼
Gemini AI
        │
        ▼
Structured JSON
        │
        ▼
Database
        │
        ▼
Analytics Dashboard
```

---

#  Tech Stack

## Frontend

- Next.js 15
- React 19
- TypeScript
- Tailwind CSS
- shadcn/ui
- Framer Motion
- Recharts

---

## Backend

- FastAPI
- SQLAlchemy
- Alembic
- Pydantic

---

## Database

- PostgreSQL
- Supabase

---

## AI

- Google Gemini
- PaddleOCR / Google Vision API

---

## Cloud

- Cloudinary

---

## Background Jobs

- Celery
- Redis

---

## Authentication

- JWT Authentication

---

#  Project Structure

```
FinSight-AI/
│
├── frontend/
│   ├── app/
│   ├── components/
│   ├── hooks/
│   ├── services/
│   └── types/
│
├── backend/
│   ├── api/
│   ├── ai/
│   ├── auth/
│   ├── models/
│   ├── ocr/
│   ├── workers/
│   └── utils/
│
├── docs/
│
└── README.md
```

---

#  Core Modules

- Authentication
- Dashboard
- Invoice Management
- Receipt Scanner
- OCR Engine
- AI Financial Assistant
- Expense Analytics
- Vendors
- Customers
- Notifications
- Settings

---

#  OCR Output Example

```json
{
  "vendor": "ABC Traders",
  "invoice_number": "INV-1023",
  "date": "2026-08-01",
  "currency": "INR",
  "subtotal": 4200,
  "tax": 756,
  "total": 4956,
  "category": "Office Supplies",
  "items": [
    {
      "name": "Printer Paper",
      "quantity": 5,
      "unit_price": 300,
      "total": 1500
    }
  ]
}
```

---

#  Roadmap

- [x] Authentication
- [x] Invoice Upload
- [x] OCR Extraction
- [x] AI Data Structuring
- [x] Expense Dashboard
- [ ] AI Expense Prediction
- [ ] Duplicate Invoice Detection
- [ ] Fraud Detection
- [ ] WhatsApp Notifications
- [ ] Mobile Application
- [ ] Multi-language OCR
- [ ] Multi-business Workspace

---

#  Future Enhancements

- AI Expense Forecasting
- Financial Health Score
- GST Reporting
- Invoice PDF Generator
- Inventory Integration
- Voice AI Assistant
- Multi-Currency Support
- Bank Statement Parsing
- Accounting Software Integration
- AI Budget Planner

---

#  Security

- JWT Authentication
- Secure File Uploads
- Input Validation
- SQL Injection Protection
- Role-Based Access Control
- Encrypted Credentials

---

#  Deployment

| Service | Platform |
|----------|----------|
| Frontend | Vercel |
| Backend | Render |
| Database | Supabase PostgreSQL |
| Storage | Cloudinary |
| Cache | Redis |
| AI | Google Gemini |

---

#  Contributing

Contributions, suggestions, and feature requests are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

#  License

## 📄 License

This project is licensed under the **MIT License** see the [LICENSE](LICENSE) file for details.

---

##  Support

If you found this project helpful, consider giving it a ⭐ on GitHub!

Built with ❤️ to simplify financial management through AI.
