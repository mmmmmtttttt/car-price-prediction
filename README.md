## 📷 Project Banner
<p align="center">
  <img src="/images/banner.png" alt="Console Smart Bot" width="1000"/>
</p>

# 🚗 Car Price Prediction using Linear Regression

## 📊 Project Overview (English)

This project aims to predict the price of a car based on its technical specifications using **Multiple Linear Regression**. The model was trained on the [Car Price Assignment Dataset], and evaluated using a scatter plot comparing predicted vs. actual prices.

### ✅ Technologies Used:
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn

### 📁 Dataset
- File: `CarPrice_Assignment.csv`
- Features used for training include:
  - `wheelbase`, `carlength`, `carwidth`, `carheight`, `curbweight`
  - `enginesize`, `boreratio`, `stroke`, `compressionratio`, `horsepower`
  - `peakrpm`, `citympg`, `highwaympg`

### 📈 Results
- The model was trained using 80% of the data and tested on 20%
- Model score (R²): displayed in terminal output
- Prediction example: Estimating the price of a car with custom values
- Final visualization: actual vs predicted prices saved as `img.png`

### 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the Jupyter Notebook in `notebooks/linear_regression_car_price.ipynb`
3. Ensure dataset is in `data/` and output image saved in `images/`

---

## 🚗 مشروع التنبؤ بسعر السيارة (عربي)

### 🎯 وصف المشروع
يهدف هذا المشروع إلى التنبؤ بسعر السيارة بناءً على المواصفات الفنية باستخدام **الانحدار الخطي المتعدد**. تم تدريب النموذج على بيانات حقيقية وتقييمه عبر رسم السعر الحقيقي مقابل السعر المتوقع.

### ✅ الأدوات المستخدمة:
- لغة Python
- مكتبات: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

### 📁 البيانات
- الملف: `CarPrice_Assignment.csv`
- الأعمدة المستخدمة في التدريب:
  - `wheelbase`, `carlength`, `carwidth`, `carheight`, `curbweight`
  - `enginesize`, `boreratio`, `stroke`, `compressionratio`, `horsepower`
  - `peakrpm`, `citympg`, `highwaympg`

### 📊 النتائج
- تم تقسيم البيانات: 80% للتدريب و 20% للاختبار
- عرض دقة النموذج في الإخراج
- تنفيذ تنبؤ على بيانات سيارة جديدة
- تم حفظ الرسم النهائي في `images/img.png`

### 🚀 كيفية التشغيل
1. تثبيت المكتبات:
   ```bash
   pip install -r requirements.txt
   ```
2. تشغيل ملف Jupyter الموجود في `notebooks/linear_regression_car_price.ipynb`
3. التأكد من وجود البيانات في `data/` وملف الصورة في `images/`

---

**📌 هذا المشروع جزء من تدريبات الذكاء الاصطناعي باستخدام Python.**
