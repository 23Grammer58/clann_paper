# CLANN: Convex Neural Network for Hyperelastic Constitutive Modeling

## Описание проекта

CLANN - это термодинамически корректная гиперупругая модель на основе выпуклой нейронной сети и лог-лапласовой параметризации.

## Структура проекта

- `main.tex` - основная статья на английском языке
- `rus/main_rus.tex` - версия статьи на русском языке
- `clann_math.tex` - математические выкладки и доказательства
- `template.tex` - шаблон для форматирования
- `Definitions/` - стили и определения для LaTeX

## Работа с проектом

### Локальная разработка

1. Клонируйте репозиторий:
```bash
git clone https://github.com/YOUR_USERNAME/clann-paper.git
cd clann-paper
```

2. Убедитесь, что у вас установлен LaTeX компилятор (TeX Live, MiKTeX)

3. Скомпилируйте документ:
```bash
pdflatex main.tex
# или используйте latexmk
latexmk -pdf main.tex
```

### Работа в Overleaf

1. Создайте новый проект в Overleaf
2. Настройте Git интеграцию (Premium) или GitHub Sync (Free)
3. Укажите URL вашего GitHub репозитория
4. Работайте над документом в Overleaf - изменения автоматически синхронизируются

### Workflow для контрибьюторов

1. **Создание ветки для изменений:**
```bash
git checkout -b feature/your-feature-name
```

2. **Внесение изменений** (локально или в Overleaf)

3. **Коммит изменений:**
```bash
git add .
git commit -m "Описание изменений"
```

4. **Push в репозиторий:**
```bash
git push origin feature/your-feature-name
```

5. **Создание Pull Request** на GitHub

### Синхронизация между Overleaf и локальным репозиторием

- Изменения в Overleaf автоматически коммитятся в GitHub
- Для получения изменений локально:
```bash
git pull origin main
```

## Требования

- LaTeX дистрибутив (TeX Live, MiKTeX)
- Git
- Overleaf аккаунт (рекомендуется Premium для Git интеграции)

## Лицензия

[Укажите лицензию проекта]

## Контакты

[Укажите контактную информацию]
