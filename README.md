# Recommender-systems

[![Open in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Jam-Reut/ml-recommender-systems/HEAD?labpath=recommender-systems.ipynb)

## 🚀 Projektbeschreibung

In diesem Projekt wird ein einfaches Inhalt-basiertes Empfehlungssystem mit Python und Pandas entwickelt. 
Ziel ist es, auf Basis von Film-Ähnlichkeiten andere Filme zu empfehlen – ohne Nutzerverhalten zu analysieren.
Ein zusätzliches Notebook mit einer fortgeschritteneren Version steht ebenfalls zur Verfügung und vertieft die vorgestellten Konzepte.

## Projektstruktur
recommender-systems/
- recommender-systems.ipynb # Haupt-Notebook mit Basis-Modell
- data:
	- u.data # Nutzungsdaten (User-Ratings)
	- u.item # Filminformationen
	- movie_id_titles # Zuordnung Film-ID zu Filmtiteln
- README.md


### 🔧 Ausführen

1. Klicke auf den **Binder-Button oben**, um das Projekt interaktiv im Browser auszuführen.
2. Öffne das Notebook `recommender-systems.ipynb` oder `
3. Starte alle Zellen nacheinander.
4. Am Ende wird eine Liste von Filmen angezeigt, die ähnlich zu einem gewählten Film sind.

### 🎯 Ergebnis

- Ein Pandas-basiertes DataFrame mit Filmempfehlungen, die auf Ähnlichkeit der Bewertungen durch andere Nutzer beruhen.
