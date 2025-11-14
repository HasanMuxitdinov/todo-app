# Django Todo App

Backend loyiha - Foydalanuvchilar uchun vazifalarni boshqarish tizimi

## 📋 Loyiha haqida

Bu Django va Django REST Framework asosida qurilgan To-do List ilovasi bo'lib, foydalanuvchilarga:
- Shaxsiy vazifalar ro'yxatini yaratish
- Vazifalarni tahrirlash va o'chirish
- Vazifalarni "bajarilgan" deb belgilash
- Vazifalarni filtrlash imkoniyatlarini taqdim etadi

## ✨ Asosiy funksiyalar

- ✅ Ro'yxatdan o'tish va login - JWT autentifikatsiya
- ✅ CRUD operatsiyalari - Vazifalarni yaratish, ko'rish, yangilash, o'chirish
- ✅ Holatni o'zgartirish - Vazifalarni "bajarilgan"/"bajarilmagan" qilish
- ✅ Filtrlash - Foydalanuvchiga tegishli vazifalarni filtrlash
- ✅ REST API - Barcha amallarni API orqali boshqarish

## 🛠 Texnologiyalar

- Backend: Django 4.2.7
- API: Django REST Framework 3.14.0
- Autentifikatsiya: JWT (JSON Web Tokens)
- Ma'lumotlar bazasi: SQLite
- CORS: django-cors-headers

## 🚀 O'rnatish va ishga tushirish

```bash
# 1. Loyihani klonlash
git clone https://github.com/HasanMaxifuínov/todo-project.git
cd todo-project

# 2. Virtual muhit yaratish
python -m venv venv
# Windows: venv\Scripts\activate
# Mac/Linux: source venv/bin/activate

# 3. Paketlarni o'rnatish
pip install -r requirements.txt

# 4. Ma'lumotlar bazasi
python manage.py makemigrations
python manage.py migrate

# 5. Serverni ishga tushirish
python manage.py runserver# todo-app
Django REST Framework Todo App with JWT Authentication
