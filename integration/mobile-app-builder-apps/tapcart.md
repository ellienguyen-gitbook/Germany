---
hidden: true
noIndex: true
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# Tapcart

[**Tapcart**](https://apps.shopify.com/freegifts?app_code=bogos\&referral_code=tapcart\&utm_term=tapcart\&utm_campaign=integration_helpdoc\&utm_medium=Tapcart\&utm_source=Partner\&sca_ref_code=tapcart\&sca_ref_offer=all) ist ein Mobile-App-Builder für Shopify-Händler, die eine vollständig gebrandete iOS- und Android-App ohne Entwicklerarbeit möchten. Mit App Studio kann Ihr Marketingteam Design und Inhalte unabhängig steuern, während integrierte KI dabei hilft, Kampagnen, Produktempfehlungen und Customer Journeys basierend auf dem Verhalten der Käufer zu personalisieren.

Durch die Integration zwischen [BOGOS](https://apps.shopify.com/freegifts?utm_source=gitbook\&utm_medium=integration\&utm_campaign=Tapcart) und [Tapcart](https://apps.shopify.com/freegifts?app_code=bogos\&referral_code=tapcart\&utm_term=tapcart\&utm_campaign=integration_helpdoc\&utm_medium=Tapcart\&utm_source=Partner\&sca_ref_code=tapcart\&sca_ref_offer=all) können Sie ganz einfach Geschenkaktionen von einem einzigen Dashboard aus erstellen, verwalten und in Ihrer Mobile App anzeigen.

**Die wichtigsten Funktionen von Tapcart:**

* No-Code-App-Builder – Starten Sie schnell eine vollständig gebrandete Mobile App mit voller kreativer Kontrolle
* Personalisiertes Engagement – Nutzen Sie KI, um maßgeschneiderte Kampagnen, Empfehlungen und Nutzerreisen bereitzustellen
* Push-Benachrichtigungen – Erreichen Sie Kunden direkt auf ihrem Homescreen mit gezielten Nachrichten
* Auf Kundenbindung ausgerichtete Tools – Verbessern Sie die Loyalität mit individuellem Onboarding und Bestellerlebnissen
* Echtzeit-Einblicke – Optimieren Sie die Leistung mit Analysen und automatischen Updates

_**Hinweis:**_

Geschenkangebote funktionieren in der Mobile App nur, wenn der Geschenkmechanismus auf Gift Clone eingestellt ist.

So konfigurieren Sie dies:

* Gehen Sie zu BOGOS → Einstellungen.
* Suchen Sie den Geschenklogik-Mechanismus und wählen Sie Produkt klonen aus.

<figure><img src="../../.gitbook/assets/unknown (224).png" alt=""><figcaption></figcaption></figure>

## So integrieren Sie BOGOS mit Tapcart

**Schritt 1:** Installieren Sie [BOGOS](https://apps.shopify.com/freegifts?utm_source=gitbook\&utm_medium=integration\&utm_campaign=Tapcart) und [Tapcart](https://apps.shopify.com/freegifts?app_code=bogos\&referral_code=tapcart\&utm_term=tapcart\&utm_campaign=integration_helpdoc\&utm_medium=Tapcart\&utm_source=Partner\&sca_ref_code=tapcart\&sca_ref_offer=all) aus dem Shopify App Store&#x20;

Derzeit haben wir die Tapcart-Integration noch nicht in Produktion bereitgestellt. Für Testzwecke senden Sie bitte eine Kollaborator-Anfrage an **bogos-tapcart-integration.myshopify.com** (Code: 2315).&#x20;

Für alle Einrichtungsanfragen wenden Sie sich bitte an das Tapcart-Team.&#x20;

**Schritt 2:** Richten Sie Geschenkangebote in der **BOGOS App** ein

Um Geschenkangebote einzurichten, folgen Sie bitte der Anleitung hier: [Geschenkangebot erstellen](https://bogos-guideline.gitbook.io/user-guide/detailed-guide/gift-offer/create-gift-offer#id-4.-select-gifts).          &#x20;

Um das automatische Hinzufügen von Geschenk(en) zum Warenkorb einzurichten, wählen Sie **„Alle Geschenke automatisch hinzufügen“** bei der Einrichtung des Geschenkangebots.

<figure><img src="../../.gitbook/assets/unknown (225).png" alt=""><figcaption></figcaption></figure>

_**Hinweis**_:&#x20;

* Bitte stellen Sie sicher, dass die Option **„Geschenk automatisch zum Warenkorb hinzufügen“** aktiviert ist. Um dies zu überprüfen, gehen Sie zu Einstellungen → Geschenkbedingung.&#x20;

<figure><img src="../../.gitbook/assets/unknown (226).png" alt=""><figcaption></figcaption></figure>

* Deaktivieren Sie das Kontrollkästchen **„Geschenk automatisch zum Warenkorb hinzufügen“**, wenn Sie Geschenk(e) immer in einem Geschenk-Slider anzeigen möchten.

Wenn Kunden ein Geschenk aus einem Geschenk-Slider auswählen sollen, aktivieren Sie „**Anzahl der Geschenke, die der Kunde erhält**“ und geben Sie eine Zahl ein, die kleiner ist als die Anzahl der ausgewählten Geschenke.&#x20;

**Schritt 3:** Aktivieren Sie das Geschenkangebot auf **Tapcart**&#x20;

* Gehen Sie in **BOGOS** zu **Einstellungen**.
* Scrollen Sie nach unten zu **Geschenkprodukt klonen** und klicken Sie auf **Verkaufskanäle bearbeiten**.
* Aktivieren Sie **Tapcart - Mobile App** und klicken Sie dann auf **Fertig**.

<figure><img src="../../.gitbook/assets/unknown (227).png" alt=""><figcaption></figcaption></figure>

**Schritt 4:** Fügen Sie den BOGOS Gift Slider und den BOGOS Core in **Tapcart** hinzu

* Gehen Sie in Tapcart zum Bereich **App Studio** und wählen Sie **My Blocks**.
* Öffnen Sie die **Legacy Custom Blocks**
* Ziehen Sie die **BOGOS Blocks** per Drag-and-drop.

**BOGOS CORE**: Ziehen Sie ihn für eine bessere Leistung auf die **Startseite** oder die **Warenkorbseite**.   &#x20;

**BOGOS - Gift Slider:** Ziehen Sie ihn auf die **Warenkorbseite** oder an eine andere Stelle, an der Kunden den Geschenk-Slider sehen sollen.

<figure><img src="../../.gitbook/assets/unknown (228).png" alt=""><figcaption></figcaption></figure>

**Schritt 5:** Fügen Sie BOGOS-Geschenkprodukte zu **Tapcart** hinzu

* Gehen Sie in **Shopify** zu **Produkte**.
* Wählen Sie alle Geschenkprodukte aus den BOGOS-Angeboten aus.&#x20;

_**Hinweis:**_ Um Geschenkprodukte zu finden, gehen Sie zum Tab **Suchen & Filtern**, wählen Sie **Tag** und dann „**bogos-gift**“ aus.&#x20;

* Klicken Sie auf das „…“-Symbol und wählen Sie In Verkaufskanäle aufnehmen.
* Wählen Sie **Tapcart** aus und klicken Sie auf **Produkte aufnehmen**.

<figure><img src="../../.gitbook/assets/unknown (229).png" alt=""><figcaption></figcaption></figure>

**Schritt 6:** Testen Sie Ihre Angebote auf **Tapcart**, um sicherzustellen, dass alles reibungslos funktioniert

#### Geschenkangebot nur im Mobile-App-Kanal ausführen

Mit dieser Funktion erstellen Sie Geschenkangebote, die ausschließlich in der Mobile App verfügbar sind, das heißt, sie sind nur beim Einkauf über die Mobile-App-Version verfügbar.

So richten Sie dies ein:

* Öffnen Sie die BOGOS App > Erstellen Sie ein neues oder wählen Sie ein bestehendes Geschenkangebot aus.
* Fügen Sie **Unterbedingung des Angebots** hinzu > Fügen Sie **Mobile-App-Kanal** hinzu
* Klicken Sie auf **Ihr Angebot veröffentlichen**

<figure><img src="../../.gitbook/assets/unknown (230).png" alt=""><figcaption></figcaption></figure>

_**Hinweis:**_ Andere Unterbedingungen funktionieren in der Mobile App nicht.

Geschenkbestand in der Mobile App verwalten

Beim Gift-Clone-Mechanismus richtet sich die Geschenkmenge nach der Konfiguration in Ihren Einstellungen:

* Menge der geklonten Produkte automatisch mit den Originalen synchronisieren – Die Geschenkmenge in der Mobile App bleibt mit dem Lagerbestand des Originalprodukts synchronisiert.
* Geschenkproduktbestand manuell eingeben – Sie können die Geschenkmenge unabhängig vom Originalprodukt manuell steuern.

<figure><img src="../../.gitbook/assets/unknown (231).png" alt=""><figcaption></figcaption></figure>

<br>
