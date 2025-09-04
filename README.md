# 🧠 CLANN: Convex Laplase Neural Network for Hyperelastic Constitutive Modeling

[![PDF Status](https://img.shields.io/badge/PDF-Доступен-brightgreen.svg)](main_rus.pdf)
[![LaTeX](https://img.shields.io/badge/LaTeX-3.14159-blue.svg)](https://www.latex-project.org/)
[![License](https://img.shields.io/badge/License-CC--BY--NC--ND-red.svg)](LICENSE)

## 📖 Описание проекта

**CLANN** (Convex Laplace Neural Network) — это термодинамически корректная гиперупругая модель, основанная на выпуклой нейронной сети и лог-лапласовой параметризации. Данная работа представляет новый подход к моделированию гиперупругих материалов с использованием современных методов машинного обучения.


## 📚 Доступные версии

| Язык | Файл | Статус | Скачать |
|------|------|--------|---------|
| 🇷🇺 Русский | `main_rus.pdf` | 🔄 В работе | [📥 Скачать PDF](main_rus.pdf) |
| 🇺🇸 English | `eng/main.pdf` | 🔄 В работе | [📥 Скачать PDF](eng/main.pdf) |

## 🔬 Содержание работы

### Основные разделы:
1. **Введение** — актуальность, цели и задачи исследования
2. **Теоретические основы** — математические принципы CLANN
3. **Методология** — описание алгоритма и архитектуры
4. **Результаты** — численные эксперименты и валидация
5. **Заключение** — выводы и перспективы развития

### Ключевые результаты:
- Разработана новая архитектура нейронной сети для моделирования гиперупругих материалов
- Доказана термодинамическая корректность предложенной модели
- Проведена валидация на реальных экспериментальных данных

## 🏗️ Структура проекта

```
clann/
├── 📄 main_rus.tex          # Основная статья на русском языке
├── 📄 main_rus.pdf          # Скомпилированная PDF версия
├── 📁 eng/                  # Английская версия
│   ├── main.tex            # Основная статья на английском
│   ├── main.pdf            # Скомпилированная PDF версия
│   ├── clann_math.markdown # Математические выкладки
│   └── template.tex        # LaTeX шаблон
├── 📁 parts/               # Составные части статьи
│   ├── chapter_clann.tex   # Основная глава
│   └── bibliography.bib    # Библиография
├── 📁 img/                 # Изображения и диаграммы
```

## 🚀 Быстрый старт

### Предварительные требования
- LaTeX дистрибутив (TeX Live, MiKTeX)
- Git

### Локальная разработка

1. **Клонирование репозитория:**
```bash
git clone https://github.com/YOUR_USERNAME/clann.git
cd clann
```

2. **Компиляция русской версии:**
```bash
pdflatex main_rus.tex
bibtex main_rus
pdflatex main_rus.tex
pdflatex main_rus.tex
```

3. **Компиляция английской версии:**
```bash
cd eng
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

### Использование latexmk (рекомендуется)
```bash
# Русская версия
latexmk -pdf main_rus.tex

# Английская версия
cd eng
latexmk -pdf main.tex
```

## 📊 Предварительный просмотр

### Русская версия
<details>
<summary>📋 Краткое содержание</summary>

- **Введение** — актуальность и цели исследования
- **Теоретические основы CLANN** — математические принципы
- **Методология** — алгоритм и архитектура
- **Результаты** — эксперименты и валидация
- **Заключение** — выводы и перспективы

</details>

### English version
<details>
<summary>📋 Table of Contents</summary>

- **Introduction** — relevance and research objectives
- **Theoretical foundations of CLANN** — mathematical principles
- **Methodology** — algorithm and architecture
- **Results** — experiments and validation
- **Conclusion** — findings and future prospects

</details>

## 🔍 Дополнительные материалы

- **Математические выкладки** — подробные доказательства и выводы доступны в [clann_math.markdown](eng/clann_math.markdown)
- **LaTeX шаблон** — готовый шаблон для форматирования статей в [template.tex](eng/template.tex)

## 📝 Цитирование

Если вы используете данную работу в своих исследованиях, пожалуйста, цитируйте:

```bibtex
@article{clann2024,
  title={CLANN: Convex Neural Network for Hyperelastic Constitutive Modeling},
  author={[Ваша фамилия]},
  journal={[Название журнала]},
  year={2024},
  volume={[Том]},
  number={[Номер]},
  pages={[Страницы]}
}
```

## 🤝 Вклад в проект

Мы приветствуем вклад в развитие проекта! Если у вас есть предложения по улучшению или вы нашли ошибки, пожалуйста:

1. Создайте Issue с описанием проблемы
2. Сделайте Fork репозитория
3. Создайте Pull Request с вашими изменениями

## 📄 Лицензия

Данная работа распространяется под лицензией [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/).

---
</div>
