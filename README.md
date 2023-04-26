# Django Online Shop
![Screenshot 2022-01-09 at 17-04-55 Django Online Shop](https://user-images.githubusercontent.com/71011395/148684469-79bfdb07-efa0-4dde-ad76-1f3277f833e6.png)
django bilan yozilgan haqiqatan ham oddiy, ammo foydalanish mumkin bo'lgan onlayn-do'kon. ushbu ilova mahsulot va buyurtmalarni boshqarish uchun maxsus asboblar panelini taqdim etadi,
foydalanuvchilar mahsulotni yoqtirishi va uni savatga qo'shishi mumkin, to'lov va buyurtma qo'llab-quvvatlanadi, ammo to'lov soxta to'lov bilan amalga oshiriladi. 

[Ko‘rib chiqish](#app-preview)

## Xususiyatlari:
Ushbu ilovada ikki turdagi foydalanuvchi mavjud: foydalanuvchi va menejer.

available to the user:
- savat
- shaxsiy ma'lumotlarni tahrirlash
- buyurtmalar
- sevimlilar
- elektron pochta orqali parolni tiklash

menejer bu barcha xususiyatlarga kirishi mumkin
ushbu manzildagi maxsus dashboard paneli: http://127.0.0.1:8000/accounts/login/manager
email: manager@example.com
parol: managerpass1234 

- mahsulot qo'shish
- mahsulotni tahrirlash va o'chirish
- yangi toifa qo'shing
- barcha buyurtmalar va buyurtma buyumlariga kirish


## Ushbu ilovada foydalanilgan:
- python3
- django 
- bootstrap
- sqlite3 database


## Uni qanday ishga tushirish kerak:
1. loyihani clone qilish yoki yuklab olish.
2. katalogni ``` online-shop-django`` ga o`zgartiring
3. make sure you have ``python3``, ```pip``` and ```virtualenv``` installed in your machine.
4. create virtualenv: ```python3 -m venv venv```
5. active virtualenv: Mac & Linux os: ```source venv/bin/activate```, Windows os: ```venv\scripts\activate```
6. install app requirements: ```pip install -r requirements.txt```
7. databse migrate: ```python manage.py migrate```
8. run the server: ```python manage.py runserver```
9. you should be able to open this address now: http://127.0.0.1:8000/

## Ilovani oldindan ko'rish
![Peek 2022-01-09 19-15](https://user-images.githubusercontent.com/71011395/148689722-6ceacc8f-81b7-48e0-a258-9d4e543d1e7c.gif)
