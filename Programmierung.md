# Programmierung eines KI-Agenten

## Was ist das?
Direkte Programmierung mit einer Programmiersprache (z. B. Python, JavaScript).

## Wofür wird es bei der Erstellung eines KI-Agenten verwendet?
Erstellung der Logik eines KI-Agenten von Grund auf. Anbindung von neuronalen Netzwerken, APIs, Datenbanken.

## Beispiel
```python
import openai

openai.api_key = "your_api_key"

response = openai.ChatCompletion.create(
    model="gpt-4",
    messages=[{"role": "user", "content": "Hallo, was kannst du?"}]
)

print(response['choices'][0]['message']['content'])
```

## Vorteile
- Volle Kontrolle über die Logik.
- Maximale Leistung und Anpassung.

## Nachteile
- Erfordert Programmierkenntnisse.
- Längere Entwicklungszeit.
