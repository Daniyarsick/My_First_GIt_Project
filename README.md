# My First Git Project

Первый учебный Android-проект на Kotlin. Репозиторий демонстрирует базовую структуру Android-приложения, подключение Gradle Kotlin DSL и минимальный экран `Hello World`.

## Возможности

- Стартовый экран на `ConstraintLayout`.
- Поддержка edge-to-edge режима.
- Обработка системных отступов через `WindowInsetsCompat`.
- Минимальная Activity на Kotlin.

## Технологии

- Kotlin
- Android SDK
- AndroidX AppCompat
- AndroidX Activity
- ConstraintLayout
- Material Components
- Gradle Kotlin DSL

## Структура проекта

```text
app/src/main
├── AndroidManifest.xml
├── java/com/example/myfirstgitproject
│   └── MainActivity.kt
└── res/layout
    └── activity_main.xml
```

`MainActivity.kt` подключает layout и настраивает корректные отступы для системных панелей. `activity_main.xml` содержит простой экран с текстом `Hello World`.

## Сборка

Требования:

- Android Studio или Android SDK
- JDK 17
- Gradle Wrapper из репозитория

Команда сборки:

```bash
./gradlew assembleDebug
```

На Windows:

```powershell
.\gradlew.bat assembleDebug
```

APK после сборки:

```text
app/build/outputs/apk/debug/app-debug.apk
```

## Что можно улучшить

- Добавить несколько экранов и навигацию.
- Перевести учебный экран на Material-компоненты.
- Добавить ViewModel для хранения состояния.
- Добавить README-скриншоты после доработки интерфейса.

## Статус

Минимальный учебный Android-проект. Его ценность в портфолио — показать стартовую практику с Kotlin, Android Studio, Gradle и базовой структурой Android-приложения.
