# Кластеризация клиентов онлайн-магазина

## Описание проекта
Этот проект основан на кластеризации клиентов онлайн-магазина для анализа их покупательского поведения. Целью является сегментация клиентов на основе их действий, что позволит разработать более эффективные маркетинговые стратегии и повысить лояльность клиентов.

## Датасет
Датасет, используемый в проекте, содержит информацию о покупках клиентов и их поведении. Ссылка на датасет: [data](https://1drv.ms/x/c/9e722d9ccae00a93/Ed4CsfycreZBjJ6DFvQioiABROat7ZuLio5Y8-nOZ_YlUw?e=VXojAQ).

## Сегментация клиентов
В ходе анализа были выделены следующие сегменты клиентов:
1. **Лояльные клиенты (cl0)**: Регулярные покупатели, приносящие значительную прибыль.
2. **Клиенты в зоне риска (cl1)**: Недавно совершали покупки, но приносят средний доход.
3. **Бывшие активные клиенты (cl2)**: Ранее лояльные клиенты, которые давно не совершали покупки.
4. **Спящие клиенты (cl3)**: Давно не покупали, минимальная активность.

## Запуск проекта
1. Перейдите в папку с проектом и откройте Jupyter Notebook:
   - Запустите Jupyter Notebook и откройте файл [main.ipynb](ipynb/main.ipynb).
2. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/Bigilittle/CustomerSegmentation


## Планы на будущее
- **Добавить Dockerfile** для упрощения развертывания приложения.
- **Создать пайплайн** для автоматизации процесса обработки данных и обучения модели.
- **Разработать сервер** для предоставления API с возможностью сегментации клиентов в реальном времени.
