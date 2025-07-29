# 🚕 Reinforcement Learning mit Q-Learning und SARSA auf Taxi-v3

Dieses Projekt implementiert und vergleicht zwei klassische tabellarische RL-Algorithmen – **Q-Learning** und **SARSA** – in der bekannten Umgebung `Taxi-v3` aus dem Gymnasium-Toolkit.

Ziel ist es, einem Agenten beizubringen, in einer kleinen Stadt effizient Passagiere abzuholen und korrekt abzusetzen.

## 📄 Inhalt

- `RL_taxi.ipynb` – Hauptnotebook mit vollständiger Implementierung, Training, Visualisierung und Auswertung
- `requirements.txt` – Python-Abhängigkeiten für lokale Ausführung
- `README.md` – Dieses Dokument

## 🚀 Schnellstart (empfohlen)

Die einfachste Möglichkeit ist die Ausführung in **Google Colab**:

[📂 Notebook jetzt in Colab öffnen](https://colab.research.google.com/github/loenneberger/RL/blob/main/RL_taxi.ipynb)


## Alternativ: Lokal ausführen

### 1. Repository klonen
  git clone https://github.com/loenneberger/RL.git
  
  cd RL

### 2. (Optional) Virtuelle Umgebung erstellen
  python -m venv venv
  
  source venv/bin/activate  # Windows: venv\Scripts\activate

### 3. Abhängigkeiten installieren
  pip install -r requirements.txt

### 4. Notebook starten
  jupyter notebook RL_taxi.ipynb

## 📊 Features
Tabellarisches Q-Learning (Off-Policy)

Tabellarisches SARSA (On-Policy)

Epsilon-Greedy Exploration mit Decay

Lernkurven mit Moving Average

Visuelle Beispiel-Episoden (GIF-Animationen)

Vergleich der Agentenleistung


## 🔍 Hinweis
Das Projekt wurde im Rahmen einer Reinforcement-Learning-Lehrveranstaltung umgesetzt und ist besonders auf einfache Reproduzierbarkeit in Colab ausgelegt.

Teile dieses Codes wurden mit Unterstützung von ChatGPT (OpenAI) generiert.
Die finalen Implementierungen wurden überprüft, getestet und ggf. angepasst.

