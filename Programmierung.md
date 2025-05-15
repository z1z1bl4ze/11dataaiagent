# Programmierung eines KI-Agenten

## Was ist das?
Man programmiert die Logik direkt mit einer Programmiersprache (z.B. Python).

## Schritt-für-Schritt Beispiel (Python):

1. API-Key von OpenAI besorgen.
2. OpenAI-Python-Bibliothek installieren: `pip install openai`
3. Einfacher Chatbot-Code:

```python
import openai

openai.api_key = "DEIN_API_KEY"

def chat_with_agent(message):
    response = openai.ChatCompletion.create(
        model="gpt-4",
        messages=[{"role": "user", "content": message}]
    )
    return response['choices'][0]['message']['content']

print(chat_with_agent("Hallo, wie geht es dir?"))
```

## Vorteile
- Volle Kontrolle über Funktionen
- Anpassbar für komplexe Aufgaben

## Nachteile
- Programmierkenntnisse erforderlich
- Höherer Entwicklungsaufwand
