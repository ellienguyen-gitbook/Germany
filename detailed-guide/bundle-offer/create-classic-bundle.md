---
description: Ein Überblick über die Erstellung eines Classic Bundles
---

# Classic Bundle erstellen

<figure><img src="../../.gitbook/assets/unknown (6).png" alt=""><figcaption></figcaption></figure>

{% embed url="https://youtu.be/xormwYiFkRM?si=n72-y7a_tjnkEIxt" %}

### 1. Bundle-Informationen

<figure><img src="../../.gitbook/assets/image (368).png" alt=""><figcaption></figcaption></figure>

#### 1.1 Bundle-Name

Dieser Name dient nur der internen Verwaltung und wird Kunden nicht angezeigt.

#### 1.2 Bundle-Titel

Der Bundle-Titel ist der Name des Bundles. Er wird oben im Bundle als Blockkopfzeile angezeigt.

#### 1.3 Bundle-Beschreibung&#x20;

Die Bundle-Beschreibung gibt Kunden weitere Informationen zum angebotenen Deal. Dieses Feld ist optional.&#x20;

#### 1.4 Startzeit und Endzeit&#x20;

* **Startzeit:** Der Zeitpunkt, ab dem das Bundle im Onlineshop und auf der Produktseite aktiv und für Kunden sichtbar wird&#x20;
* **Endzeit:** Der Zeitpunkt, ab dem das Bundle im Onlineshop und auf der Produktseite deaktiviert wird. Lassen Sie dieses Feld leer, damit das Bundle dauerhaft aktiv bleibt.&#x20;

#### 1.5. Countdown-Timer anzeigen (optional)

Aktivieren Sie einen Countdown-Timer im Widget, um Kunden zum Kauf vor Ablauf des Angebots zu motivieren.

* Diese Option ist standardmäßig deaktiviert. Sie wird verfügbar, sobald Sie eine Endzeit festlegen oder die wiederkehrende Zeit aktivieren.
* Ohne wiederkehrende Zeit läuft der Countdown basierend auf der Endzeit.
* Wenn eine wiederkehrende Zeit festgelegt ist, läuft der Countdown basierend auf der Endzeit jeder wiederkehrenden Sitzung (in Tagen).

#### 1.6. Wiederkehrende Zeit (optional)

Aktivieren Sie das Angebot nach einem wiederkehrenden Zeitplan innerhalb seines Aktivitätszeitraums – ideal für tägliche Blitzverkäufe, Wochenend-Aktionen oder monatliche Kampagnen. Wenn aktiviert, wird die Endzeit des Aktivitätszeitraums automatisch mit dem Enddatum der Wiederholung synchronisiert.

Zum Einrichten konfigurieren Sie Folgendes:

**1.6.1. Häufigkeit**

Wählen Sie, wie oft sich das Angebot wiederholt: Täglich, Wöchentlich oder Monatlich.

* **Täglich:** Das Angebot läuft jeden Tag innerhalb des gewählten Zeitfensters.

<figure><img src="../../.gitbook/assets/image (435).png" alt=""><figcaption></figcaption></figure>

* **Wöchentlich:** Das Angebot läuft an ausgewählten Wochentagen.&#x20;

<figure><img src="../../.gitbook/assets/image (437).png" alt=""><figcaption></figcaption></figure>

* **Monatlich:** Das Angebot läuft an einem bestimmten Tag jeden Monats. Wenn Sie Tag 29, 30 oder 31 auswählen, wiederholt sich das Angebot am letzten Tag des Monats, falls dieses Datum nicht existiert.

<figure><img src="../../.gitbook/assets/image (441).png" alt=""><figcaption></figcaption></figure>

**1.6.2. Startzeit (in Tagen) / Endzeit (in Tagen)**

Das tägliche Zeitfenster, in dem das Angebot während jeder wiederkehrenden Sitzung aktiv ist (z. B. 09:00 bis 11:00 Uhr). Die Zeiten werden entsprechend der aktuellen Zeitzone Ihres Shops eingestellt.

**1.6.3. Wiederholung beenden, wenn**

Wählen Sie, wann die Wiederholung endet.

* **Kein Enddatum:** Das Angebot wiederholt sich weiter, bis Sie es manuell deaktivieren.
* **Am Datum:** Das Angebot endet an einem bestimmten Datum. Wenn Sie bereits eine Endzeit festgelegt haben, wird dieses Feld standardmäßig auf dieses Datum gesetzt, Sie können es aber weiterhin ändern.
* **Nach N-mal:** Das Angebot endet, nachdem es eine festgelegte Anzahl von Malen gelaufen ist.

{% hint style="warning" %}
Wenn ein Angebot mit aktivierter wiederkehrender Zeit erstellt wird, erscheint es mit dem Status „Geplant“, damit Sie kommende Durchläufe verfolgen können.&#x20;
{% endhint %}

{% hint style="warning" %}
Wenn ein Angebot abläuft, während sich ein Kunde noch im Checkout-Prozess befindet, wird der Rabatt automatisch entfernt und die Produkte werden zum ursprünglichen Preis berechnet.&#x20;
{% endhint %}

### 2. Unterbedingungen hinzufügen

Unterbedingungen fügen zusätzliche Regeln hinzu, um zu entscheiden, wer Ihre Angebote sehen und erhalten kann. Dadurch können nur die gezielten Kunden das Angebot sehen und anwenden, während andere es überhaupt nicht sehen.

{% hint style="info" %}
* Diese Unterbedingungen sind optional. Wenn Sie keine hinzufügen, ist das Angebot für alle Kunden verfügbar.
* Sie können mehrere Unterbedingungen kombinieren. Kunden müssen alle ausgewählten Kriterien erfüllen, um qualifiziert zu sein.
{% endhint %}

<figure><img src="../../.gitbook/assets/unknown (154).png" alt="" width="503"><figcaption></figcaption></figure>

1. _Spezifische Link-Adresse_ – Wenden Sie Angebote auf Kunden an, die über einen bestimmten Link auf Ihren Shop zugreifen. Perfekt für E-Mail-Kampagnen, Social-Media-Beiträge oder Affiliates.
2. _Bestellverlauf_ – Zielen Sie auf Kunden basierend auf ihrem Kaufverhalten. Ideal, um Erstkäufer, Vielkäufer und mehr zu belohnen.
3. _Kundentags_ – Angebote basierend auf Kundentags anzeigen oder ausblenden.
4. _Kundenstandort_ – Führen Sie länderspezifische Werbeaktionen basierend auf der IP-Adresse des Kunden durch.
5. _Märkte_ – Führen Sie regionsspezifische Angebote basierend auf Ihren Shopify Markets durch.

♦️ Weitere Details finden Sie in unserem \[[Unterbedingungen](../detailed-doc/how-to-add-bogos-sub-conditions-to-bundle-upsell-discount.md)]-Leitfaden.

### 3. Bundle auswählen

#### 3.1 Bundle-Artikelebene:

Wählen Sie, wie jeder Artikel im Bundle gezählt wird.

* **Produktebene:** Jedes Produkt zählt als ein Bundle-Artikel. Das Widget zeigt jedes Produkt als einzelne Zeilenposition an, mit der Option, die bevorzugte Variante auszuwählen.

<figure><img src="../../.gitbook/assets/unknown (7).png" alt=""><figcaption></figcaption></figure>

* **Variantenebene:** Jede Variante zählt als ein Bundle-Artikel und wird als separate Zeilenposition im Widget angezeigt.

<figure><img src="../../.gitbook/assets/unknown (8).png" alt=""><figcaption></figcaption></figure>

#### 3.2 Bundle-Rabattart

Es stehen Ihnen zwei separate Optionen zur Einrichtung Ihrer Werbekampagnen zur Verfügung.

<figure><img src="../../.gitbook/assets/image (291).png" alt=""><figcaption></figcaption></figure>

**4 Rabattarten**

* Prozentsatz: Ein Prozentsatz des Rabatts wird vom Gesamtpreis aller Produkte im Bundle abgezogen.
* Betrag: Ein Geldbetrag wird vom Gesamtpreis aller Produkte im Bundle abgezogen.&#x20;
* Festpreis: Für alle Produkte im Bundle wird ein bestimmter Preis festgelegt.
* Gratisgeschenk: ein kostenloser Artikel, der automatisch zu den Warenkörben der Kunden hinzugefügt wird, die die Bedingung erfüllen

**Versandrabatt**

<figure><img src="../../.gitbook/assets/unknown (111).png" alt=""><figcaption></figcaption></figure>

Es gibt 2 Arten von Versandrabatt:

* Prozentsatz: Ein Prozentsatz der Versandkosten wird abgezogen.
* Betrag: Ein fester Betrag wird von den gesamten Versandkosten abgezogen.

**Beschriftung auf dem Widget:** Dieser Text informiert Kunden darüber, ob das Bundle einen Versandrabatt enthält.&#x20;

**Währung hinzufügen:** Wenn Sie Shopify Markets eingerichtet haben, können Sie anpassen, wie viel Rabattbetrag Sie in jeder Währung anbieten möchten, anstatt Shopifys Wechselkurse zu verwenden (z. B. SGD 10, CN¥8, A$12).

<figure><img src="../../.gitbook/assets/image (377).png" alt="" width="506"><figcaption></figcaption></figure>

### 4. Ein Produkt für dieses Bundle erstellen (optional)

Wenn aktiviert, erhält das Bundle eine **eigene Produktseite** (Bundle als Produkt) – zusätzlich zur Anzeige eines Classic-Bundle-Widgets auf den Produktseiten.

{% hint style="info" %}
Aufgrund der Shopify-Regeln darf ein Bundle-Produkt nicht mehr als 30 gebündelte Produkte, 3 Optionen und 100 Varianten enthalten.
{% endhint %}

<figure><img src="../../.gitbook/assets/unknown (9).png" alt=""><figcaption></figcaption></figure>

**So richten Sie es ein:**

1. Aktivieren Sie „**Ein Produkt für dieses Bundle erstellen**“

<figure><img src="../../.gitbook/assets/unknown (10).png" alt=""><figcaption></figcaption></figure>

2. Bearbeiten Sie den **Titel** & die **Beschreibung** des Bundles.
3. Wählen Sie den **Status** des Bundle-Produkts aus (aktiv, Entwurf, nicht gelistet)
4. **Bilder von Bundle-Artikeln synchronisieren** (optional): Zeigt automatisch das Hauptbild jedes gebündelten Produkts im Storefront an.
5. **Bundle-Produkt beim Deaktivieren dieses Bundles löschen** (optional): Löscht dieses Bundle-Produkt automatisch aus Ihrem Shopify-Shop, wenn dieses Classic-Bundle-Angebot in der BOGOS-App deaktiviert wird.

**Nach der Veröffentlichung des Angebots** können Sie zum Einrichtungsbildschirm zurückkehren, um das Bundle-Produkt schnell zu verwalten:

* **Details bearbeiten:** Bearbeiten Sie schnell Produktdetails wie Kategorie, Lagerbestand und Vertriebskanäle.

<figure><img src="../../.gitbook/assets/unknown (11).png" alt=""><figcaption></figcaption></figure>

* **Informationen synchronisieren:** Wenn Sie das Bundle-Produkt direkt im Shopify-Adminbereich bearbeitet haben, klicken Sie hier, um die neuesten Shopify-Daten zurück in die BOGOS-App zu synchronisieren.
* **Produkt löschen:** Löschen Sie das Bundle-Produkt schnell aus Shopify. Dadurch wird das Classic-Bundle-Angebot selbst nicht gelöscht.

### 5. Rabattcode

#### Einen benutzerdefinierten Rabattcode hinzufügen

In diesem Abschnitt können Sie den Namen des Rabattcodes an Ihre Marke anpassen.

<figure><img src="../../.gitbook/assets/image (321).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" icon="triangle-exclamation" %}
Der Name des Rabattcodes muss unter 256 Zeichen liegen und über alle Shopify-Rabatte hinweg eindeutig sein.
{% endhint %}

### 6. Kombination

Standardmäßig funktionieren BOGOS-Bundles mit allen anderen Rabatten zusammen. Deaktivieren Sie jedes Kontrollkästchen, um die Kombination mit anderen Rabatten zu deaktivieren.&#x20;

* Bestellrabatte: Rabatt auf Bestellebene
* Versandrabatt

### FAQs

<details>

<summary><strong>Wie verfolgt das Bundle als Produkt (erstellt mit „Ein Produkt für dieses Bundle erstellen“ im Classic Bundle) den Lagerbestand?</strong></summary>

Wenn ein Bundle gekauft wird, wird der Lagerbestand von jedem gebündelten Artikel (z. B. jedem T-Shirt) abgezogen, um genaue Lagerbestände und einen reibungslosen Versand sicherzustellen.

![](<../../.gitbook/assets/unknown (12).png>)

</details>

<details>

<summary><strong>Kann das Bundle als Produkt (erstellt mit „Ein Produkt für dieses Bundle erstellen“ im Classic Bundle) in Shopify und BOGOS Analytics nachverfolgt werden?</strong></summary>

Aufgrund von Shopify-Einschränkungen werden Bestellungen mit diesem Bundle-Produkt nicht in Shopify Analytics erfasst.

Sie können die Performance jedoch weiterhin in BOGOS Analytics mit einer klaren Trichteransicht verfolgen, wie sie konvertiert.

![](<../../.gitbook/assets/unknown (13).png>)

</details>

<details>

<summary><strong>Kann ich einen Classic-Bundle-Rabatt mit anderen Shopify-Rabattcodes kombinieren?</strong></summary>

Standardmäßig ermöglicht BOGOS die Kombination von Bundle-Rabatten mit Bestellrabatten und Versandrabatten. Sie können diese Funktion jedoch im Abschnitt „**Kombination**“ der Einstellungen deaktivieren.

Wenn sowohl ein Classic-Bundle-Rabatt als auch ein Shopify-Rabatt für dieselben Produkte gelten, wendet Shopify nur den höchsten Rabattcode an.

</details>

<details>

<summary><strong>Kann ich den Rabattcode meines Bundles an meine eigene Kampagne anpassen?</strong></summary>

Ja, Sie können den **Namen des Rabattcodes** (bis zu **256 Zeichen**) anpassen, um ihn besser an Ihre Marke anzupassen, indem Sie im Angebot zum Rabattcode gehen > Einen benutzerdefinierten Rabattcode hinzufügen ankreuzen.

![](<../../.gitbook/assets/unknown (1).png>)

</details>

<details>

<summary><strong>Ich habe das Classic Bundle aktiviert, sehe es aber nicht. Wo wird es angezeigt?</strong></summary>

Standardmäßig erscheint das Bundle-Widget auf den Produktseiten jedes einzelnen im Bundle enthaltenen Artikels.

**Um es sichtbar zu machen, führen Sie bitte diese Schritte aus:**&#x20;

Schritt 1: Gehen Sie zu Shopify-Adminbereich > Onlineshop > Themes > Theme bearbeiten > Produktseite

![](<../../.gitbook/assets/unknown (2).png>)

Schritt 2: Fügen Sie im Bereich Produktinformationen den Classic-Bundle-Block von BOGOS hinzu

![](<../../.gitbook/assets/unknown (3).png>)

Schritt 3: Klicken Sie auf die Schaltfläche „Speichern“

</details>
