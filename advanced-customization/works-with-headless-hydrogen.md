---
description: >-
  Diese Anleitung zeigt Ihnen, wie Sie BOGOS in Ihren Headless-/Hydrogen-Shop
  integrieren.
---

# Funktioniert mit Headless/Hydrogen

### Überblick

BOGOS bietet zwei Integrationsansätze für Headless-Shops, die jeweils für unterschiedliche Anwendungsfälle und technische Anforderungen konzipiert sind. Diese Anleitung erläutert beide Methoden, damit Sie die für Ihre Einrichtung passende auswählen können:

[Option 1: API-Integration (maximale Flexibilität)](works-with-headless-hydrogen.md#option-1-api-integration-maximum-flexibility)

[Option 2: JS/SDK-Integration (schnellere Implementierung)](works-with-headless-hydrogen.md#option-2-js-sdk-integration-faster-implementation)

### Option 1: API-Integration (maximale Flexibilität)

**Dokumentation:** [https://bogos-api-integration.gitbook.io/bogos-api-integration/integration-steps/gift-offer](https://bogos-api-integration.gitbook.io/bogos-api-integration/integration-steps/gift-offer)

**Am besten geeignet für:** Entwickler, die vollständige Kontrolle benötigen und für eine beliebige Plattform entwickeln (Web, mobile App oder Drittanbieter-Integrationen)

**Welche Angebote werden unterstützt**

Die API-Integration unterstützt **alle BOGOS-Angebotstypen**, einschließlich Geschenkangebote, Bündel, Upsells, Rabattangebote und Booster. Dieser Ansatz gibt Ihnen direkten Zugriff auf die Kernfunktionen von BOGOS über API-Endpunkte.

**Vorteile**

* **Vollständige Anpassung** - Erstellen Sie genau das, was Sie brauchen
* **Plattformunabhängig** - Funktioniert mit Web-Apps, mobilen Apps und Drittanbieter-Integrationen
* **Volle Kontrolle** - Implementieren Sie die Logik genau so, wie Sie es möchten

**Technische Anforderungen**

Ihr Entwicklungsteam benötigt fundierte Kenntnisse in:

* Shopify-Plattformarchitektur
* Storefront-API-Implementierung
* BOGOS-App-Funktionen und Angebotsmechanik

Dies ist keine Plug-and-Play-Lösung. Sie bauen die Integration von Grund auf, was bedeutet, dass Ihre Entwickler sowohl das Shopify-Ökosystem als auch die Funktionsweise von BOGOS-Aktionen im Detail verstehen müssen.

***

### Option 2: JS/SDK-Integration (schnellere Implementierung)

**Dokumentation:** [https://bogos-api-integration.gitbook.io/bogos-api-integration/bogos-js-sdk](https://bogos-api-integration.gitbook.io/bogos-api-integration/bogos-js-sdk)

**Am besten geeignet für:** Webanwendungen, bei denen die Implementierungsgeschwindigkeit wichtig ist und Sie funktionierende Codebeispiele wünschen

**Welche Angebote werden unterstützt**

Das JS/SDK unterstützt alle BOGOS-Angebotstypen und bietet Ihnen mit weniger Implementierungsaufwand volle Abdeckung der BOGOS-Funktionen.

**Vorteile**

* **Schnellere Entwicklung** - Ein vorgefertigtes SDK übernimmt die Hauptarbeit
* **Konkrete Beispiele** - Demo-Code hilft Ihnen bei einem schnellen Einstieg
* **Weniger detailliertes Fachwissen erforderlich** - Sie benötigen weiterhin Shopify- und Storefront-API-Kenntnisse, müssen aber nicht jedes Detail der BOGOS-Internas kennen

**Einschränkungen**

* **Nur Web-Apps** - Nicht kompatibel mit nativen mobilen Anwendungen

***

### Erste Schritte

**Schritt 1:** Überprüfen Sie Ihre technischen Anforderungen

* Welche Plattformen müssen Sie unterstützen?
* Welche Arten von Angeboten werden Sie während des BFCM ausführen?
* Wie sieht Ihr Entwicklungszeitplan aus?

**Schritt 2:** Bewerten Sie das Fachwissen Ihres Teams

* Wie vertraut sind sie mit der Architektur von Shopify?
* Haben sie die Kapazität, von Grund auf zu entwickeln (API), oder benötigen sie eine schnellere Implementierung (SDK)?

**Schritt 3:** Wählen Sie Ihre Integrationsmethode

* **API-Ansatz:** Beginnen Sie mit der Anleitung zur API-Integration für Ihren gewählten Angebotstyp.
* **SDK-Ansatz:** Sehen Sie sich die JS/SDK-Dokumentation und den Demo-Code an.

**Schritt 4:** Prüfen Sie die Dokumentation und bitten Sie das BOGOS-Support-Team um Ihren **BOGOS-API-Schlüssel**

**Schritt 5:** Entwickeln Sie anhand der Anweisungen Ihrer gewählten Methode.
