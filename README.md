# Spotify Users Clustering

Data: https://www.kaggle.com/datasets/sahilislam007/spotify-user-behavior-and-pattern

## Project Description
Analysis of Spotify user behavior, segmentation into 4 clusters, and identification of key user behavior patterns.

## Key Results
- Identified 4 user types with different activity levels and subscription types
- Silhouette score: 0.73 (high clustering quality)
- Discovered users (12%) who pay for subscription but don't use the service

## Technologies
- Python (pandas, numpy, scikit-learn)
- Visualization: matplotlib, seaborn
- Clustering: K-Means, Agglomerative, PCA

## How to run
```bash
git clone https://github.com/sonnnnkaaa/SpotifyUsersBehavior
cd SpotifyUsersBehavior
python -m venv .venv
pip install -r requirements.txt
jupyter notebook code/spotify-users-behavior-clustering.ipynb
```

File `spotify-users-behavior-clustering.ipynb` can be opened in Google Colab or VSCode.

---

# Кластеризация пользователей Spotify

Данные: https://www.kaggle.com/datasets/sahilislam007/spotify-user-behavior-and-pattern

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
