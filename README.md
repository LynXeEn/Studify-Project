# 📚 Studify

Studify е мобилна Flutter апликација наменета за студенти, која им овозможува да зачувуваат и управуваат со важни локации поврзани со нивните академски активности. Апликацијата користи Google Firebase за автентикација и чување на податоци, и нуди интерактивна мапа за подобро визуелно искуство.

## 🚀 Карактеристики

- 📍 Зачувување на локации со име или белешка
- 🗺️ Интерактивна OpenStreetMap мапа (преку `flutter_map`)
- 🔁 Релно време синхронизација со Cloud Firestore
- 💬 Автентикација на корисници со Firebase Auth (најава/регистрација)
- ➡️ Автоматска навигација до избрана локација
- ✅ Поддршка за `flutter_location` за тековна локација на уредот
- 🔥 Чист, интуитивен и современ UI

## 📦 Технологии и пакети

| Технологија       | Верзија / Пакет            |
|-------------------|----------------------------|
| Flutter           | 3.x+                        |
| firebase_core     | ^2.x                        |
| cloud_firestore   | ^4.x                        |
| firebase_auth     | ^4.x                        |
| flutter_map       | ^6.x                        |
| latlong2          | ^0.9.x                      |
| location          | ^5.x                        |

## 📸 Снимки од апликацијата

<img src="screenshots/map.png" width="250" />
<img src="screenshots/save_location.png" width="250" />
<img src="screenshots/location_list.png" width="250" />

## 🛠️ Како да ја покренеш локално

1. Клонирај го репозиториумот:

```bash
git clone https://github.com/yourusername/studify.git
cd studify
