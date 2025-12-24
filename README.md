# StudentPortal (Student Mini-Portal)

Мобільний додаток на Kotlin (Jetpack Compose) для студентського міні-порталу:
- дедлайни / завдання
- профіль студента (Student ID)
- health & focus (звички/поради)

## Функціонал
- Навігація між екранами: Home / Tasks / Profile / Health
- Авторизація та реєстрація через Firebase Auth
- Зберігання профілю студента у Firebase Firestore (колекція `students`)
- Зберігання завдань у Firebase Firestore (колекція `tasks/{uid}/items`)
- Додавання / редагування / видалення завдань, чекбокс "done"

## Встановлення (запуск локально)
1. Клонувати репозиторій:
   ```bash
   git clone https://github.com/duyndiik/MyStudentApp.git
