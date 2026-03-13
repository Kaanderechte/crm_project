# Flask CRM System

Ein Customer Relationship Management System entwickelt mit Flask und SQLite.

## Features

- Customer Management (CRUD)
- Lead Tracking
- User Authentication (Login/Logout/Register)
- Persistente Datenspeicherung mit SQLite
- Dashboard mit Statistiken

## Installation

1. Repository klonen
2. Abhängigkeiten installieren: `pip install -r requirements.txt`
3. App starten: `python app.py`
4. Browser öffnen: `http://127.0.0.1:5000`

## Standard-Zugangsdaten

- Admin: `admin` / `admin123`
- User: `user` / `user123`

## Projektstruktur

- `app.py` – Flask Controller und Routen
- `models.py` – Datenbankmodelle (SQLAlchemy)
- `templates/` – HTML Templates
- `static/` – CSS und JavaScript
- `docs/` – UML Diagramme

## Diagramme

- `docs/erd.png` – Entity Relationship Diagram
- `docs/use_case.png` – Use-Case Diagramm
- `docs/activity.png` – Aktivitätsdiagramm
- `docs/sequence.png` – Sequenzdiagramm
