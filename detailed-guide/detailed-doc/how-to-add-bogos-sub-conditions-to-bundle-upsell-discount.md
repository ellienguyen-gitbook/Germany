---
description: >-
  Learn how to use advanced sub-conditions with Bundles, Upsells, and Discounts
  to target the right customer segments.
---

# Wie fügt man BOGOS-Unterbedingungen zu Bundle, Upsell, Rabatt hinzu?

Insgesamt fügen Unterbedingungen **zusätzliche Regeln hinzu, um zu entscheiden, wer Ihre Angebote sehen und erhalten kann**. Dadurch können nur die angesprochenen Kunden das Angebot sehen und anwenden, während andere es überhaupt nicht sehen.

<figure><img src="../../.gitbook/assets/unknown (148).png" alt="" width="503"><figcaption></figcaption></figure>

{% hint style="info" %}
* Diese Unterbedingungen sind optional. Wenn Sie keine hinzufügen, ist das Angebot für alle Kunden verfügbar.
* Sie können mehrere Unterbedingungen in einem Angebot kombinieren. Kunden müssen alle davon erfüllen, um für Ihr Angebot qualifiziert zu sein.
{% endhint %}

### Übersicht der Funktionsliste

Sehen Sie sich diese Funktionsliste an, um zu verstehen, welche Unterbedingungen für jeden Angebotstyp verfügbar sind, bevor Sie Ihre Aktion einrichten:

<figure><img src="../../.gitbook/assets/image (430).png" alt=""><figcaption></figcaption></figure>

_**\*Upsell-Auslöser:** Legen Sie diese Bedingungen im Upsell-Auslöser → Kundenauslöser in der Einrichtung von_ [_Checkout-Upsell_](../upsell-offer/create-checkout-upsell.md#id-2.4-customer-trigger) _oder_ [_Danke-Seite-Upsell_](../upsell-offer/create-thank-you-page-upsell.md#customer-trigger) _fest, nicht im Bereich der Unterbedingungen._

### 1. Spezifische Linkadresse

Diese Bedingung erlaubt nur Kunden, die Ihren Shop über einen bestimmten Link aufrufen, Ihre Angebote zu erhalten. Verwenden Sie dies für E-Mail-Kampagnen, Social-Media-Beiträge oder Influencer-Partnerschaften, um bestimmte Traffic-Quellen anzusprechen.

<figure><img src="../../.gitbook/assets/unknown (149).png" alt=""><figcaption></figcaption></figure>

_**Eine spezifische Linkadresse für ein Angebot erstellen:**_

1. _Wählen Sie ein Linkziel:_ Wählen Sie aus, wo Kunden landen sollen (Startseite, Sammlungsseite oder Produktseite).
2. _Geben Sie ein anzupassendes Wort ein_ (z. B. summersale2024): Dies erstellt einen eindeutigen Link für Ihre Kampagne.
3. _Kopieren Sie den generierten Link:_ Kopieren und teilen Sie diesen Link in Ihren Marketingkampagnen. Kunden, die über diesen Link auf Ihren Shop zugreifen, erhalten Ihre Angebote.

_**Mehrere Linkziele für ein Angebot erstellen:**_

Wenn Sie mehrere Linkziele haben möchten (nicht nur das oben ausgewählte), zum Beispiel wenn Ihre Kampagne mehrere Produkte bewirbt und Sie möchten, dass Kunden über verschiedene Produktlinks einsteigen, um Ihr Angebot zu erhalten, folgen Sie diesen Schritten:

1. _Wiederholen Sie die Schritte_ zur Erstellung einer spezifischen Linkadresse für ein Angebot
2. _**Kopieren Sie den Parameter**_ und fügen Sie ihn am Ende jedes Links hinzu.

{% hint style="info" %}
Wenn Ihre URL bereits ein „?“-Symbol enthält, **ändern Sie das „?“ im Parameter in „&“.** Beispiele:

* Ursprüngliche URL mit „?“: https://yourstore.com/product?variant=12345
* URL mit korrektem Parameter: https://yourstore.com/product?variant=1234&#x35;**&**&#x66;reegifts\_code=summersale2024
* URL mit falschem Parameter: https://yourstore.com/product?variant=1234&#x35;**?**&#x66;reegifts\_code=summersale2024
{% endhint %}

### 2. Bestellhistorie der Kunden

Diese Unterbedingung spricht Kunden basierend auf ihrer Kaufhistorie an. Nur Kunden, die die von Ihnen festgelegten Bestellanforderungen erfüllen, sind für das Angebot qualifiziert.

{% hint style="info" %}
Diese Unterbedingung erfordert, dass Kunden sich in Ihrem Shop anmelden.
{% endhint %}

<figure><img src="../../.gitbook/assets/unknown (150).png" alt="" width="426"><figcaption></figcaption></figure>

1. **Wählen Sie, ab wann die Bestellung erstellt wurde:** Legen Sie einen Datumsbereich fest, um die unten ausgewählten Bedingungen innerhalb dieses Zeitraums anzuwenden, oder lassen Sie es leer, um sie über den gesamten Zeitraum anzuwenden.
2. **Wählen Sie die Bedingungen aus, die Sie anwenden möchten:**

* _Gesamtausgaben in der Bestellhistorie:_ Sprechen Sie Kunden basierend auf ihren Gesamtausgaben in Ihrem Shop an (z. B. Belohnung für ausgabefreudige VIP-Kunden).
* _Gesamtausgaben der letzten Bestellung:_ Sprechen Sie Kunden basierend auf dem Wert ihrer letzten Bestellung an (z. B. Kunden mit geringen Ausgaben).
* _Gesamtanzahl aufgegebener Bestellungen:_ Sprechen Sie Kunden basierend auf der Anzahl ihrer Bestellungen an (z. B. Erstkäufer oder Stammkunden).
* _Anzahl der Nutzungen pro Kunde begrenzen:_ Legen Sie fest, wie oft jeder Kunde das Angebot nutzen kann. Nach Erreichen des Limits qualifizieren sie sich nicht erneut.

### 3. Kundentags

Mit dieser Unterbedingung können Sie steuern, wer ein Angebot erhalten kann, basierend auf den von Ihnen eingerichteten Kundentags, wie z. B. VIP, Großhandel oder Kunden mit geringen Ausgaben.

{% hint style="info" %}
* Kundentags müssen in Ihrem Shopify-Admin unter Kunden eingerichtet werden, bevor sie in BOGOS verwendet werden können.
* Diese Unterbedingung erfordert, dass Kunden sich in Ihrem Shop anmelden.
{% endhint %}

<figure><img src="../../.gitbook/assets/unknown (151).png" alt=""><figcaption></figcaption></figure>

_**▶ So zeigen Sie Angebote für bestimmte Kundentags an:**_

1. _Tags auswählen:_ Geben Sie die Kundentags ein, die Sie ansprechen möchten (z. B. VIP, Großhandel, Kunden mit geringen Ausgaben).
2. BOGOS wendet das Angebot nur auf Kunden an, deren Konten mit diesen Tags übereinstimmen.

_**▶ So schließen Sie Angebote für bestimmte Kundentags aus:**_

1. _Tags auswählen:_ Geben Sie die Kundentags ein, die Sie ausschließen möchten (z. B. VIP, Großhandel, Kunden mit geringen Ausgaben).
2. _Kunden mit diesen Tags ausschließen:_ Kunden mit den ausgewählten Tags erhalten das Angebot nicht. Das Angebot gilt für alle anderen angemeldeten Kunden.
3. _Nicht angemeldete Nutzer als Kunden ohne Tags betrachten (empfohlen):_ Aktivieren Sie dies, um **auch nicht angemeldeten** Kunden zu erlauben, das Angebot zu erhalten.

### 4. Kundenstandort

Mit dieser Unterbedingung können Sie steuern, wer ein Angebot erhalten kann, basierend auf dem Standort des Kunden, sodass Sie standortspezifische Aktionen durchführen können.

{% hint style="info" %}
Wenn Sie Shopify Markets eingerichtet haben und Angebote darauf anwenden möchten, verwenden Sie stattdessen die [Markets-Unterbedingung](how-to-add-bogos-sub-conditions-to-bundle-upsell-discount.md#id-5.-markets).
{% endhint %}

<figure><img src="../../.gitbook/assets/unknown (152).png" alt=""><figcaption></figcaption></figure>

▶ **So zeigen Sie Angebote für bestimmte Standorte an:**<br>

1. _Standort auswählen:_ Wählen Sie ein oder mehrere Länder aus, in denen das Angebot gelten soll (z. B. Frankreich).
2. _BOGOS prüft_ die **IP-Adresse des Kunden** und wendet das Angebot nur an, wenn dessen Land mit den ausgewählten Standorten übereinstimmt.

**▶ So schließen Sie Angebote für bestimmte Standorte aus:**

1. _Standort auswählen:_ Wählen Sie die Länder aus, die Sie ausschließen möchten (z. B. Frankreich).
2. _Kunden von ausgewählten Standorten ausschließen:_ Verhindern Sie, dass Kunden aus ausgewählten Standorten das Angebot erhalten. Das Angebot gilt stattdessen für Kunden aus allen anderen Standorten.

### 5. Markets

Diese Unterbedingung synchronisiert sich mit Ihrer Shopify-Markets-Einrichtung, um zu entscheiden, welche Kunden ein Angebot erhalten können.

{% hint style="info" %}
Shopify Markets muss in Ihrem Shopify-Admin eingerichtet werden, bevor es in BOGOS verwendet werden kann.
{% endhint %}

<figure><img src="../../.gitbook/assets/unknown (153).png" alt=""><figcaption></figcaption></figure>

**▶ So zeigen Sie Angebote für bestimmte Märkte an:**

1. _Märkte auswählen:_ Wählen Sie einen oder mehrere Shopify Markets aus (zum Beispiel: Europa, Asien).

**▶ So schließen Sie Angebote für bestimmte Märkte aus:**

1. _Märkte auswählen:_ Wählen Sie die Märkte aus, die Sie ausschließen möchten (zum Beispiel: Europa, Asien).
2. _Kunden von ausgewählten Märkten ausschließen:_ Aktivieren Sie dies, um zu verhindern, dass Kunden aus den ausgewählten Märkten das Angebot erhalten. Das Angebot gilt stattdessen für Kunden aus allen anderen Märkten.
