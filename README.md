# social-content — скіл для Claude Code

**пости для соцмереж**

Окремий скіл із паку [my-skills](https://github.com/JulyLay/my-skills) від Юлії Лайко. Усі 51 скіл одним паком — там.

## 🚀 Як встановити

Відкрий Claude Code, новий чат, встав промт:

```
Встанови мені скіл з репозиторію https://github.com/JulyLay/social-content.git так, щоб він був доступний у будь-якому чаті назавжди:
1. Зклонуй репозиторій у ~/.claude/skills/social-content (якщо папки ~/.claude/skills немає — створи).
2. Видали з неї папку .git.
3. Перевір, що є файл ~/.claude/skills/social-content/SKILL.md.
4. Зроби все сам і коротко підтверди, що скіл встановлено.
```

Або командою в терміналі:

```bash
git clone https://github.com/JulyLay/social-content.git ~/.claude/skills/social-content && rm -rf ~/.claude/skills/social-content/.git
```

Далі просто опиши задачу в чаті або виклич `/social-content`.

## 📄 Першоджерело і ліцензія

Скіл базується на відкритому наборі [marketingskills](https://github.com/coreyhaines31/marketingskills) від Corey Haines (MIT). Текст ліцензії — у файлі `LICENSE`.

## 💜 Авторка

**Юлія Лайко** — AI-маркетологиня. [codegirlai.com](https://www.codegirlai.com/) · Telegram [@julylay](https://t.me/julylay)
