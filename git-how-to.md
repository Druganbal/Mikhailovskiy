Вот краткий гайд по установке Git на Windows:

---

### 1. **Скачайте Git**
   - Перейдите на официальный сайт: [git-scm.com](https://git-scm.com/).
   - Нажмите на кнопку **Download for Windows**.
   - Загрузите установочный файл.

---

### 2. **Запустите установку**
   - Откройте скачанный файл (например, `Git-2.xx.x-64-bit.exe`).
   - Следуйте инструкциям мастера установки:
     - Оставьте настройки по умолчанию, если не уверены.
     - На шаге **Choosing the default editor** выберите удобный текстовый редактор (например, **Nano** или **Notepad++**).
     - На шаге **Adjusting your PATH environment** выберите **Git from the command line and also from 3rd-party software**.
     - На шаге **Choosing HTTPS transport backend** выберите **Use the OpenSSL library**.
     - На шаге **Configuring the line ending conversions** выберите **Checkout Windows-style, commit Unix-style line endings**.
     - На шаге **Configuring the terminal emulator** выберите **Use MinTTY**.
     - Остальные настройки можно оставить по умолчанию.

---

### 3. **Завершите установку**
   - Нажмите **Install** и дождитесь завершения установки.
   - После установки закройте мастер.

---

### 4. **Проверка установки**
   - Откройте терминал (CMD, PowerShell или Windows Terminal).
   - Введите команду:
     ```bash
     git --version
     ```
   - Если Git установлен, вы увидите версию (например, `git version 2.xx.x`).

---

### 5. **Настройка Git**
   - Установите имя и email (это нужно для коммитов):
     ```bash
     git config --global user.name "Ваше Имя"
     git config --global user.email "ваш.email@example.com"
     ```

---

Готово! Теперь Git установлен и готов к использованию. 🚀