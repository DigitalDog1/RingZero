# 🎉 RingZero v1.0 - Полный редизайн

> **Это ПОЛНАЯ архитектурная переработка с нуля.** Каждый компонент был переписан с самого начала для повышения производительности, надежности и удобства использования.

---

## 🇷🇺 v1.0

### ✨ Что изменилось?

Это не просто обновление — это **полное переложение всей архитектуры**. RingZero теперь:
- Лучше понимает вас на вашем языке
- Быстрее выполняет команды
- Надежнее работает с файлами и системой
- Красивее выглядит и приятнее использовать

---

## 🎨 Новый Интерфейс

#### Переработанный UI с современным дизайном

```
💻 Примеры команд:
  • "Создай на рабочем столе файл notes.txt и запиши рецепт"
  • "Запусти игру [Название]"
  • "Найди последние новости про ИИ"
```

---

## 🤖 Новая Архитектура Agent'а

#### Улучшенное распознавание инструментов
- **7 различных парсеров** вместо одного (лучше понимает ваши команды)
- **Максимум 8 итераций** за один запрос (может делать несколько операций подряд)
- **Правильный контекст** в истории диалога

#### Ask Mode — Режим Подтверждения ✅
Включите "Ask Mode" в настройках, и ИИ будет просить разрешение перед критичными операциями:

```
👤 Вы: "Удали файл data.txt"
🤖 RingZero:
   ┌───────────────────────────────────┐
   │                                   │
   │ Вы просите удалить файл: data.txt │
   │ [Разрешить] [Отклонить]           │
   │                                   │
   └───────────────────────────────────┘
```

Особенно полезно для операций типа:
- ❌ Удаление файлов
- 🔌 Выключение ПК
- 📧 Отправка писем
- 💾 Управление дисками

---

## 🛠️ 22 Встроенных Инструмента

### 📂 Работа с Файлами
```
create_file      — Создавать файлы и папки
read_file        — Читать содержимое
edit_file        — Редактировать текст в файле
delete_file      — Удалять файлы
rewrite_file     — Полностью переписать файл
list_directory   — Показать содержимое папки
```

**Пример:** *"Создай на рабочем столе файл notes.txt и запиши туда рецепт шарлотки"*

---

### 💻 Управление Системой
```
run_command         — Запустить команду (cmd, PowerShell)
run_in_new_window   — Открыть новое окно и выполнить команду
close_process       — Закрыть приложение по названию
get_system_info     — Получить инфо о ПК (CPU, RAM, Диски)
```

**Пример:** *"Какой у меня объем оперативной памяти?"* или *"Закрой Telegram"*

---

### 🌐 Сеть & Интернет
```
network_ping    — Проверить доступность сайта
network_scan    — Найти устройства в локальной сети
open_url        — Открыть ссылку в браузере
```

**Пример:** *"Пингани google.com"* или *"Какие устройства подключены к моей WiFi?"*

---

### ⚡ Питание & Управление
```
manage_power    — Выключить, перезагрузить, режим сна
                  (с поддержкой задержки: "через 30 минут")
```

**Пример:** *"Выруби ПК через 30 минут"* или *"Перезагрузись прямо сейчас"*

---

### 📦 Архивы & Бэкапы
```
archive_files    — Zip/Unzip файлы (с паролями!)
backup_directory — Создать бэкап папки (с временной меткой)
```

**Пример:** *"Заархивируй папку 'Documents' паролем 123456"*

---

### 📧 Почта (SMTP)
```
send_email  — Отправить письмо от вашего имени
```

**Пример:** *"Отправь письмо на example@mail.com с темой 'Привет' и текстом 'Как дела?'"*

---

### 🔍 Поиск Файлов
```
find_path     — Найти файл по имени в быстрых папках
find_all_dir  — Поиск ПО ВСЕМ ДИСКАМ (медленнее, но полнее)
```

**Пример:** *"Найди все .mp3 файлы на компьютере"*

---

### ⏰ Утилиты
```
set_timer          — Таймер/Напоминание ("через 15 минут")
execute_python     — Выполнить Python код
schedule_task      — Запланировать задачу на позже
create_presentation — Создать .pptx презентацию
```

**Пример:**
- *"Напомни мне через 15 минут проверить почту"*
- *"Сделай презентацию про космос на 5 слайдов"*
- *"Напиши Python скрипт для парсинга сайта"*

---

### ⚙️ Конфигурация
```
add_saved_directory — Добавить папку в "избранное"
```

---

### Что улучшилось?
- ✅ **Поддержка API провайдеров:** OpenAI, Anthropic, OpenRouter, Groq, VLLM и т.д.
- ✅ **Локальные модели:** Ollama
- ✅ **Безопасность:** Защита от повреждения конфига
- ✅ **Быстрый доступ:** Сохраненные папки и URL'ы

---

## 📝 Как обновиться?

1. Скачайте новый `RingZero.exe` из [Releases](https://github.com/DigitalDog1/RingZero/releases) или на нашем [Сайте](https://ringzero.vercel.app/). Также есть возможность обновиться через само приложение.
2. Замените старый файл на новый
3. Запустите

> ℹ️ Все ваши чаты и настройки будут сохранены.

---

## 🙏 Спасибо!

Спасибо за использование **RingZero**! Ваши отзывы и предложения помогают делать приложение лучше.

📧 Проблемы? → [GitHub Issues](https://github.com/DigitalDog1/RingZero/issues)
⭐ Нравится? → [Поставьте Star](https://github.com/DigitalDog1/RingZero)

---

---

# 🎉 RingZero v1.0 - Complete Redesign

> **This is a COMPLETE architectural redesign from scratch.** Every component has been rewritten from the ground up for better performance, reliability, and user experience.

---

## 🇬🇧 v1.0

### ✨ What's changed?

This isn't just an update—it's a complete redesign of the entire architecture. RingZero now:
- Understands you better in your language
- Executes commands faster
- Works more reliably with files and the system
- Looks better and is more pleasant to use

---

## 🎨 New Interface

#### Redesigned UI with a modern design

```
💻 Example commands:
• "Create a notes.txt file on your desktop and write down a recipe"
• "Launch the game [Name]"
• "Find the latest news about AI"
```

---

## 🤖 New Agent Architecture

#### Improved tool recognition
- **7 different parsers** instead of one (better understands your commands)
- **Maximum of 8 iterations** per request (can perform multiple operations in a row)
- **Correct context** in conversation history

#### Ask Mode — Confirmation Mode ✅
Enable "Ask Mode" in the settings, and the AI ​​will ask for permission before critical operations:

```
👤 You: "Delete the file data.txt"
🤖 RingZero:
┌─────────────────────────────────────────────────┐
│                                                 │
│ You are requesting to delete the file: data.txt │
│ [Allow] [Decline]                               │
│                                                 │
└─────────────────────────────────────────────────┘
```

Especially useful for operations like:
- ❌ Deleting files
- 🔌 Shutting down a PC
- 📧 Sending emails
- 💾 Disk Management

---

## 🛠️ 22 Built-in Tools

### 📂 Working with Files
```
create_file — Create files and folders
read_file — Read contents
edit_file — Edit text in a file
delete_file — Delete files
rewrite_file — Completely rewrite a file
list_directory — Show folder contents
```

**Example:** *"Create a file named notes.txt on your desktop and add the Charlotte recipe there"*

---

### 💻 System Management
```
run_command — Run a command (cmd, PowerShell)
run_in_new_window — Open a new window and run the command
close_process — Close an application by name
get_system_info — Get PC information (CPU, RAM, Disks)
```

**Example:** *"How much RAM do I have?"* or *"Close Telegram"*

---

### 🌐 Network & Internet
```
network_ping — Check website availability
network_scan — Find devices on the local network
open_url — Open a link in Browser
```

**Example:** *"Ping google.com"* or *"Which devices are connected to my WiFi?"*

---

### ⚡ Power & Management
```
manage_power — Shut down, restart, sleep
(with delay support: "in 30 minutes")
```

**Example:** *"Shut down your PC in 30 minutes"* or *"Restart now"*

---

### 📦 Archives & Backups
```
archive_files — Zip/Unzip files (with passwords!)
backup_directory — Create a backup of a folder (with a timestamp)
```

**Example:** *"Zip the 'Documents' folder with the password 123456"*

---

### 📧 Mail (SMTP)
```
send_email — Send an email on your behalf
```

**Example:** *"Send an email to example@mail.com with the subject 'Hello' and the text 'How are you?'"*

---

### 🔍 File Search
```
find_path — Find a file by name in Quick Folders
find_all_dir — Search ALL DRIVES (slower, but more complete)
```

**Example:** *"Find all .mp3 files on your computer"*

---

### ⏰ Utilities
```
set_timer — Timer/Reminder ("in 15 minutes")
execute_python — Execute Python code
schedule_task — Schedule a task for later
create_presentation — Create a .pptx presentation
```

**Example:**
- *"Remind me to check my email in 15 minutes"*
- *"Make a 5-slide presentation about space"*
- *"Write a Python script to parse a website"*

---

### ⚙️ Configuration
```
add_saved_directory — Add a folder to "favorites"
```

---

### What's improved?
- ✅ **API provider support:** OpenAI, Anthropic, OpenRouter, Groq, VLLM, etc.
- ✅ **Local models:** Ollama
- ✅ **Security:** Protection against config corruption
- ✅ **Quick access:** Saved folders and URLs

---

## 📝 How to update?

1. Download the new `RingZero.exe` from [Releases](https://github.com/DigitalDog1/RingZero/releases) or from our [Website](https://ringzero.vercel.app/). You can also update it through the app itself.
2. Replace the old file with the new one.
3. Run

> ℹ️ All your chats and settings will be saved.

---

## 🙏 Thank you!

Thank you for using **RingZero**! Your feedback and suggestions help us make the app better.

📧 Problems? → [GitHub Issues](https://github.com/DigitalDog1/RingZero/issues)
⭐ Like it? → [Put Star](https://github.com/DigitalDog1/RingZero)
