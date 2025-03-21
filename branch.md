Вот пример текста, который можно добавить в новый файл (например, `branch_guide.txt`) о том, как пользоваться ветками в Git:

---

### Как пользоваться ветками в Git

Ветки в Git позволяют работать над разными задачами параллельно, не затрагивая основной код. Вот основные команды:

1. **Создание новой ветки**
   ```bash
   git branch feature/new-feature
   

2. Переключение на ветку
      git checkout feature/new-feature
   
   Или (в новых версиях Git):
      git switch feature/new-feature
   

3. Создание и переключение на новую ветку одной командой
      git checkout -b feature/new-feature
   

4. Просмотр всех веток
      git branch
   

5. Слияние ветки в текущую
   Переключитесь на ветку, в которую хотите влить изменения, и выполните:
      git merge feature/new-feature
   

6. Удаление ветки
      git branch -d feature/new-feature

7. Отправка ветки на удалённый репозиторий
      git push origin feature/new-feature

8. Получение изменений из удалённой ветки
      git fetch origin
   git checkout feature/new-feature
   

---

Совет: Используйте ветки для изоляции новой функциональности, исправления багов или экспериментов. Это помогает сохранять основной код стабильным.

---
```