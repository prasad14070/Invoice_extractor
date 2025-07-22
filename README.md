
<center>
<img src="https://readme-typing-svg.herokuapp.com?color=4CBB17&size=40&width=1000&height=80&lines=Welcome+to+Smart+Invoice+Parser+📄" />
</center>

# 💼 Smart Invoice Parser

Smart Invoice Parser is an AI-powered system designed to automatically process scanned invoices (PDFs or images) and extract structured expense data such as invoice number, date, vendor name, line items, and total amount. Built using modern OCR, NLP, and deep learning techniques — it helps automate and streamline finance workflows.

---

## ✅ Key Features

- 📥 **Invoice Ingestion**  
  Supports PDF, JPG, and PNG formats. Converts PDFs to images using `pdf2image`.

- 🔍 **OCR & Text Extraction**  
  Leverages Tesseract or Google Vision to extract raw text from invoice images.

- 🧠 **Entity Extraction**  
  Extracts key fields using Regex, NLP (spaCy, Transformers), and optionally LayoutLM/Donut.

- 🧾 **Structured Output**  
  Outputs clean JSON, with options to export as CSV/Excel.

- ✨ **Bonus Features**
  - Multiple invoice layout support
  - UI for invoice upload & preview
  - Confidence scores
  - Export to DB or financial tools

---

## 📋 Required Extracted Fields

- Invoice Number
- Vendor Name
- Invoice Date
- Total Amount
- Tax Amount (GST/VAT)
- Line Items (Description + Amount)

---

## 🧰 Tech Stack

| Component      | Tools/Libraries |
|----------------|-----------------|
| OCR            | Tesseract, Google Vision, EasyOCR |
| NLP            | spaCy, HuggingFace Transformers |
| Layout Models  | LayoutLMv3, Donut, PaddleOCR |
| PDF/Image      | pdf2image, OpenCV, Pillow |
| Backend        | Python (FastAPI or Flask) |
| Optional Frontend | React, Streamlit, Tkinter GUI |

---

## 🚀 Getting Started

### 🧪 Setup

```bash
git clone https://github.com/yourusername/smart-invoice-parser.git
cd smart-invoice-parser
pip install -r requirements.txt
```

### ⚙️ Run Trainer

```bash
python trainer.py
```

### 📤 Run Extractor

```bash
python extractor.py
```

---

## 🌐 UI (Optional)

Build a web interface (e.g. with React or Streamlit) for:

- Uploading invoice files  
- Displaying parsed results with highlights  
- Exporting results  

---

## 🧪 Datasets & Resources

- [SROIE Dataset (Kaggle)](https://www.kaggle.com/datasets/urbikn/sroie-datasetv2)
- [GitHub: Invoice PDFs](https://github.com/topics/invoice-pdf)

Upload your own 5–10 sample invoices for better testing and model tuning.

---

## 🧮 Evaluation Criteria

| Metric | Weight |
|--------|--------|
| 📈 Accuracy of extracted data | 40% |
| 🧩 Layout flexibility         | 20% |
| 🔧 Code quality & structure   | 15% |
| 🤖 Use of AI tools            | 15% |
| ✨ Bonus features & UI        | 10% |

---

## 📦 Folder Structure

```bash
smart-invoice-parser/
│
├── data/                 # Raw and preprocessed invoice data
├── models/               # Trained model checkpoints
├── processed_data/       # Structured labeled data
├── src/                  # Extraction logic and utilities
├── trainer.py            # Model training interface
├── extractor.py          # Extraction interface
├── requirements.txt
└── README.md
```

---

## 🤝 Contributing

Contributions are welcome!

```bash
git checkout -b feature/YourFeature
git commit -m "Add new feature"
git push origin feature/YourFeature
```

---

## 📜 License

MIT License

---

## 👤 Author

**Prasad Bhujbal**  
📧 Email: [your.email@example.com]  
🔗 [LinkedIn](https://www.linkedin.com/in/prasad-bhujbal)  
🐙 [GitHub](https://github.com/yourusername)

---

<center> <strong>📄 Smart Invoice Parser – Automate Invoice Intelligence with AI!</strong> </center>
