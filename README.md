# CrptApi - Класс для работы с API Честного знака

## Описание проекта
Данный проект представляет собой реализацию класса CrptApi на языке Java, предназначенного для работы с API Честного знака. Класс обеспечивает возможность создания документа для ввода в оборот товара, произведенного в РФ, и поддерживает ограничение на количество запросов к API в заданный интервал времени.

Конструктор класса CrptApi позволяет создать экземпляр класса с указанными ограничениями на количество запросов к API.
### Параметры:
- timeUnit: Перечисление (enum) типа TimeUnit, указывающее промежуток времени для ограничения запросов (например, TimeUnit.SECONDS или TimeUnit.MINUTES).
- requestLimit: Целочисленное значение, определяющее максимальное количество запросов в заданном промежутке времени.

