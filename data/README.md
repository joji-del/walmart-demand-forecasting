# Данные

Ноутбук ожидает файл `walmart-sales-dataset-of-45stores.csv` в этой папке.

Источник: [Walmart Sales Dataset of 45stores](https://www.kaggle.com/datasets/varsharam/walmart-sales-dataset-of-45stores) (Kaggle).
Скачайте CSV вручную (нужен аккаунт Kaggle) или через Kaggle CLI:

```bash
kaggle datasets download -d varsharam/walmart-sales-dataset-of-45stores -p data --unzip
```

Колонки: `Store`, `Date` (формат `dd-mm-yyyy`), `Weekly_Sales`, `Holiday_Flag`, `Temperature`, `Fuel_Price`, `CPI`, `Unemployment`.
6 435 строк: 45 магазинов × 143 недели (05.02.2010 – 26.10.2012).

Сам CSV в репозиторий не добавлен (см. `.gitignore`).
