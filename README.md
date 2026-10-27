# Bar Swipe

Минималистичный LSPosed-модуль, позволяющий скрывать статус-бар свайпом вверх и возвращать его свайпом вниз.

<p align="left">
  <img src="https://img.shields.io/badge/Android-13%E2%80%9316-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android 13-16" />
  <img src="https://img.shields.io/badge/API-LibXposed%20101-blue?style=flat-square" alt="LibXposed 101" />
  <img src="https://img.shields.io/badge/Size-~17%20KB-orange?style=flat-square" alt="APK Size" />
</p>

---

### ✨ Возможности
* 👆 **Свайп вверх по строке состояния:** плавно скрывает статус-бар с тактильным откликом.
* 👇 **Свайп вниз по верхней зоне:** возвращает статус-бар на место.
* ⚡ **Нулевая нагрузка:** хук срабатывает исключительно для `com.android.systemui` при обработке тачей корня окна, не трогает сторонние приложения.
* 🛡️ **Защитный режим (Protective Mode):** при любых непредвиденных ошибках SystemUI не падает, событие просто передается дальше.
* 🎨 **Material You:** адаптивная иконка с поддержкой динамических цветов Monet и монохромного слоя (Themed Icons) для Android 13+.
* 🪶 **Ультралегкий:** размер готового APK составляет всего ~17 КБ.

---

### 📋 Требования
* Android 13+ (протестировано на Android 15 и 16 / OxygenOS / ColorOS / AOSP)
* LSPosed с поддержкой современного LibXposed API 101+

---

### 👨‍💻 Разработчик
* **Автор:** [Rooni](https://rooni.dev)
* **Telegram:** [@YouRooni](https://t.me/YouRooni)
* **Канал:** [@RnPlugins](https://t.me/RnPlugins)
