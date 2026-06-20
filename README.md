# Rewriting Academic

Проект для переписывания и рефакторизации академических текстов с использованием различных алгоритмов и методов обработки естественного языка.

## Возможности

- **Синонимическая замена** — замена слов и фраз на синонимы
- **Изменение структуры предложений** — реорганизация синтаксиса
- **Паraphrase-based переписывание** — переписывание на основе парафраз
- **Улучшение академического стиля** — адаптация текста к академическим стандартам
- **Сохранение смысла** — гарантия сохранения исходного содержания

## Структура проекта

```
Rewriting-academic/
├── algorithms/              # Основные алгоритмы переписывания
│   ├── __init__.py
│   ├── synonym_replacer.py  # Синонимическая замена
│   ├── paraphrase.py        # Парафразирование
│   ├── structure_modifier.py # Модификация структуры
│   └── style_enhancer.py    # Улучшение стиля
├── utils/                   # Вспомогательные функции
│   ├── __init__.py
│   ├── nlp_tools.py         # Инструменты обработки текста
│   └── synonym_database.py  # База данных синонимов
├── tests/                   # Тесты
│   └── __init__.py
├── examples/                # Примеры использования
│   └── demo.py
└── requirements.txt         # Зависимости
```

## Установка

```bash
pip install -r requirements.txt
```

## Быстрый старт

```python
from algorithms.synonym_replacer import SynonymReplacer

replacer = SynonymReplacer()
original_text = "The important research shows significant results."
rewritten = replacer.rewrite(original_text)
print(rewritten)
```

## Лицензия

MIT
