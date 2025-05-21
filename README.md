# smart-invoice-analyzer

A smart AI-powered tool that extracts, analyzes, and summarizes invoice details using **OCR**, **Named Entity Recognition (NER)**, and **Text Summarization**. Perfect for automating business processes and financial document analysis.


## 🚀 Features

- 📤 **Upload Invoice Image**
- 🔍 **OCR**: Extract text from scanned or photographed invoices
- 🧠 **NER**: Identify key fields like:
  - Vendor Name
  - Total Amount
  - Due Date
  - Product Names
- 📃 **Summarization**: Generate a human-readable summary from invoice content

---

## 🛠️ Tech Stack

| Tool         | Purpose                         |
|--------------|----------------------------------|
| `pytesseract`| Optical Character Recognition (OCR) |
| `spaCy`      | Named Entity Recognition (NER)     |
| `transformers` (BART) | Text Summarization            |
| `Pillow`     | Image processing                   |
| `Google Colab` | Development/Testing Environment     |

---

## 📸 Example Output

**Uploaded Invoice:** `invoice-analyzer.jpg`

