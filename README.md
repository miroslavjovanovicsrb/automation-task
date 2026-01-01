### Dokumentation
Toolstack: Python (Jupyter Notebook), Pandas, OpenAI API (GPT-4o).
## Vorgehensweise:
# Daten-Setup: 
Erstellung einer Basisliste mit Headlines (Fokus: Solar & Finanzen) und Bild-Prompts.

# AI-Optimierung: 
Über die OpenAI API wurden die Headlines automatisiert in zwei psychologische Varianten (Emotional & Benefit-getrieben) übersetzt. Die Bild-Ideen wurden technisch für Bild-KIs (DALL-E/Midjourney) präzisiert.

# Matrix-Generierung: 
Mittels eines Cross-Joins wurde jede Headline-Variante mit jedem optimierten Prompt kombiniert, um eine strukturierte Test-Basis zu erhalten.

# Erweiterbarkeit für den Produktivbetrieb:
Direkte Anbindung an die Airtable API, um Ergebnisse ohne manuellen CSV-Import zu synchronisieren.
Integration von DALL-E 3, um die Visuals direkt im Workflow zu generieren.
Implementierung eines Approval-Schritts (z.B. via Slack), bevor die Creatives in den Ad Manager geladen werden.
