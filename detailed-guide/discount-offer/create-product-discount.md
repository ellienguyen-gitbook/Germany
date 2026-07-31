# Produktrabatt erstellen

Ein Produktrabatt **wendet einen Rabatt pro Produkt** in Ihrem Shop an, und der reduzierte Preis wird automatisch im Warenkorb angewendet, ohne dass eine manuelle Gutscheineingabe erforderlich ist.&#x20;

Sie können auch shopweite Verkäufe, Blitzverkäufe oder private Verkäufe durchführen, die eine bestimmte Kundengruppe belohnen.

![](<../../.gitbook/assets/unknown (320).png>)

Die Einrichtung eines Produktrabatt-Angebots mit der BOGOS-App umfasst 9 Schritte:

1. Öffnen Sie im Menü Alle Angebote > Angebote erstellen > Rabatt > Produktrabatt.
2. [Richten Sie die Angebotsinformationen ein](create-product-discount.md#set-up-offer-information).
3. [Legen Sie fest, für welche Produkte das Angebot gilt](create-product-discount.md#define-offers-apply-to-which-products).
4. [Fügen Sie eine Unterbedingung hinzu](create-product-discount.md#add-sub-condition) (optional).
5. [Richten Sie die maximale Anzahl an Rabattnutzungen ein](create-product-discount.md#set-up-maximum-discount-uses) (optional).
6. [Richten Sie einen Rabatt ein](create-product-discount.md#set-up-discount).
7. [Individueller Rabattcode & Kombination](create-product-discount.md#custom-discount-code-name-1) (optional).
8. Klicken Sie auf Veröffentlichen.
9. [Passen Sie die Anzeige des reduzierten Preises & des Countdown-Widgets an](../customize/customize-product-discount.md).

{% embed url="https://youtu.be/wcDYt8VEct0?si=GRiLmJzTg2WKlN4G" %}

## 1. Angebotsinformationen einrichten

Dieser Bereich legt die grundlegenden Informationen für Ihr Produktrabatt-Angebot fest.

<figure><img src="../../.gitbook/assets/image (428).png" alt=""><figcaption></figcaption></figure>

Füllen Sie zur Einrichtung diese Felder aus:

#### **1.1. Angebotsname**

Nur zur Verwaltung in BOGOS.

#### **1.2. Angebotstitel, Blockbeschreibung**

Text, der im Countdown-Timer angezeigt wird.

#### **1.3. Startzeit / Endzeit** (optional)

Planen Sie, wann das Angebot live geht und wann es endet.

{% hint style="info" %}
Wenn Sie die Endzeit des Angebots festlegen, wird ein Countdown-Timer auf der Produktseite ausgelöst. [Passen Sie den Countdown-Timer an](../customize/customize-product-discount.md).
{% endhint %}

#### 1.4. Wiederkehrende Zeit (optional)

Aktivieren Sie das Angebot nach einem wiederkehrenden Zeitplan innerhalb seines aktiven Zeitraums, ideal für tägliche Blitzverkäufe, Wochenendaktionen oder monatliche Kampagnen. Wenn aktiviert, wird die Endzeit des aktiven Zeitraums automatisch mit dem Enddatum der Wiederholung synchronisiert.

Zur Einrichtung konfigurieren Sie Folgendes:

**1.4.1. Häufigkeit**

Wählen Sie, wie oft sich das Angebot wiederholt: Täglich oder Wöchentlich.

* **Täglich:** Das Angebot läuft jeden Tag innerhalb des gewählten Zeitfensters.

<figure><img src="../../.gitbook/assets/image (452).png" alt=""><figcaption></figcaption></figure>

* **Wöchentlich:** Das Angebot läuft an den ausgewählten Wochentagen.&#x20;

<figure><img src="../../.gitbook/assets/image (454).png" alt=""><figcaption></figcaption></figure>

**1.4.2. Startzeit (in Tag) / Endzeit (in Tag)**

Das tägliche Zeitfenster, in dem das Angebot während jeder wiederkehrenden Sitzung aktiv ist (z. B. 09:00 bis 11:00 Uhr). Die Zeiten richten sich nach der aktuellen Zeitzone Ihres Shops.

{% hint style="warning" %}
Wenn das Angebot mit aktivierter wiederkehrender Zeit erstellt wird, erscheint es mit dem Status Geplant, damit Sie kommende Ausführungen verfolgen können.&#x20;
{% endhint %}

{% hint style="warning" %}
Wenn ein Angebot abläuft, während sich ein Kunde noch im Checkout-Prozess befindet, wird der Rabatt automatisch entfernt und die Produkte werden zum Originalpreis berechnet.&#x20;
{% endhint %}

## 2. Festlegen, für welche Produkte die Angebote gelten

Diese Einstellung steuert, für welche Produkte der Rabatt gilt.

![](<../../.gitbook/assets/unknown (323).png>)

Wählen Sie zur Einrichtung eine der folgenden Optionen unter Rabatt anwenden auf:

* alle Produkte
* alle außer ausgewählten Produkten
* alle außer ausgewählten Typen/Anbietern/Sammlungen
* ausgewählte Produkte
* Produkte in ausgewählten Typen/Anbietern/Sammlungen

{% hint style="warning" %}
Wenn für ein Produkt mehrere Rabatte gleichzeitig aktiv sind, wird nur der größte Rabatt angewendet.&#x20;
{% endhint %}

## 3. Unterbedingung hinzufügen

Unterbedingungen fügen zusätzliche Regeln hinzu, die entscheiden, wer den Rabatt sehen und erhalten kann. Nur Kunden, die die Bedingungen erfüllen, sehen und erhalten das Angebot; andere sehen es gar nicht.

![](<../../.gitbook/assets/unknown (326).png>)

Klicken Sie auf Unterbedingung hinzufügen und wählen Sie dann eine oder mehrere:

* Spezifische Linkadresse
* Bestellhistorie der Kunden
* Kunden-Tags
* Kundenstandort
* Markets

{% hint style="info" %}
Sie können mehrere Unterbedingungen kombinieren. Kunden müssen ALLE ausgewählten Kriterien erfüllen, um berechtigt zu sein.
{% endhint %}

_Weitere Details finden Sie in unserem \[_[_Leitfaden zu Unterbedingungen bei Bundle, Upsell, Rabatt_](../detailed-doc/how-to-add-bogos-sub-conditions-to-bundle-upsell-discount.md)_]._

## 4. Maximale Anzahl an Rabattnutzungen einrichten

In diesem Bereich können Sie begrenzen, wie oft der Rabatt insgesamt oder pro Kunde eingelöst werden kann, nützlich für zeitlich begrenzte oder exklusive Rabatte.

![](<../../.gitbook/assets/unknown (341).png>)

Aktivieren Sie zur Einrichtung eine oder beide der folgenden Optionen:

* **Anzahl, wie oft dieser Rabatt insgesamt genutzt werden kann, begrenzen**: Legen Sie eine maximale Anzahl fest, wie oft der Rabatt über alle Kunden hinweg eingelöst werden kann.

{% hint style="info" %}
Der Zähler „X/Y genutzt“ zeigt die aktuelle Nutzung an.
{% endhint %}

* **Auf eine Nutzung pro Kunde begrenzen**: Stellen Sie sicher, dass jeder Kunde den Rabatt nur einmal einlösen kann.
  * **Bei angemeldeten Kunden** prüft BOGOS die Nutzung ihres Kontos. Wenn sie das Limit erreicht haben, wird der Rabatt ausgeblendet und ist nicht verfügbar.
  * **Bei Gastkunden** bleibt der Rabatt sichtbar und kann im Warenkorb angewendet werden. Beim Checkout prüft BOGOS jedoch die vergangenen Bestellungen der E-Mail-Adresse. Wenn die E-Mail-Adresse das Limit erreicht hat, wird der Rabatt automatisch entfernt.

## 5. Rabatt einrichten

Dieser Bereich legt fest, wie viel Kunden sparen.

![](<../../.gitbook/assets/unknown (329).png>)

Füllen Sie zur Einrichtung diese Felder aus:

* **Rabattart**: Wählen Sie, wie der Rabatt berechnet wird:
  * Prozentsatz (z. B., 10 % Rabatt)
  * Fester Betrag (z. B., 10 $ Rabatt)
  * Festpreis (z. B., dieses Produkt für 9,99 $ kaufen) (Tipp: ein Pauschalpreis-Verkauf für Ihren gesamten Shop).
* **Maximalen Rabattwert festlegen** (nur für Prozentsatz): Begrenzen Sie den maximalen Betrag, den ein Kunde sparen kann
  * Beispiel: 10 % Rabatt, bis zu 10 $.
* **Cent-Betrag überschreiben**: Ersetzen Sie den Centanteil des Endpreises durch einen von Ihnen festgelegten Wert, für saubere Preisendungen.
  * Beispiel: Cent-Betrag überschreiben = 0,99 bedeutet, wenn der reduzierte Preis 12,34 $ beträgt, wird Kunden der Endpreis 12,99 $ angezeigt.
* **Währung hinzufügen** (nur für Festen Betrag, Festpreis, Maximalen Rabattwert): Wenn Sie Shopify Markets verwenden, können Sie eine Währung hinzufügen, um einen individuellen Rabattwert für die Währung jedes Marktes festzulegen.

<img src="../../.gitbook/assets/unknown (331).png" alt="" height="150" width="447">

<br>

## 6. Individueller Rabattcode-Name

![](<../../.gitbook/assets/unknown (333).png>)

### 6.1. Einen individuellen Rabattcode-Namen hinzufügen

Standardmäßig generiert und wendet BOGOS automatisch einen Rabattcode für das Angebot an (z. B.; BOGOS-PpOp12).

Um diesen Code anzupassen, aktivieren Sie **Individuellen Rabattcode hinzufügen** und geben Sie einen Namen ein, der zu Ihrer Strategie passt (z. B., SUMMER20).&#x20;

![](<../../.gitbook/assets/unknown (335).png>)

{% hint style="info" %}
Der Code muss unter 256 Zeichen liegen und über alle mit Shopify-Rabatten erstellten Rabatte hinweg eindeutig sein.
{% endhint %}

### 6.2. Mit anderen Rabatten kombinieren

Standardmäßig kann der Produktrabatt mit Bestell- und Versandrabatten kombiniert werden. Die Kombination folgt den Rabattregeln von Shopify. Stellen Sie sicher, dass auch die anderen Rabatte auf ihrer Seite die Kombination zulassen.

Um die Kombination zu verhindern, **deaktivieren Sie die Option**, die Sie nicht möchten.

### Benötigen Sie Hilfe?

Wenn Sie Unterstützung benötigen, kontaktieren Sie gerne unser Kundensupport-Team über den Live-Chat in unserer BOGOS-App.
