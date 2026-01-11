# Experiments: BiLSTM NER (Character-level)

**Цель:**

Папка содержит экспериментальные ноутбуки и данные для серии контролируемых экспериментов по обучению BiLSTM-модели для NER на символьном уровне на подвыборке из 5000 примеров.

## Состав

- `5__Экспериментальный_ноутбук_.ipynb` — основной экспериментальный ноутбук для экспериментов.
- `data/` — файлы с обучающей выборкой:
  - `xTrain_BiLSTM_idx_5000.txt`
  - `yTrain_BiLSTM_padded_5000.txt`

## Быстрый старт

Откройте экспериментальный ноутбук в Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vitality1918-ctrl/diploma-project/blob/main/experiments_notebook/5__Экспериментальный_ноутбук_.ipynb)

> **Словари (vocab) для экспериментов берутся из финального ноутбука:**
> [final_notebook/vocab/](https://github.com/vitality1918-ctrl/diploma-project/tree/main/final_notebook/vocab)

## Описание экспериментов

- Все эксперименты используют одинаковые данные, словари и пайплайн загрузки.
- Отличие между экспериментами — **ровно один фактор** (уменьшение параметров, добавление Dropout).
- Это позволяет объективно сравнивать влияние каждого изменения.

## Рекомендации

- Для запуска используйте Google Colab или Jupyter Notebook.
- Если добавляете новые данные или ноутбуки — обновляйте этот README.md.

---

**Контакты:** vitality1918-ctrl (GitHub)
