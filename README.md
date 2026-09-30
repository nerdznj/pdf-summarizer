<p align="center">
  <img src=".github/assets/8b596a0d-6b0e-4d60-8a11-b8768e20d837.png" alt="pdf-summarizer logo" width="200"/>
</p>

<h1 align="center">🧠 PDF Summarizer | خلاصه‌ساز PDF فارسی</h1>

<p align="center">
تبدیل فایل‌های PDF فارسی به متن و تولید خلاصه هوشمندانه با کمک OCR و GPT-3.5
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue" />
  <img src="https://img.shields.io/badge/OCR-Tesseract-green" />
  <img src="https://img.shields.io/badge/GPT-3.5-critical" />
  <img src="https://img.shields.io/badge/Persian_NLP-Supported-orange" />
</p>

---

## 📽️ دمو تصویری

<p align="center">
  <img src="assets/demo.gif" alt="PDF Summarizer demo" width="600"/>
</p>

---

## 📦 درباره پروژه

ابزار `pdf-summarizer` یک اپلیکیشن Python است که برای تبدیل فایل‌های PDF فارسی به متن، و سپس خلاصه‌سازی محتوا طراحی شده است. این ابزار از ترکیب OCR فارسی با Tesseract و مدل GPT-3.5 برای تولید خلاصه‌های دقیق و قابل درک استفاده می‌کند.

---

```
📂 ساختار پروژه
📁 pdf-summarizer/
├── main.py
├── requirements.txt
├── README.md
├── .gitignore
└── .github/
└── assets/
└── 8b596a0d-6b0e-4d60-8a11-b8768e20d837.png
```


🤝 مشارکت در پروژه

اگر علاقه‌مند به بهبود این پروژه هستید، خوشحال می‌شویم که مشارکت کنید! لطفاً یک Fork از پروژه بزنید و Pull Request ارسال کنید.

📄 مجوز

این پروژه تحت مجوز MIT منتشر شده است. برای اطلاعات بیشتر، فایل LICENSE را مشاهده کنید.

🧩 تکنولوژی‌ها و کتابخانه‌ها

| تکنولوژی | کاربرد |
|----------|--------|
| Python 3.10 | زبان اصلی پروژه |
| Tesseract OCR | استخراج متن از PDF به صورت تصویری |
| OpenAI API | خلاصه‌سازی متن |
| pdf2image | تبدیل صفحات PDF به تصویر |
| pytesseract | رابط Python برای Tesseract |
| reportlab | ساخت PDF خروجی (در آینده) |

---

## ⚙️ نصب و راه‌اندازی

> پیش‌نیاز: نصب [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) و [Poppler](https://github.com/oschwartz10612/poppler-windows/releases)

آدرس مخزن را از گزینه **Code** در صفحه همین پروژه کپی کرده و جایگزین `<repository-url>` کنید.

```bash
git clone <repository-url>
cd pdf-summarizer
pip install -r requirements.txt
```

