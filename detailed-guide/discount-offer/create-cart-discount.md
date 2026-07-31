# Warenkorbrabatt erstellen

Ein Warenkorbrabatt belohnt Kunden mit **einem Rabatt auf ihren gesamten Warenkorb**, wenn sie einen **bestimmten Ausgabenwert oder eine Produktmengen-Schwelle** erreichen, und motiviert Kunden so, mehr und mehr auszugeben.

<figure><img src="../../.gitbook/assets/image (410).png" alt=""><figcaption></figcaption></figure>

**Die Einrichtung eines Warenkorbrabatt-Angebots mit der** [**BOGOS-App**](https://apps.shopify.com/freegifts?utm_source=HelpDoc\&utm_medium=CartDiscount\&utm_campaign=Create) **umfasst 9 Schritte:**

{% stepper %}
{% step %}
Öffnen Sie im Menü „Alle Angebote“ > „Angebote erstellen“ > „Rabattangebot“ > „Warenkorbrabatt“.
{% endstep %}

{% step %}
[Richten Sie die Angebotsinformationen ein.](create-cart-discount.md#set-up-offer-information)
{% endstep %}

{% step %}
[Legen Sie fest, für welche Produkte das Angebot gilt.](create-cart-discount.md#define-offers-apply-to-which-products)
{% endstep %}

{% step %}
[Richten Sie die maximale Anzahl an Rabattnutzungen ein](create-cart-discount.md#set-up-maximum-discount-uses) (optional).
{% endstep %}

{% step %}
[Fügen Sie Unterbedingungen hinzu](create-cart-discount.md#add-sub-conditions) (optional).
{% endstep %}

{% step %}
[Richten Sie Rabatte & Stufen ein.](create-cart-discount.md#set-up-discounts-and-tiers)
{% endstep %}

{% step %}
[Benutzerdefinierter Rabattcode](create-cart-discount.md#custom-discount-code) & [Rabattkombination](create-cart-discount.md#combine-with-other-discounts) (optional).
{% endstep %}

{% step %}
Klicken Sie auf „Veröffentlichen“.
{% endstep %}

{% step %}
Passen Sie die [Widget-Anzeige](../customize/customize-cart-discount.md#id-1.-customize-product-page-widget) & [Glückwunschnachricht](../customize/customize-cart-discount.md#id-2.-customize-congrats-message) an.
{% endstep %}
{% endstepper %}

{% embed url="https://www.youtube.com/watch?v=n33xNlhbvDg" %}

### 1. Angebotsinformationen einrichten

Dieser Abschnitt legt die grundlegenden Informationen für Ihr Warenkorbrabatt-Angebot fest.

<figure><img src="../../.gitbook/assets/unknown (57).png" alt=""><figcaption></figcaption></figure>

Füllen Sie zur Einrichtung diese Felder aus:

#### **1.1. Angebotsname**

Nur für die interne Nutzung, um Ihnen zu helfen, mehrere Angebote innerhalb der BOGOS-App zu identifizieren und zu verwalten.

#### **1.2. Angebotstitel**

Der Anzeigetitel, der diesen Rabatt Ihren Kunden vorstellt.

#### **1.3. Blockbeschreibung** (optional)

Fügen Sie zusätzliche Details hinzu, um das Angebot zu erläutern oder hervorzuheben.

#### **1.4. Start-** und **Endzeit** (optional)

Planen Sie, wann das Angebot live geht und wann es endet. Wenn nicht geändert, wird das Angebot nach der Veröffentlichung automatisch aktiv.

#### **1.5. Countdown-Timer anzeigen (optional)**

Aktivieren Sie einen Countdown-Timer im Widget, um Kunden zu motivieren, vor Ablauf des Angebots zu kaufen.

* Diese Option ist standardmäßig deaktiviert. Sie wird verfügbar, sobald Sie eine Endzeit festlegen oder die Wiederholungszeit aktivieren.
* Ohne Wiederholungszeit läuft der Countdown basierend auf der Endzeit.
* Wenn die Wiederholungszeit festgelegt ist, läuft der Countdown basierend auf der Endzeit jeder Wiederholungssitzung (in Tagen).

#### 1.6. Wiederholungszeit (optional)

Aktivieren Sie das Angebot nach einem wiederkehrenden Zeitplan innerhalb seines aktiven Zeitraums, ideal für tägliche Blitzverkäufe, Wochenend-Aktionen oder monatliche Kampagnen. Wenn aktiviert, wird die Endzeit des aktiven Zeitraums automatisch mit dem Enddatum der Wiederholung synchronisiert.

Konfigurieren Sie zur Einrichtung Folgendes:

**1.6.1. Häufigkeit**

Wählen Sie, wie oft sich das Angebot wiederholt: Täglich, Wöchentlich oder Monatlich.

* **Täglich:** Das Angebot läuft jeden Tag innerhalb des gewählten Zeitfensters.

<figure><img src="../../.gitbook/assets/image (446).png" alt=""><figcaption></figcaption></figure>

* **Wöchentlich:** Das Angebot läuft an ausgewählten Wochentagen.&#x20;

<figure><img src="../../.gitbook/assets/image (449).png" alt=""><figcaption></figcaption></figure>

* **Monatlich:** Das Angebot läuft an einem bestimmten Tag jeden Monats. Wenn Sie Tag 29, 30 oder 31 auswählen, wiederholt sich das Angebot am letzten Tag des Monats, falls dieses Datum nicht existiert.

<figure><img src="../../.gitbook/assets/image (450).png" alt=""><figcaption></figcaption></figure>

**1.6.2. Startzeit (in Tagen) / Endzeit (in Tagen)**

Das tägliche Zeitfenster, in dem das Angebot während jeder Wiederholungssitzung aktiv ist (z. B. 09:00 bis 11:00). Die Zeiten basieren auf der aktuellen Zeitzone Ihres Shops.

**1.6.3. Wiederholung beenden wenn**

Wählen Sie, wann die Wiederholung endet.

* **Kein Enddatum:** Das Angebot wiederholt sich weiter, bis Sie es manuell deaktivieren.
* **Am Datum:** Das Angebot endet an einem bestimmten Datum. Wenn Sie bereits eine Endzeit festgelegt haben, wird dieses Feld standardmäßig auf dieses Datum gesetzt, Sie können es aber weiterhin ändern.
* **Nach N Malen:** Das Angebot endet, nachdem es eine festgelegte Anzahl von Malen gelaufen ist.

{% hint style="warning" %}
Wenn das Angebot mit aktivierter Wiederholungszeit erstellt wird, erscheint es mit dem Status „Geplant“, damit Sie kommende Durchläufe verfolgen können.&#x20;
{% endhint %}

{% hint style="warning" %}
Wenn ein Angebot abläuft, während sich ein Kunde noch im Checkout-Prozess befindet, wird der Rabatt automatisch entfernt und die Produkte werden zum Originalpreis berechnet.&#x20;
{% endhint %}

### 2. Festlegen, für welche Produkte das Angebot gilt

Diese Einstellung legt fest, welche Produkte im Warenkorb auf die Rabattbedingung angerechnet werden und für den Rabatt berechtigt sind.&#x20;

<figure><img src="../../.gitbook/assets/image (455).png" alt="" width="563"><figcaption></figcaption></figure>

Wählen Sie zur Einrichtung eine der folgenden Optionen:

* **Beliebige Produkte**: Rabatt auf alle Produkte im Warenkorb anwenden.
* **Alle außer ausgewählte Produkte**: Rabatt auf alle Produkte außer den von Ihnen ausgewählten anwenden.
* **Alle außer ausgewählte Produktart/Verkäufer/Sammlung**: Rabatt auf alle Produkte außer denen einer bestimmten Produktart, eines Verkäufers oder einer Sammlung anwenden.
* **Ausgewählte Produkte**: Rabatt nur auf die von Ihnen ausgewählten spezifischen Produkte anwenden.
* **Ausgewählte Produktart/Verkäufer/Sammlung**: Rabatt nur auf Produkte einer bestimmten Produktart, eines Verkäufers oder einer Sammlung anwenden.

### 3. Maximale Anzahl an Rabattnutzungen einrichten

In diesem Abschnitt können Sie begrenzen, wie oft der Rabatt insgesamt oder pro Kunde eingelöst werden kann, nützlich für zeitlich begrenzte oder exklusive Rabatte.

<figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

Aktivieren Sie zur Einrichtung **eine oder beide** der folgenden Optionen:

1. **Anzahl der Nutzungen dieses Rabatts insgesamt begrenzen:** Legen Sie eine maximale Anzahl fest, wie oft der Rabatt über alle Kunden hinweg eingelöst werden kann (z. B. die ersten 100 Nutzungen).&#x20;

{% hint style="info" %}
Der Zähler „X/Y verwendet“ zeigt die aktuelle Nutzung an (z. B. bedeutet „89/100 verwendet“, dass dieser Rabatt 89 von 100 Mal eingelöst wurde).
{% endhint %}

2. **Auf eine Nutzung pro Kunde beschränken:** Stellen Sie sicher, dass jeder Kunde den Rabatt nur einmal einlösen kann.

* **Für angemeldete Kunden** prüft BOGOS deren Kontonutzung. Wenn sie das Limit erreicht haben, wird das Warenkorbrabatt-Widget ausgeblendet und der Rabatt ist nicht verfügbar.
* **Für Gastkunden** bleibt das Widget sichtbar, und der Rabatt kann im Warenkorb angewendet werden. An der Kasse prüft Shopify jedoch die vergangenen Bestellungen der E-Mail-Adresse. Wenn die E-Mail-Adresse das Limit erreicht hat, wird der Rabatt automatisch entfernt.

### 4. Unterbedingungen hinzufügen

Unterbedingungen sind optional einzurichten, können aber zusätzliche Regeln hinzufügen, die festlegen, wer Ihre Angebote sehen und erhalten kann. Dadurch können nur gezielte Kunden das Angebot sehen und anwenden, während andere es überhaupt nicht sehen.

<figure><img src="../../.gitbook/assets/unknown (60).png" alt="" width="503"><figcaption></figcaption></figure>

* **Spezifische Linkadresse** – Angebote auf Kunden anwenden, die über einen bestimmten Link auf Ihren Shop zugreifen. Perfekt für E-Mail-Kampagnen, Social-Media-Beiträge oder Affiliates.
* **Bestellhistorie** – Kunden basierend auf ihrem Kaufverhalten ansprechen. Am besten geeignet, um Erstkäufer, Vielkäufer und mehr zu belohnen.
* **Kundentags** – Angebote basierend auf Kundentags anzeigen oder ausblenden.
* **Kundenstandort** – Länderspezifische Aktionen basierend auf der IP-Adresse des Kunden durchführen.
* **Märkte** – Regionsspezifische Angebote basierend auf Ihren Shopify Markets durchführen.

{% hint style="info" %}
Sie können mehrere Unterbedingungen kombinieren. Kunden müssen alle ausgewählten Kriterien erfüllen, um sich zu qualifizieren.
{% endhint %}

_Weitere Details finden Sie in unserem Leitfaden \[_[_Unterbedingung bei Bundle, Upsell, Rabatt_](https://bogos-guideline.gitbook.io/user-guide/detailed-guide/detailed-doc/how-to-add-bogos-sub-conditions-to-bundle-upsell-discount)_]._

### 5. Rabatte & Stufen einrichten

In diesem Abschnitt können Sie Rabatte erstellen, die Kunden dazu ermutigen, mehr zu kaufen. Sie können einen einzelnen Rabatt festlegen oder gestaffelte Rabatte verwenden (mehr ausgeben, mehr sparen), um höhere Ausgaben zu belohnen.

![](<../../.gitbook/assets/unknown (358).png>)

Wenn Sie im Abschnitt „Angebote“ **Alle außer ausgewählte Produkte**, **Alle außer ausgewählte Produktart/Verkäufer/Sammlung**, **Ausgewählte Produkte** oder **Ausgewählte Produktart/Verkäufer/Sammlung** ausgewählt haben, wählen Sie, wie der Rabatt angewendet wird:

* **Rabatt auf die gesamte Bestellung anwenden:** Den Rabatt vom gesamten Warenkorbwert abziehen, einschließlich nicht berechtigter Produkte.
* **Rabatt nur auf berechtigte Produkte anwenden:** Den Rabatt nur von den berechtigten Produkten im Warenkorb abziehen.



Füllen Sie zur Einrichtung diese Felder aus:

1. Wählen Sie **Rabatt nach**, um festzulegen, wodurch der Rabatt ausgelöst wird:

* **Warenkorbwert**: Basierend auf dem Gesamtwarenkorbwert (z. B. 100 £ ausgeben).
* **Warenkorbmenge**: Basierend auf der Anzahl der Artikel im Warenkorb (z. B. 5 Artikel kaufen).



2. Wählen Sie die **Rabattart**:

* **Prozentsatz**: Einen Prozentsatz des Gesamtwarenkorbwerts abziehen (z. B. 10 % Rabatt).
* **Betrag**: Einen festen Betrag vom Gesamtwarenkorbwert abziehen (z. B. 10 £ Rabatt).



3. **Stufen hinzufügen**, um einen gestaffelten Rabatt für ein „mehr ausgeben, mehr sparen“-Angebot zu erstellen (optional).



4. Konfigurieren Sie jede Stufe, indem Sie die folgenden Felder ausfüllen:

* **Erforderlicher Warenkorbwert / Erforderliche Warenkorbmenge**: Der minimale Warenkorbwert oder die minimale Menge, die ein Kunde erreichen muss, um den Rabatt dieser Stufe freizuschalten.
* **Rabattwert**: Der Prozentsatz oder feste Betrag, der abgezogen wird, wenn diese Stufe erreicht wird.
* **Maximaler Rabattbetrag** (bei Auswahl eines prozentualen Rabatts): Legen Sie die maximale Ersparnis fest, die ein Kunde erhalten kann (z. B. 10 % Rabatt, maximal 10 $).
* **Labeltext**: Ein auf dem Widget angezeigtes Label, das Kunden hilft, diese Rabattstufe besser zu verstehen (z. B. „Kaufen Sie für 100 $ und erhalten Sie 5 % RABATT“).

{% hint style="info" %}
Wenn Sie Warenkorbwert oder festen Rabattbetrag oder maximalen Rabattwert wählen und auch Shopify Markets verwenden, können Sie „**Währung hinzufügen**“ und **den Geldbetrag für jeden Markt anpassen**, anstatt die Wechselkurse von Shopify zu verwenden (z. B. SGD 10, CN¥8, A$12).

<p align="center"><img src="../../.gitbook/assets/unknown (65).png" alt="" data-size="original"></p>
{% endhint %}

### 6. Benutzerdefinierter Rabattcode

Standardmäßig **generiert BOGOS automatisch einen zufälligen Rabattcode** (z. B. BOGOS-XSJSC) für den Rabatt. Dieser Code wird automatisch im Warenkorb des Kunden angewendet.

Sie können diesen automatisch generierten Code jedoch durch einen benutzerdefinierten Namen ersetzen, der zu Ihrer Strategie passt (z. B. SUMMER20). Füllen Sie dazu das Feld **Benutzerdefinierter Rabattcode** aus.

<figure><img src="../../.gitbook/assets/unknown (63).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Der Name des Rabattcodes muss unter 256 Zeichen liegen und über alle mit Shopify-Rabatten erstellten Rabatte hinweg eindeutig sein.
{% endhint %}

### 7. Mit anderen Rabatten kombinieren

Standardmäßig funktioniert der BOGOS-Warenkorbrabatt mit allen anderen Rabatten zusammen. Um die Kombination zu verhindern, können Sie die gewünschte Option **deaktivieren**:

<figure><img src="../../.gitbook/assets/unknown (64).png" alt=""><figcaption></figcaption></figure>

* **Produktrabatt**: Mit Rabatten auf Produktebene kombinieren
* **Bestellrabatt**: Mit Rabatten auf Bestellebene kombinieren
* **Versandrabatt**: Mit Versandrabatten kombinieren

{% hint style="info" %}
Die Kombinationseinstellungen folgen den Rabattregeln von Shopify. Stellen Sie sicher, dass die Rabatte, die Sie kombinieren möchten, auch auf ihrer Seite für die Kombination konfiguriert sind.
{% endhint %}

### Benötigen Sie Hilfe?

Wenn Sie Unterstützung benötigen, wenden Sie sich gerne über den **Live-Chat** in unserer BOGOS-App an unser Kundensupport-Team.
