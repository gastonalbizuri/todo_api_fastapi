# To-Do API (FastAPI)

Eine einfache REST-API zur Verwaltung von Aufgaben, entwickelt mit FastAPI. Dieses Projekt ist Teil meines Portfolios als Junior Backend-Entwickler.

## Endpunkte

- `GET /tasks`: Listet alle Aufgaben auf
- `POST /tasks`: Erstellt eine neue Aufgabe
- `GET /tasks/{id}`: Zeigt eine Aufgabe anhand der ID an
- `DELETE /tasks/{id}`: Löscht eine Aufgabe anhand der ID

## Technologien

- Python 3
- FastAPI
- Uvicorn

## Anleitung zur Ausführung

Um die API lokal zu starten, führen Sie folgenden Befehl aus:

```bash
uvicorn main:app --reload
