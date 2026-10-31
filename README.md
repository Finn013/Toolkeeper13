<p align="center">
  <img src="assets/icon.png" width="128" alt="Toolkeeper 13">
</p>

<h1 align="center">Toolkeeper 13</h1>

<p align="center">
  Учёт выдачи и возврата инструмента в одном HTML-файле.<br>
  Tool check-out and return tracking in a single HTML file.
</p>

<p align="center">
  <a href="https://github.com/Finn013/Toolkeeper13/releases/latest">Скачать / Download</a> ·
  <a href="https://finn013.github.io/Toolkeeper13/">Открыть онлайн / Open online</a>
</p>

---

## 🇷🇺 О приложении

Toolkeeper 13 — простой журнал инструмента для мастерской, склада, бригады или гаража. Видно, что лежит на месте, что выдано и кому, а что в ремонте. Работает без интернета и без регистрации.

### Возможности
- **Три состояния:** «В наличии», «Выдано», «На ремонте» — со счётчиками сверху.
- **Выдача и возврат** одной позиции или сразу нескольких: кому выдан и дата.
- **Разделы и группы** с цветами, перетаскивание инструмента, групп и разделов.
- Поиск, сортировка по названию, дате и получателю.
- **QR-код лота** для выданного набора: сохранить картинкой или скопировать текстом.
- **Хранение в файле** `data.json`, который вы держите у себя, плюс черновик на случай случайного закрытия.
- **Облако (по желанию):** база шифруется AES-256 и хранится в вашем приватном репозитории GitHub. Репозиторий, токен и ключ вводятся в настройках ⚙️ и остаются только на устройстве.

## Скачать

| Платформа | Файл | Статус |
|---|---|---|
| Любое устройство с браузером | `Toolkeeper13.html` | ✅ Доступно |
| Android 7+ | `Toolkeeper13.apk` | ✅ Доступно |
| Windows 10/11 — установщик | `Toolkeeper13-Setup.exe` | ✅ Доступно |
| Windows 10/11 — переносная | `Toolkeeper13-Portable.exe` | ✅ Доступно |
| iPhone, iPad, Mac | [finn013.github.io/Toolkeeper13](https://finn013.github.io/Toolkeeper13/) | ✅ Доступно |

**Android:** при установке разрешите установку из неизвестных источников. Файлы сохраняются в «Загрузки/Toolkeeper13», `data.json` перезаписывается.
**Windows:** сборки не подписаны — если SmartScreen предупредит, нажмите «Подробнее» → «Выполнить в любом случае».
**iPhone/iPad:** откройте ссылку в Safari → «Поделиться» → «На экран Домой». **Mac:** Safari → «Файл» → «Добавить в Dock».

### Облако GitHub за 3 шага
1. Создайте **приватный** репозиторий для данных, например `tools-data`.
2. Создайте fine-grained токен только для этого репозитория с правом **Contents: Read and write**.
3. В приложении нажмите ⚙️, введите `логин/репозиторий` и токен, нажмите «Новый ключ» и **сохраните ключ** — он нужен на каждом устройстве, без него данные не расшифровать.

---

## 🇬🇧 About

Toolkeeper 13 is a simple tool log for a workshop, warehouse, crew or garage: what's in stock, what's checked out and to whom, and what's in repair. Works offline, no sign-up.

### Features
- **Three states:** In stock, Checked out, In repair — with counters.
- **Check-out and return** of one item or many at once: recipient and date.
- **Sections and groups** with colours; drag and drop items, groups and sections.
- Search; sort by name, date and recipient.
- **Lot QR code** for a checked-out set: save as an image or copy as text.
- **File storage** in `data.json` that you keep, plus a draft backup if the app closes unexpectedly.
- **Optional cloud:** the database is AES-256 encrypted and stored in your private GitHub repository. Repo, token and key are entered in ⚙️ settings and stay on the device.

## Download

| Platform | File |
|---|---|
| Any device with a browser | `Toolkeeper13.html` |
| Android 7+ | `Toolkeeper13.apk` |
| Windows 10/11 installer | `Toolkeeper13-Setup.exe` |
| Windows 10/11 portable | `Toolkeeper13-Portable.exe` |
| iPhone, iPad, Mac | [finn013.github.io/Toolkeeper13](https://finn013.github.io/Toolkeeper13/) |

Windows builds are unsigned; if SmartScreen warns, click “More info” → “Run anyway”.

### GitHub cloud in 3 steps
1. Create a **private** repository for data, e.g. `tools-data`.
2. Create a fine-grained token for that repository only with **Contents: Read and write**.
3. In the app tap ⚙️, enter `owner/repo` and the token, tap “New key” and **keep the key safe** — every device needs it to decrypt the data.

## Лицензия / License
MIT © Finn013
