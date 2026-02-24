# Vyshka Liga Tools

Инструменты для учеников Вышка Лига.

---

## YouTube Thumbnail AI

Генерация профессиональных превью для YouTube через Claude + Gemini.

### Структура

```
skill/                          ← скилл для Claude Code
  SKILL.md                      ← инструкция для Claude
  brand-style.md                ← стиль бренда (настрой под себя)
  scripts/
    generate_thumbnail.py       ← генерация через Gemini API
    combine_thumbnails.py       ← сборка сравнительного грида
    search_examples.py          ← поиск конкурентов (опционально)
  assets/headshots/             ← положи сюда своё фото

guide/
  youtube-thumbnail-guide.html  ← интерактивная инструкция по установке
```

### Быстрый старт

1. Открой `guide/youtube-thumbnail-guide.html` в браузере
2. Следуй инструкции — установка займёт 15 минут
3. Скопируй готовые промпты прямо из гайда

### Требования

- [Claude Code](https://claude.ai/download)
- Gemini API Key — бесплатно на [aistudio.google.com](https://aistudio.google.com)
- Python 3.9+

---

*Вышка Лига · Premium Infobusiness*
