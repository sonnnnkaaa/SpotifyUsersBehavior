# Кластеризация пользователей Spotify

## Описание проекта
Анализ поведения пользователей Spotify, сегментация на 4 кластера и выявление основных моделей поведения пользователей.

## Главные результаты
- Выделено 4 типа пользователей с разными показателями активности и типами подписки
- Silhouette score: 0.73 (высокое качество кластеризации)
- Обнаружены пользователи (12%), которые оплачивают подписку, но не пользуются сервисом

## Технологии
- Python (pandas, numpy, scikit-learn)
- Визуализация: matplotlib, seaborn
- Кластеризация: K-Means, Agglomerative, PCA

## Как запустить
```bash
git clone https://github.com/sonnnnkaaa/SpotifyUsersBehavior
cd SpotifyUsersBehavior
python -m venv .venv
pip install -r requirements.txt
jupyter notebook code/spotify-users-behavior-clustering.ipynb
```

Файл `spotify-users-behavior-clustering.ipynb` можно открыть в Google Colab или в VSCode.
