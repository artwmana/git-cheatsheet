# git-cheatsheet

Этот репозиторий - структурированная документация по Git:
- Базовые команды
- Рабочие пайплайны (feature → PR → release)
- Разбор вопросов на собеседованиях

Документация разбита по сценариям использования: сначала минимальная база,
потом реальные рабочие процессы, затем глубинное понимание для собесов.

---

## 10 самых нужных команд

```bash
git clone <url>
git status
git add .
git commit -m "message"
git push -u origin feature-x
git pull --rebase
git branch
git switch -c feature-x
git merge feature-x
git stash
```

---

## Структура документации
1. [Базовые команды + теория](docs/git/basics/)

2. [Пайплайны для работы](docs/git/pipelines/)

3. [Разбор собеседований (продвинутые сценарии)](docs/git/interviews/)