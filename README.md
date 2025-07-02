
 README 

 Sentiment Analysis with Logistic Regression (TF-IDF)

This is a **simple yet effective sentiment analysis project** written in Python using **scikit-learn** and **TF-IDF vectorization**. It classifies Persian (Farsi) text as either **positive** or **negative** based on predefined training samples.

---
 Features

* Text preprocessing with `TfidfVectorizer`
* Classification with `LogisticRegression`
* Real-time sentiment prediction with a simple function
* Works with Persian (Farsi) text out of the box

---

 Requirements

```bash
pip install pandas scikit-learn
```

---

 How It Works

1. Creates a small labeled dataset of Persian sentences with `Label` (0: negative, 1: positive).
2. Uses `TfidfVectorizer` to convert text into numerical features.
3. Trains a logistic regression model on 80% of the data.
4. Defines a function `predict_sentiment` that:

   * Takes a sentence as input.
   * Predicts whether it's **positive** or **negative**.
   * Returns the result in Persian.

---

 File Structure

```
├── sentiment_analysis.py
├── README.md
```

---

 Example Output

```python
print(predict_sentiment("این گوشی عالیه"))         # مثبت
print(predict_sentiment("هوا چه قدر بده"))         # منفی
print(predict_sentiment("این فیلم محشره"))         # مثبت
```

---

 Future Ideas

* Use larger, real-world Persian datasets (e.g. from Digikala or Twitter)
* Train with deep learning models like BERT for Persian (e.g. ParsBERT)
* Add a simple web interface using Flask or Streamlit

---






 تشخیص احساسات متنی با Logistic Regression

در این پروژه‌ی ساده با استفاده از پایتون و کتابخانه‌های `scikit-learn` و `TF-IDF`، جملات فارسی از نظر احساسی به **مثبت** یا **منفی** طبقه‌بندی می‌شوند.

---

 امکانات

* بردار‌سازی متن با `TfidfVectorizer`
* آموزش مدل با `LogisticRegression`
* تابع ساده برای پیش‌بینی احساسات متون جدید
* پشتیبانی از متن فارسی بدون نیاز به پردازش اضافی

---

 پیش‌نیازها

```bash
pip install pandas scikit-learn
```

---

 نحوه عملکرد

1. ایجاد یک دیتاست کوچک شامل جملات فارسی با برچسب (0: منفی، 1: مثبت)
2. تبدیل متن به ویژگی عددی با `TfidfVectorizer`
3. آموزش مدل `Logistic Regression` با ۸۰٪ داده
4. تعریف تابع `predict_sentiment` برای:

   * دریافت جمله ورودی
   * پیش‌بینی احساس آن (مثبت یا منفی)
   * بازگرداندن نتیجه به صورت متنی (مثبت/منفی)
   

- ساختار فایل

```
├── sentiment_analysis.py
├── README.md
```

---

 خروجی نمونه

```python
print(predict_sentiment("این گوشی عالیه"))         # مثبت
print(predict_sentiment("هوا چه قدر بده"))         # منفی
print(predict_sentiment("این فیلم محشره"))         # مثبت
```

---

 ایده‌های توسعه

* استفاده از دیتاست‌های واقعی و بزرگ‌تر (مثلاً توییتر، دیجی‌کالا و غیره)
* استفاده از مدل‌های پیشرفته‌تر مثل BERT (مثلاً ParsBERT)
* ساخت رابط کاربری ساده با Flask یا Streamlit

---

