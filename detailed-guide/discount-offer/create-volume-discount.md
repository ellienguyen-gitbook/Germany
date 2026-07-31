---
description: Übersicht zur Erstellung eines Mengenrabatts mit BOGOS
---

# Mengenrabatt erstellen

<figure><img src="../../.gitbook/assets/unknown (14).png" alt=""><figcaption></figcaption></figure>

Navigieren Sie zunächst in Ihrer **BOGOS-Navigation** zu **Alle Angebote** -> klicken Sie auf **Angebot erstellen** -> wählen Sie **Rabattangebot** -> **Mengenrabatt.**

{% embed url="https://youtu.be/E72ZySxY8AI" %}

### 1. Informationen zum Mengenrabatt

#### **1.1. Rabattname**

Der Rabattname ist eine interne Bezeichnung für Sie und Ihr Team zur Verwaltung und wird Kunden nicht angezeigt.

#### **1.2. Widget-Titel**&#x20;

Dies ist der Titel für Ihr Rabatt-Widget. Er wird Käufern auf der Produktseite angezeigt, daher sollte er ansprechend sein und die Aufmerksamkeit der Kunden erregen.&#x20;

#### **1.3. Blockbeschreibung**

Dieser Bereich dient dazu, Kunden mehr Informationen zu den im Widget angezeigten Rabattcodes zu geben.&#x20;

#### 1.4. Startzeit und Endzeit

* **Startzeit:** Der genaue Zeitpunkt, zu dem das Angebot beginnt.
* **Endzeit:** Der genaue Zeitpunkt, zu dem das Angebot endet.

#### 1.5. Countdown-Timer anzeigen (optional)

Aktivieren Sie einen Countdown-Timer im Widget, um Kunden zu motivieren, vor Ablauf des Angebots zu kaufen.

* Diese Option ist standardmäßig deaktiviert. Sie wird verfügbar, sobald Sie eine Endzeit festlegen oder die wiederkehrende Zeit aktivieren.
* Ohne wiederkehrende Zeit läuft der Countdown basierend auf der Endzeit.
* Wenn die wiederkehrende Zeit festgelegt ist, läuft der Countdown basierend auf der Endzeit jeder wiederkehrenden Sitzung (in Tagen).

#### 1.6. Wiederkehrende Zeit (optional)

Aktivieren Sie das Angebot nach einem wiederkehrenden Zeitplan innerhalb seines aktiven Zeitraums, ideal für tägliche Blitzverkäufe, Wochenendaktionen oder monatliche Kampagnen. Wenn aktiviert, wird die Endzeit des aktiven Zeitraums automatisch mit dem Enddatum der Wiederholung synchronisiert.

Zur Einrichtung konfigurieren Sie Folgendes:

**1.6.1. Häufigkeit**

Wählen Sie, wie oft sich das Angebot wiederholt: Täglich, Wöchentlich oder Monatlich.

* **Täglich:** Das Angebot läuft jeden Tag innerhalb des gewählten Zeitfensters.

![](<../../.gitbook/assets/unknown (355).png>)

* **Wöchentlich:** Das Angebot läuft an den ausgewählten Wochentagen.&#x20;

![](<../../.gitbook/assets/unknown (356).png>)

* **Monatlich:** Das Angebot läuft an einem bestimmten Tag jedes Monats. Wenn Sie Tag 29, 30 oder 31 auswählen, wiederholt sich das Angebot am letzten Tag des Monats, falls dieses Datum nicht existiert.

![](<../../.gitbook/assets/unknown (357).png>)

**1.6.2. Startzeit (in Tag) / Endzeit (in Tag)**

Das tägliche Zeitfenster, in dem das Angebot während jeder wiederkehrenden Sitzung aktiv ist (z. B. 09:00 bis 11:00 Uhr). Die Zeiten richten sich nach der aktuellen Zeitzone Ihres Shops.

**1.6.3. Wiederholung beenden, wenn**

Wählen Sie, wann die Wiederholung endet.

* **Kein Enddatum:** Das Angebot wiederholt sich weiter, bis Sie es manuell deaktivieren.
* **An Datum:** Das Angebot endet an einem bestimmten Datum. Wenn Sie bereits eine Endzeit festgelegt haben, ist dieses Feld standardmäßig auf dieses Datum gesetzt, Sie können es jedoch weiterhin ändern.
* **Nach N Malen:** Das Angebot endet, nachdem es eine festgelegte Anzahl von Malen ausgeführt wurde.

{% hint style="warning" %}
Wenn das Angebot mit aktivierter wiederkehrender Zeit erstellt wird, erscheint es mit dem Status Geplant, damit Sie kommende Ausführungen verfolgen können.&#x20;
{% endhint %}

{% hint style="warning" %}
Wenn ein Angebot abläuft, während sich ein Kunde noch im Checkout-Prozess befindet, wird der Rabatt automatisch entfernt und die Produkte werden zum Originalpreis berechnet.&#x20;
{% endhint %}

### 2. Angebote

<img src="../../.gitbook/assets/unknown (293).png" alt="" height="337" width="624">

**Mengenlogik:** Wählen Sie, wie Produkte im Warenkorb auf den Mengenschwellenwert angerechnet werden (festgelegt im Abschnitt [Stufen](create-volume-discount.md#id-4.-tiers)).

* **Nur gleiche Produkte zählen:** Der Kauf mehrerer Einheiten desselben Produkts zählt (z. B., wenn Kunden 3 Produkte kaufen müssen, qualifiziert sich 2A + 1B nicht für den Rabatt, aber 3A oder 3B schon).
* **Nur eindeutige Produkte zählen:** Der Kauf mehrerer Einheiten desselben Produkts zählt nur als eines. Das Hinzufügen weiterer Einheiten desselben Artikels erhöht die Zählung nicht.
  * Nach Produkt: Produkte müssen unterschiedlich sein, und Varianten desselben Produkts zählen als eines (z. B., 1A + 1B = 2 Artikel, aber 2A = 1 Artikel).
  * Nach Variante: Varianten müssen unterschiedlich sein (z. B., 1A-Rot + 1A-Blau = 2 Artikel, aber 2A-Rot = 1 Artikel).
* **Alle Produkte zählen:** Jeder Artikel im Warenkorb zählt, egal ob gleich oder unterschiedlich (z. B., 2A + 1B = 3 Artikel).

{% hint style="warning" %}
Der Anzeigetyp „Mengenoptionen“ ist nicht verfügbar, wenn „Nur eindeutige Produkte zählen“ ausgewählt ist.
{% endhint %}

**Anzeigetyp auswählen:** Wählen Sie einen geeigneten Typ zur Anzeige des Mengenrabatts zwischen:

* Mengenoptionen: Ein anpassbares Widget, mit dem Käufer ihre gewünschte Menge direkt auswählen können.&#x20;
* Mengenrabatt-Tabelle: Eine übersichtliche Aufschlüsselung aller verfügbaren Rabattstufen, die automatisch auf Produktseiten angezeigt wird.

**Anwenden auf:** Wählen Sie Produkte aus, auf die der Mengenrabatt angewendet werden soll, unter:

* Alle Produkte.
* Alle außer ausgewählte Produkte.
* Alle außer ausgewählte Typen/Anbieter/Sammlungen.
* Ausgewählte Produkte.
* Produkte in ausgewählten Typen/Anbietern/Sammlungen.

### 3. Unterbedingungen hinzufügen

Unterbedingungen fügen zusätzliche Regeln hinzu, um zu entscheiden, wer Ihre Angebote sehen und erhalten kann. Dadurch können nur die anvisierten Kunden das Angebot sehen und nutzen, während andere es gar nicht sehen.

{% hint style="info" %}
* Diese Unterbedingungen sind optional. Wenn Sie keine hinzufügen, ist das Angebot für alle Kunden verfügbar.
* Sie können mehrere Unterbedingungen kombinieren. Kunden müssen alle ausgewählten Kriterien erfüllen, um berechtigt zu sein.
{% endhint %}

<figure><img src="../../.gitbook/assets/unknown (154).png" alt="" width="503"><figcaption></figcaption></figure>

1. _Spezifische Linkadresse_ – Wenden Sie Angebote auf Kunden an, die über einen bestimmten Link auf Ihren Shop zugreifen. Perfekt für E-Mail-Kampagnen, Social-Media-Beiträge oder Affiliates.
2. _Bestellhistorie_ – Zielen Sie auf Kunden basierend auf ihrem Kaufverhalten ab. Am besten geeignet, um Erstkäufer, Vielkäufer und mehr zu belohnen.
3. _Kunden-Tags_ – Zeigen oder verbergen Sie Angebote basierend auf Kunden-Tags.
4. _Kundenstandort_ – Führen Sie länderspezifische Aktionen basierend auf der IP-Adresse des Kunden durch.
5. _Markets_ – Führen Sie regionsspezifische Angebote basierend auf Ihren Shopify Markets durch.

♦️ Weitere Details finden Sie in unserem \[[Unterbedingungen](../detailed-doc/how-to-add-bogos-sub-conditions-to-bundle-upsell-discount.md)]-Leitfaden.

### 4. Stufen

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfoHjdLGqWhQjGNqK5yCzPtiwVmjRoYm_N5Jl_tBWgqfMTCyEORebvHSVzZlQrfRiaCJYZHJLeoeYaBPpVVPtweL0h-EYZHsQx5QAeplt16bsocAfOaodGUWmbmODufM_4esK7Inw?key=M5v5s4MQ5Q14uLuc63pUvj8n" alt=""><figcaption></figcaption></figure>

Jeder Mengenrabatt umfasst mehrere Stufen mit bestimmten Produktmengenschwellen und Rabatthöhen.

{% hint style="info" %}
Der Mengenrabatt funktioniert über Bereiche, nicht über exakte Mengen.&#x20;

Beispiel:

* Stufe 1: Kaufen Sie **2 Artikel** → 10 % Rabatt
* Stufe 2: Kaufen Sie **5 Artikel** → 30 % Rabatt

Also:

* Kaufen Sie **2–4 Artikel** → 10 % Rabatt
* Kaufen Sie **5 oder mehr** → 30 % Rabatt

Damit nur Artikel bis zur letzten Stufe 30 % Rabatt erhalten und zusätzliche Artikel nicht rabattiert werden, aktivieren Sie „Alle Artikel, die die Menge der letzten Stufe überschreiten, werden nicht rabattiert“.
{% endhint %}

**Titel:** Dies ist der Name der Stufe. Häufig verwendete Namen sind Single, Double oder Trio. &#x20;

**Menge:** Dies stellt die Mindestproduktmenge dar, die Kunden kaufen müssen, um sich für den entsprechenden Stufenrabatt zu qualifizieren.

**Rabattart:** Wählen Sie zwischen 3 Typen:

* Prozentsatz (z. B., 20 % Rabatt)
* Betrag (z. B., 20 $ Rabatt)
* Festpreis (z. B., kaufen für 100 $)

**Versandrabatt:** Fügen Sie einen Versandrabatt zusätzlich zum oben ausgewählten Hauptrabatt hinzu,

<figure><img src="../../.gitbook/assets/unknown (117).png" alt="" width="461"><figcaption></figcaption></figure>

**Währung hinzufügen:** Wenn Sie **„Betrag“ oder „Festpreis“** wählen und außerdem Shopify Markets eingerichtet haben, können Sie individuell festlegen, wie hoch der Rabattbetrag in jeder Währung sein soll, anstatt die Wechselkurse von Shopify zu verwenden (z. B. SGD 10, CN¥8, A$12).

<figure><img src="../../.gitbook/assets/unknown (116).png" alt="" width="563"><figcaption></figcaption></figure>

**Beschreibungstext:** Dieser Bereich hilft Händlern, die Stufe genauer zu beschreiben.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXd5VDxpERcbKw4AotsC3yaqLpwKsdY9lWl_Nko1kiR2fDUCnIKTUovjRvS6Ktb2LTvv5LSPlXrXu9Bc4Iz8PMmf7SlJws8OSKqIxRTltXKY0_jwc2HxYgv9J93WvXLCWERhTtob?key=M5v5s4MQ5Q14uLuc63pUvj8n" alt=""><figcaption></figcaption></figure>

**Etikett** (für den Anzeigetyp „Mengenoptionen“)**:** Das Etikett erscheint über dem Titel und hebt die potenziellen Ersparnisse bei der Nutzung von Mengenrabatten hervor.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXc8iwBNXidFH1bZrzIym8fGJF-XOu1uSD32vKwv1aTGSCbwbMPLg0A1YNKvP8nqbzNPwtYm3-gRWVz7lS6uIh-WBEPoGupr6qmrZxgXdRNlsfu3do9F0qBFWd0IYZ8RgetrmMt-?key=M5v5s4MQ5Q14uLuc63pUvj8n" alt=""><figcaption></figcaption></figure>

**Tag:** Der Tag wird neben dem Etikett angezeigt. Dies hilft, jede Stufe zu identifizieren.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcSJwz6LJrMNrRtLiTUfvoLPU6OEhO3INWp2xHEYYavbDjApxzWJXHRAv-ib5hq0dD4ksDX16MJ5QPBpRf3CuT0gRLSUV_kXCi39kDRVKtlVI4KgZuGQr5qZNZBwwu56k0ZnW8u?key=M5v5s4MQ5Q14uLuc63pUvj8n" alt=""><figcaption></figcaption></figure>

**Vorausgewählt** (für den Anzeigetyp „Mengenoptionen“)**:** „Vorausgewählt“ wird standardmäßig verwendet, um eine Stufe auszuwählen.

**Alle Artikel, die die Menge der letzten Stufe überschreiten, werden nicht rabattiert** (optional): Wenn die letzte Stufe 3 Artikel erfordert, erhalten Kunden, die 4 oder mehr hinzufügen, den Rabatt nur auf die ersten 3 Artikel. Alle Artikel über dieser Menge hinaus werden zum vollen Preis berechnet.

<figure><img src="../../.gitbook/assets/unknown (17).png" alt=""><figcaption></figcaption></figure>

### 5. Abonnement

<figure><img src="../../.gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>

Diese neue Abonnement-Option ermöglicht es Ihren Kunden, Abonnement-Produkte direkt in Kombination mit dem Mengenrabatt in einem einzigen Widget von BOGOS zu kaufen.&#x20;

<figure><img src="../../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

Gleichzeitig werden Ihre mit der BOGOS-App erstellten Mengenrabattangebote automatisch mit diesen Abonnementrabatten kombiniert.

Wenn Sie sich dafür entscheiden, die Abonnement-Option auszublenden, können Ihre Kunden über dieses Mengenrabatt-Widget nur einmalige Artikel kaufen.

Solange Sie jedoch einen aktiven, in einer Abonnement-App erstellten Abonnementplan haben, werden Abonnementrabatte automatisch angewendet, wenn Kunden Ihre Bedingungen erfüllen, selbst wenn sie über ein Abonnement-Widget eines Drittanbieters kaufen.

{% hint style="info" %}
Wenn ein Produkt sowohl über Abonnement- als auch Mengenrabatte verfügt, wenden wir zuerst den Abonnementrabatt und dann den Mengenrabatt an (falls der Warenkorb des Kunden für beide qualifiziert ist).

Beispiel: Es gibt eine Jacke für 5 $ mit 5 % Abonnementrabatt und 10 % Mengenrabatt (Kauf von 2 Artikeln). Wenn ein Kunde 2 Jacken im Abonnement kauft, erhalten wir den Endpreis:&#x20;

(5 $ × 95 %) × 90 % = 4,28 $ pro Jacke
{% endhint %}

### 6. Rabattcode

#### Benutzerdefinierten Code hinzufügen

In diesem Bereich können Sie den Namen des Rabattcodes anpassen, damit er zu Ihrer Marke passt.

<figure><img src="../../.gitbook/assets/image (326).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Der Name des Rabattcodes muss unter 256 Zeichen liegen und über alle Shopify-Rabatte hinweg eindeutig sein.
{% endhint %}

#### **Kombination**

<figure><img src="../../.gitbook/assets/image (327).png" alt=""><figcaption></figcaption></figure>

Mit dieser Option können Sie Ihre Mengenrabatte verbessern, indem Sie sie mit bestehenden Aktionen in Ihrem Shop kombinieren:

* Bestellrabatte
* Versandrabatte

### 7. Mengenrabatt anpassen

Weitere Informationen finden Sie in [diesem Dokument](create-volume-discount.md#id-5.-customize-volume-discount) für die ausführliche Anleitung zum **Anpassen des Mengenrabatts**

## FAQs

<details>

<summary><strong>Ist es möglich, einen Rabatt beim Kauf von genau 3 Produkten einzurichten?</strong></summary>

Derzeit ist unsere Rabattlogik für **mengenbasierte Anreize** optimiert (Käufe, die eine bestimmte Menge überschreiten). Zurzeit unterstützt das System keine „exakten“ Mengenanforderungen.&#x20;

</details>

<details>

<summary><strong>Ist es möglich, den Vergleichspreis eines Produkts im Mengenrabatt-Widget anzuzeigen?</strong></summary>

Um ein transparentes Einkaufserlebnis zu gewährleisten und die Shopify-Konformität einzuhalten, zeigt unsere App den aktuellen Preis der Produkte an und wendet den Rabatt ebenfalls auf diese Preise an.&#x20;

</details>

<details>

<summary><strong>Wie kann ich das Mengenrabatt-Angebot nur für VIP-Kunden sichtbar machen?</strong></summary>

Sie können die Unterbedingung **„Kunden-Tags“** verwenden. Indem Sie ein Tag wie „VIP“ hinzufügen, ist das Mengenrabatt-Widget nur für angemeldete Kunden mit diesem bestimmten Tag sichtbar und anwendbar.

![](<../../.gitbook/assets/unknown (218).png>)

</details>
