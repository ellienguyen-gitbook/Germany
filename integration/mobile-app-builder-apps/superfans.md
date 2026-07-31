# Superfans

{% embed url="https://youtu.be/0KbAk1bzALk?si=Zyvot70_HsUNLS0a" %}

[**Superfans**](https://apps.shopify.com/vajro?utm_source=partner\&utm_medium=BOGOS\&utm_campaign=integration_helpdoc) ist ein No-Code-Mobile-App-Builder für Shopify- und Shopify-Plus-Marken, der entwickelt wurde, um mobile Käufer über native iOS- und Android-Apps in treue Kunden zu verwandeln. Mit seinem intuitiven Builder und leistungsstarken Engagement-Tools ermöglicht Superfans es Händlern, schnelle, ansprechende und conversion-starke mobile Einkaufserlebnisse zu bieten.

Durch die Integration zwischen [BOGOS](https://apps.shopify.com/freegifts?utm_source=gitbook\&utm_medium=integration\&utm_campaign=Superfans) und [Superfans](https://apps.shopify.com/vajro?utm_source=partner\&utm_medium=BOGOS\&utm_campaign=integration_helpdoc) können Sie Geschenkaktionen ganz einfach über ein einziges Dashboard erstellen, verwalten und in Ihrer mobilen App anzeigen.&#x20;

**Superfans Hauptfunktionen:**

* No-Code-Mobile-App-Builder – Erstellen Sie native iOS- und Android-Apps mit einer einfachen Drag-and-Drop-Oberfläche
* Unbegrenzte Push-Benachrichtigungen – Senden Sie gezielte mobile Benachrichtigungen an bestimmte Kundensegmente.
* One-Click-Integrationen – Verbinden Sie Ihre bestehenden Shopify-Apps und Ihren Tech-Stack nahtlos.
* Live-Selling-Funktionen – Veranstalten Sie Live-Sessions in Ihrer mobilen App und auf Facebook, um Käufer einzubinden und mehr Verkäufe zu erzielen.

_**Hinweis:**_ Geschenkangebote funktionieren in der mobilen App nur, wenn der Geschenkmechanismus auf Gift Clone eingestellt ist.

So konfigurieren Sie dies:

* Gehen Sie zu BOGOS → Einstellungen.
* Suchen Sie den Geschenklogik-Mechanismus und wählen Sie dann Clone product aus.

<figure><img src="../../.gitbook/assets/unknown (177).png" alt=""><figcaption></figcaption></figure>

## So integrieren Sie BOGOS mit Superfans

**Schritt 1:** Installieren Sie [BOGOS](https://apps.shopify.com/freegifts?utm_source=gitbook\&utm_medium=integration\&utm_campaign=Superfans) und [Superfans](https://apps.shopify.com/vajro?utm_source=partner\&utm_medium=BOGOS\&utm_campaign=integration_helpdoc) aus dem Shopify App Store&#x20;

**Schritt 2:** Richten Sie Geschenkangebote in der BOGOS-App ein

Um das automatische Hinzufügen von Geschenk(en) zum Warenkorb einzurichten, prüfen Sie, ob Sie die Einstellung „Geschenk automatisch zum Warenkorb hinzufügen“ unter Einstellungen → Geschenkbedingung aktiviert haben.

<figure><img src="../../.gitbook/assets/unknown (178).png" alt=""><figcaption></figcaption></figure>

Wählen Sie beim Erstellen des Angebots „Alle Geschenke automatisch hinzufügen“ aus.

<figure><img src="../../.gitbook/assets/unknown (179).png" alt=""><figcaption></figcaption></figure>

Weitere Details finden Sie in der Anleitung [Geschenkangebot erstellen](https://bogos-guideline.gitbook.io/user-guide/detailed-guide/gift-offer/create-gift-offer#id-4.-select-gifts).          &#x20;

**Schritt 3:** Aktivieren Sie die BOGOS-Integration in Superfans

* Navigieren Sie in Superfans zu Plugins.&#x20;
* Suchen Sie BOGOS und klicken Sie auf Details anzeigen oder aktivieren Sie den Schalter.

<figure><img src="../../.gitbook/assets/unknown (180).png" alt=""><figcaption></figcaption></figure>

* Geben Sie Ihren BOGOS-API-Schlüssel ein (kontaktieren Sie das BOGOS-Support-Team, um diesen Schlüssel zu erhalten).
* Klicken Sie dann auf Speichern und Plugin aktivieren.

<figure><img src="../../.gitbook/assets/unknown (181).png" alt=""><figcaption></figcaption></figure>

**Schritt 4:** Fügen Sie BOGOS Gift Slider und BOGOS Core in Superfans hinzu

* Gehen Sie in Superfans zum Bereich Themes und öffnen Sie das Theme Ihres Shops.
* Öffnen Sie die Warenkorbseite.
* Klicken Sie auf Block hinzufügen → Plugin.

<figure><img src="../../.gitbook/assets/unknown (182).png" alt=""><figcaption></figcaption></figure>

* Fügen Sie die folgenden Blöcke hinzu: **BOGOS Gift Slider** & **BOGOS Core**

<figure><img src="../../.gitbook/assets/unknown (183).png" alt=""><figcaption></figcaption></figure>

**Schritt 5:** Fügen Sie BOGOS-Geschenkprodukte zu Superfans hinzu

* Gehen Sie in Shopify zu Produkte.
* Wählen Sie alle Geschenkprodukte aus den BOGOS-Angeboten aus.
* Klicken Sie auf das Symbol „…“ und wählen Sie In Verkaufskanäle aufnehmen.
* Wählen Sie Superfans aus und klicken Sie auf Produkte aufnehmen.

<figure><img src="../../.gitbook/assets/unknown (184).png" alt=""><figcaption></figcaption></figure>

**Schritt 6:** Testen Sie Ihre Angebote in Superfans, um sicherzustellen, dass alles reibungslos funktioniert

#### Geschenkangebot nur im Mobile-App-Kanal ausführen

Diese Funktion erstellt Geschenkangebote, die ausschließlich in der mobilen App verfügbar sind, das heißt, sie sind nur beim Kauf über die mobile App-Version des Shops verfügbar.

**So richten Sie es ein:**

* Öffnen Sie die BOGOS-App > Erstellen Sie ein neues Geschenkangebot oder wählen Sie ein bestehendes aus.
* Fügen Sie eine Unterbedingung des Angebots hinzu > Fügen Sie Mobile app channel hinzu
* Klicken Sie auf Ihr Angebot veröffentlichen

<figure><img src="../../.gitbook/assets/unknown (188).png" alt=""><figcaption></figcaption></figure>

_Hinweis: Andere Unterbedingungen funktionieren **nicht** in der mobilen App._

#### Geschenkbestand in der mobilen App verwalten

Beim Gift Clone-Mechanismus richtet sich die Geschenkmenge nach der Konfiguration in Ihren Einstellungen:

* Menge der Klonprodukte automatisch mit den Originalen synchronisieren – Die Geschenkmenge in der mobilen App bleibt mit dem Lagerbestand des Originalprodukts synchronisiert.
* Geschenkprodukt-Lagerbestand manuell eingeben – Sie können die Geschenkmenge unabhängig vom Originalprodukt manuell steuern.

<figure><img src="../../.gitbook/assets/unknown (187).png" alt=""><figcaption></figcaption></figure>
