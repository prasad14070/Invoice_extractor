<center>
<img src="https://readme-typing-svg.herokuapp.com?color=4CBB17&size=40&width=1000&height=80&lines=Welcome+to+Smart+Invoice+Parser+📄" />
</center>

# 💼 Smart Invoice Parser

Smart Invoice Parser is an AI-powered system designed to automatically process scanned invoices (PDFs or images) and extract structured expense data such as invoice number, date, vendor name, line items, and total amount. Built using modern OCR, NLP, and deep learning techniques — it helps automate and streamline finance workflows.

---

## 🎯 Objective

> Build an AI system that automatically reads scanned invoices (PDFs/images) and extracts structured expense information in JSON format.

---

## 🖼️ Input Examples

- 📄 PDF or image-based invoices (JPG, PNG)
- 📃 Invoices with varying layouts (tables, plain text, etc.)
  
---

## 🧾 Sample Output (JSON)

```json
{
  "invoice_number": "INV-2023-1983",
  "vendor_name": "ABC Technologies Pvt Ltd",
  "invoice_date": "2023-06-15",
  "total_amount": 18750.50,
  "tax_amount": 1250.50,
  "line_items": [
    {
      "description": "Cloud Hosting (May 2023)",
      "amount": 15000
    },
    {
      "description": "Support Fee",
      "amount": 2500
    }
  ]
}
