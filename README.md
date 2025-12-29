# Анализ резюме hh.ru (EDA + преобразование и очистка данных)

Проект содержит разведывательный анализ данных (EDA), преобразование признаков и очистку данных.
Основной артефакт — ноутбук: `Python_для_анализа_данных__Итоговыи__проект_Костиков_Алексей.ipynb`.

## Данные

GitHub не позволяет хранить файлы > 25 МБ, поэтому датасеты в репозиторий не добавлены.

- Курсы валют (ExchangeRates 2): https://drive.google.com/file/d/1Pct0CselzIMYGK8sApv4tu3ScmqHxKr3/view?usp=sharing  
- Датасет резюме (dst-3.0_16_1_hh_database): https://drive.google.com/file/d/1Eg3c4TGSdFUK9rQ_bTgkFExwhPOHH9kt/view?usp=sharing

После скачивания укажи пути к файлам в первой ячейке ноутбука, по моему примеру (MacOS):
```python
DATA_PATH = '/Users/alekseikostikov/Downloads/Новая папка/dst-3.0_16_1_hh_database.csv'
RATES_PATH = '/Users/alekseikostikov/Downloads/Новая папка/ExchangeRates 2.csv'