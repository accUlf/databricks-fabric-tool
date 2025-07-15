# 🚀 Databricks vs. Fabric Entscheidungsbaum

Eine interaktive Webanwendung zur Unterstützung bei der Auswahl der optimalen Datenplattform für Ihr Unternehmen.

## 📋 Überblick

Dieses Tool hilft Organisationen dabei, eine fundierte Entscheidung zwischen **Databricks**, **Microsoft Fabric** oder einer **Hybrid-Lösung** zu treffen. Durch einen strukturierten Fragebogen werden die wichtigsten Faktoren wie Budget, technische Expertise, Anwendungsfälle und Komplexitätstoleranz bewertet.

## 🎯 Funktionen

### Intelligente Bewertung
- **10 strukturierte Fragen** zu kritischen Entscheidungsfaktoren
- **K.O.-Kriterien** für realistische Empfehlungen
- **Dynamische Scoring-Algorithmus** mit Echtzeit-Updates
- **Fortschrittsanzeige** und visuelle Bewertungsübersicht

### Bewertungskriterien
1. **Unternehmensgröße** (Startup, Mittelstand, Großunternehmen)
2. **Budget** (< 50k bis > 1 Mio. €/Jahr)
3. **Technische Expertise** (Business User bis Data Engineers)
4. **Anwendungsfälle** (BI/Reporting vs. Advanced Analytics/ML)
5. **Komplexitätstoleranz** (Minimal bis Hoch)
6. **Cloud-Strategie** (Azure-First, Multi-Cloud, Flexibel)
7. **Time-to-Value** (Kritisch bis Flexibel)
8. **Datenverarbeitung** (Batch, Real-time, Gemischt)
9. **BI-Integration** (Kritisch bis Minimal)
10. **Open Source Integration** (Kritisch bis Unwichtig)

### Ergebnisse & Empfehlungen

#### 🔥 Databricks
- **Optimal für:** Advanced Analytics, ML/AI, Multi-Cloud, technische Teams
- **Kosten:** 2.000-20.000€/Monat + BI-Tool-Kosten
- **Vorteile:** Maximale Flexibilität, Open Source, Performance
- **Nachteile:** Höhere Komplexität, separates BI-Tool erforderlich

#### 📊 Microsoft Fabric
- **Optimal für:** BI-fokussierte Organisationen, Microsoft-Ökosystem, Business User
- **Kosten:** 320-10.000€/Monat (F2-F64 Capacity)
- **Vorteile:** Integrierte BI, niedrige Einstiegshürde, vereinfachte Administration
- **Nachteile:** Azure-beschränkt, weniger ML/AI-Features

#### 🔀 Hybrid-Lösung
- **Optimal für:** Großunternehmen, diverse Anforderungen, Best-of-Breed-Ansatz
- **Kosten:** Mindestens 2.500€/Monat aufwärts
- **Vorteile:** Maximale Flexibilität, optimierte Nutzung beider Plattformen
- **Nachteile:** Höhere Komplexität, doppelte Lizenzkosten

## 🛠️ Technische Implementierung

### Frontend
- **Vanilla JavaScript** für optimale Performance
- **Responsive Design** mit CSS Grid/Flexbox
- **Progressive Enhancement** für maximale Kompatibilität
- **Accessibility** mit ARIA-Labels und Keyboard-Navigation

### Features
- **Smooth Animations** mit CSS-Transitionen
- **Real-time Scoring** mit visueller Feedback
- **Mobile-First Design** für alle Geräte
- **Lokale Datenspeicherung** (keine Server-Abhängigkeit)

### Algorithmus
```javascript
// Scoring-System mit K.O.-Kriterien
- Multi-Cloud erforderlich → Fabric ausgeschlossen
- Minimale Komplexität + niedriges Budget → Databricks ausgeschlossen
- Niedriges Budget → Kombination ausgeschlossen
- Gewichtete Bewertung basierend auf Antworten
- Kontextuelle Entscheidung bei knappen Ergebnissen
```

## 🚀 Nutzung

### Lokal starten
```bash
# Einfach die index.html in einem Browser öffnen
open index.html
```

### Web-Deployment
```bash
# Auf beliebigen Webserver deployen
# Keine Server-Side Dependencies erforderlich
```

### Integration
```html
<!-- Einfache iframe-Integration -->
<iframe src="path/to/index.html" width="100%" height="800px"></iframe>
```

## 📊 Bewertungslogik

### K.O.-Kriterien
- **Multi-Cloud zwingend** → Fabric nicht möglich
- **Minimale Komplexität + niedriges Budget** → Nur Fabric
- **Niedriges Budget** → Kombination nicht finanzierbar

### Scoring-Gewichtung
- **Budget**: 20% (kritischer Faktor)
- **Technische Expertise**: 15%
- **Anwendungsfall**: 20%
- **Komplexitätstoleranz**: 15%
- **Cloud-Strategie**: 10%
- **Time-to-Value**: 5%
- **Datenverarbeitung**: 5%
- **BI-Integration**: 7%
- **Open Source**: 3%

## 🏢 Entwickelt von

**accantec group AG** - part of x|F  
Spezialisiert auf Datenplattform-Architektur und Cloud-Analytics

---

## 📄 Lizenz

Dieses Tool wurde für Beratungszwecke entwickelt und steht unter den Nutzungsbedingungen der accantec group AG.

## 🔄 Updates

- **v1.0** - Initiale Version mit 9 Fragen
- **v1.1** - Erweitert um Open Source Integration (Frage 10)
- **v1.2** - Optimierte Scoring-Algorithmus und K.O.-Kriterien

## 🤝 Beitrag

Feedback und Verbesserungsvorschläge sind willkommen. Bitte erstellen Sie ein Issue oder Pull Request.
