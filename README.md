<h1 align="center">🛍️ Django Shop</h1>

<p align="center">
  <strong>سیستم فروشگاه اینترنتی کامل با جنگو، زرین‌پال، سبد خرید، مدیریت سفارش و کوپن تخفیف</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue" alt="Python">
  <img src="https://img.shields.io/badge/Django-4.2%2B-darkgreen" alt="Django">
  <img src="https://img.shields.io/badge/Zarinpal-Payment-orange" alt="Zarinpal">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/Status-Production%20Ready-green" alt="Status">
</p>

---

## 📖 فهرست مطالب

- [درباره پروژه](#-درباره-پروژه)
- [امکانات](#-امکانات)
- [نصب و راه‌اندازی](#-نصب-و-راهاندازی)
- [بانک اطلاعاتی](#-بانک-اطلاعاتی)
- [قالب فروشگاه](#-قالب-فروشگاه)
- [مشارکت](#-مشارکت)
- [مجوز](#-مجوز)

---

## 📌 درباره پروژه

این پروژه یک **سیستم فروشگاه اینترنتی کامل و آماده استقرار** است که شامل:

- مدیریت محصولات و دسته‌بندی‌ها
- سبد خرید حرفه‌ای
- اتصال به درگاه پرداخت زرین‌پال
- سیستم کوپن‌های تخفیف
- مدیریت سفارشات و فاکتورها

این پروژه برای استفاده در **پروژه‌های واقعی** طراحی شده و قابلیت سفارشی‌سازی بالایی دارد.

---

## ✨ امکانات

- ✅ ثبت‌نام و ورود کاربران
- ✅ نمایش محصولات با دسته‌بندی
- ✅ سبد خرید (Cart)
- ✅ ثبت سفارش
- ✅ اتصال به درگاه **زرین‌پال**
- ✅ مدیریت کوپن‌های تخفیف
- ✅ پنل مدیریت کامل برای محصولات و سفارشات
- ✅ خروجی فاکتور
- ✅ طراحی ریسپانسیو

---

## 🚀 نصب و راه‌اندازی

### پیش‌نیازها

- Python 3.10+
- pip

### مراحل نصب

```bash
git clone https://github.com/Taranemp/Django-Shop-1.git
cd Django-Shop-1
python -m venv venv
source venv/bin/activate  # یا venv\Scripts\activate در ویندوز
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver