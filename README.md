# 👋 Привет, я Степан Пиво (aka demon64k)

> *"Код — это современное заклинание, которое заставляет фантома из параллельной вселенной стать осязаемой реальностью."*

Я разработчик-прагматик, специализирующийся на трех направлениях: **браузерные расширения для борьбы с рекламой**, **независимый аудит безопасности** мобильных приложений и **неофициальные игровые патчи**.

Моя философия: у каждой идеи есть свое альтер-эго. Моя задача — помочь ему материализоваться в виде инструментов, которые реально решают проблемы пользователей: убирают надоедливую рекламу, вскрывают ложь о приватности или улучшают игровой опыт.

---

### 📌 Избранные проекты

Здесь собраны мои ключевые работы — каждая из них отвечает на конкретный вызов:

#### 🛡 [Яндекс AdBlock Extension](https://github.com/demon64k/adblock-yandex-extension)
> *Pre-blocking рекламы в Яндекс Играх и Видео на сетевом уровне*

Продвинутое браузерное расширение (Manifest V3) для Chromium-браузеров, которое **пред-блокирует** рекламу до её показа. Использует `declarativeNetRequest`, перехват `fetch/XHR` в MAIN world, `MutationObserver` для DOM-очистки, конвертер ABP → DNR и поддержку внешних фильтров (RU AdList, EasyList). Блокирует rewarded-рекламу, interstitial, preroll и midroll в видео.

#### 🔒 [Аудит безопасности: Приложение «ИТД»](https://github.com/demon64k/Analiz-bezopasnosti-ITD-v1.0.13)
> *Независимый технический расследовательский отчёт о приватности*

Глубокий анализ APK мобильного приложения «ИТД» (com.itd.app). Выявил **ложную декларацию** в Google Play (разработчик утверждал, что данные не передаются третьим сторонам, но внутри — SDK ironSource, передающий данные 20+ рекламным сетям). Оценка CVSS v3.1: **7.2 (High)**, итоговый рейтинг безопасности: 🔴 2.5/10. Включает инструкцию по подаче жалобы в Google Play.

#### 🍪 [GarticPhone AdBlocker Ultra](https://github.com/demon64k/GarticPhoneAdBlocker)
> *Бескомпромиссная блокировка 250+ рекламных сетей в игре*

Расширение для чистого геймплея в GarticPhone. Поддерживает Chrome, Edge, Яндекс, Firefox, Opera (MV2 и MV3). Трехуровневая защита: сетевая блокировка (`cancel: true`), CSS-скрытие фреймов и JS-очистка через `MutationObserver`. Полная приватность — работает только на доменах Gartic, без телеметрии.

#### 📼 [Backrooms Level 94: Subtitles Mod](https://github.com/demon64k/Backrooms-Level94-Subtitles)
> *Фанатский патч для улучшения нарратива*

Неофициальный мод для «Побег из Закулисья: Уровень 94» (Davilkus Games). Добавляет имя героини Кэмми в субтитры, что помогает лучше понять сюжет. Замена файлов в `StreamingAssets/Lang/` — просто, элегантно, работает.

---

### 🧰 Мой стек технологий

**Браузерные расширения:**
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Manifest V3](https://img.shields.io/badge/-Manifest%20V3-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![declarativeNetRequest](https://img.shields.io/badge/-DNR-FF6B00?style=flat-square)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Аудит безопасности:**
![Android APK](https://img.shields.io/badge/-Android%20APK-3DDC84?style=flat-square&logo=android&logoColor=white)
![CVSS v3.1](https://img.shields.io/badge/-CVSS%20v3.1-DC143C?style=flat-square)
![Reverse Engineering](https://img.shields.io/badge/-Reverse%20Engineering-9C27B0?style=flat-square)
![Network Analysis](https://img.shields.io/badge/-Network%20Analysis-00BCD4?style=flat-square)

**Автоматизация и инструменты:**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Telegram Bot API](https://img.shields.io/badge/-Telegram%20API-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Low-Code/No-Code](https://img.shields.io/badge/-Low--Code-8A2BE2?style=flat-square)

---

### 💡 Мой подход к разработке

1. **Эффективность превыше всего**: Если задачу можно решить без написания тысяч строк кода, я найду этот путь. Если нет — напишу полноценный, масштабируемый код.
2. **Пользователь в центре**: Мои расширения не собирают телеметрию, не замедляют браузер и работают именно там, где нужны.
3. **Техническая глубина**: От анализа APK и оценки CVSS v3.1 до перехвата `fetch` в MAIN world — я не делаю поверхностных решений.
4. **Творческий прагматизм**: Философские концепции (вроде цифровых фантомов и альтер-эго) вдохновляют меня на нестандартные архитектурные решения.

---

### 📫 Как со мной связаться

- 💬 **Telegram**: [@Dimoska_studio](https://t.me/Dimoska_studio)
- 📧 **Email**: [твой_email@example.com](mailto:твой_email@example.com) *(замени на свой)*
- 🌐 **GitHub**: [github.com/demon64k](https://github.com/demon64k)
