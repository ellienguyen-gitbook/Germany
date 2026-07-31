# Checkout-Upsell erstellen

Mit Checkout-Upsell können Sie Kunden beim Checkout zusätzliche Produkte anbieten und so Ihren durchschnittlichen Bestellwert (AOV) erhöhen und Ihren Umsatz steigern.

Hier ist eine kurze Demo, wie das Checkout-Upsell-Widget in Ihrem Shop angezeigt wird:

<figure><img src="../../.gitbook/assets/unknown (41).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Nachdem Sie Ihren Upsell veröffentlicht haben, müssen Sie [das Widget aktivieren](create-checkout-upsell.md#id-8.-enable-the-checkout-upsell-widget), damit es in Ihrem Storefront erscheint.
{% endhint %}

{% hint style="info" %}
Shopify erlaubt nur **Shopify Plus**, Checkout-Seiten zu bearbeiten, daher ist diese Funktion derzeit nur für Shopify Plus verfügbar.&#x20;
{% endhint %}

{% embed url="https://youtu.be/A0EKHj3ZtyQ?si=ds35FtxozKolQvg7" %}

## 1. Upsell-Informationen

### 1.1 Upsell-Titel

Der Upsell-Titel ist der Name des Upsells, der für Kunden nicht sichtbar ist und im Bereich „Alle Angebote“ der BOGOS-App zur einfachen Verwaltung neben anderen Angeboten angezeigt wird.

### 1.2 Start- & Endzeit

* **Startzeit:** Dies ist der Zeitpunkt, an dem der Upsell aktiv wird und für Kunden beim Checkout Ihres Shops sichtbar ist.
* **Endzeit:** Dies ist der Zeitpunkt, an dem der Upsell abläuft und beim Checkout Ihres Shops nicht mehr sichtbar ist. Lassen Sie dieses Feld leer, damit der Upsell durchgehend läuft.

## 2. Upsell-Auslöser

Hier wählen Sie eine der 4 unten aufgeführten Bedingungen aus, die Kunden erfüllen müssen, damit der Upsell beim Checkout angezeigt wird.

### 2.1 Upsell immer anzeigen

Der Upsell wird Kunden beim Checkout ohne besondere Bedingungen immer angezeigt.

### 2.2 Warenkorb-Auslöser

Der Upsell wird angezeigt, wenn der Warenkorb des Kunden eine der folgenden 2 Bedingungen erfüllt:

* **Menge**: Der Warenkorb des Kunden muss eine von Ihnen festgelegte Mindest- und/oder Höchstanzahl an Produkten erfüllen.
* **Wert**: Der Warenkorb des Kunden muss einen von Ihnen festgelegten Mindest- und/oder Höchstgesamtwert erfüllen.&#x20;

**Für Shops mit eingerichteten Shopify Markets, die „Warenkorbwert“ wählen:**

Normalerweise rechnet BOGOS Ihre Hauptwährung automatisch mithilfe des Wechselkurses von Shopify in die Währung des Kunden um (z. B. 1 SGD = 0,666 €).

Wenn Sie jedoch **individuelle Warenkorbwerte für jede Währung festlegen** möchten, klicken Sie nach der Festlegung des Werts für Ihren Hauptmarkt (Mindestwert ist 0) auf „Währung hinzufügen“ und geben Sie den Wert ein.

<figure><img src="../../.gitbook/assets/image (382).png" alt=""><figcaption></figcaption></figure>

### 2.3 Auslöser für bestimmte Produkte

Der Upsell wird ausgelöst, wenn der Checkout des Kunden Folgendes enthält:

* **Produkt**: Die Checkout-Übersicht des Kunden muss Produkte aus der von Ihnen ausgewählten Liste enthalten und die von Ihnen festgelegte „erforderliche Produktanzahl“ erfüllen.
* **Sammlung**: Jedes Produkt aus einer oder mehreren von Ihnen ausgewählten Sammlungen.
* **Abonnement-Produkt**: Ein oder mehrere von Ihnen ausgewählte Produkte mit einem Abonnementplan.

### 2.4 Kunden-Auslöser

Der Upsell wird basierend auf bestimmten Kundenbedingungen ausgelöst, darunter:

* **Kunden-Tags:** Der Upsell wird nur Kunden mit den von Ihnen ausgewählten Tags angezeigt. Es gibt außerdem 2 optionale Einstellungen:
  * Kunden mit diesen Tags ausschließen: Alle Kunden außer denen mit den ausgewählten Tags sehen den Upsell.
  * Nicht angemeldete Nutzer als Kunden ohne Tags behandeln: Kunden, die nicht angemeldet sind, werden so behandelt, als hätten sie keine Tags, das heißt, sie werden basierend auf Ihren Tag-Einstellungen ein- oder ausgeschlossen.
* **Standort**: Der Upsell wird nur Kunden aus den von Ihnen ausgewählten Standorten angezeigt. Es gibt außerdem 1 optionale Einstellung:
  * Kunden aus ausgewählten Standorten ausschließen: Kunden aus jedem Standort außer den ausgewählten sehen den Upsell.
* **Bestellhistorie:** Der Upsell wird nur Kunden angezeigt, die ab dem von Ihnen gewählten Datum Bestellungen aufgegeben haben. Anschließend müssen Sie auswählen, welche Bedingung(en) diese Bestellungen erfüllen müssen, damit der Upsell ausgelöst wird:
* **Gesamtausgaben in der Bestellhistorie**: Die Gesamtausgaben aus Bestellungen, die nach dem Startdatum aufgegeben wurden, müssen einen Mindest- und/oder Höchstbetrag erfüllen.
* **Gesamtausgaben der letzten Bestellung:** Die letzte Bestellung des Kunden, aufgegeben nach dem Startdatum, muss einen Mindest- und/oder Höchstwert erfüllen.
* **Gesamtanzahl der aufgegebenen Bestellungen:** Ab dem ausgewählten Datum muss der Kunde eine Mindest- und/oder Höchstanzahl an Bestellungen aufgeben.

## 3. Unterbedingungen hinzufügen

Unterbedingungen fügen zusätzliche Regeln hinzu, um zu entscheiden, wer Ihre Angebote sehen und erhalten kann. Dadurch können nur die anvisierten Kunden das Angebot sehen und nutzen, während andere es gar nicht sehen.

{% hint style="info" %}
* Diese Unterbedingungen sind optional. Wenn Sie keine hinzufügen, ist das Angebot für alle Kunden verfügbar.
* Sie können mehrere Unterbedingungen kombinieren. Kunden müssen alle ausgewählten Kriterien erfüllen, um berechtigt zu sein.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (388).png" alt="" width="563"><figcaption></figcaption></figure>

1. _Spezifische Linkadresse_ – Wenden Sie Angebote auf Kunden an, die über einen bestimmten Link auf Ihren Shop zugreifen. Perfekt für E-Mail-Kampagnen, Social-Media-Beiträge oder Affiliates.
2. _Markets_ – Führen Sie regionsspezifische Angebote basierend auf Ihren Shopify Markets durch.

♦️ Weitere Details finden Sie in unserem \[[Unterbedingungen](../detailed-doc/how-to-add-bogos-sub-conditions-to-bundle-upsell-discount.md)]-Leitfaden.

## 4. Upsell-Methode

Hier legen Sie fest, wie Sie Kunden während des Checkouts Upsell-Produkte anbieten möchten. Es gibt 3 Methoden.

### 4.1 Manuell

Sie wählen die Produkte für den Upsell manuell aus und legen die Art des Rabatts (entweder prozentual oder als Festbetrag) fest.

### 4.2 Automatisch

Um diese Option zu nutzen, müssen Sie zunächst die App **Shopify Search & Discovery** in Ihrem Shop installiert haben. BOGOS wählt Upsell-Produkte automatisch anhand der mit der Shopify Search & Discovery App synchronisierten Daten aus. [Installieren Sie diese KOSTENLOSE App hier.](https://apps.shopify.com/search-and-discovery)

Auf dem Einstellungsbildschirm von BOGOS gibt es 2 Empfehlungstypen: **Ergänzende Produkte** und **Verwandte Produkte**, beide synchronisiert mit Daten aus der Shopify Search & Discovery App, wie im folgenden Beispiel gezeigt.

{% hint style="info" %}
Für „Ergänzende Produkte“ in der Shopify Search & Discovery App müssen Sie Produkte manuell innerhalb der App auswählen. Bei „Verwandte Produkte“ nutzt Shopify KI, um automatisch Produktempfehlungen zu generieren. [Klicken Sie hier, um die Hilfedokumentation dazu anzusehen.](https://help.shopify.com/en/manual/online-store/search-and-discovery/product-recommendations)
{% endhint %}

### 4.3 Abonnement-Produkt

Diese Methode erscheint nur, wenn Sie oben im **Upsell-Auslöser** „Abonnement-Produkt“ ausgewählt haben.&#x20;

Abonnement-Produkte können nur diese Upsell-Methode verwenden, die Kunden automatisch zum wertvollsten Plan mit dem größten Rabatt upselt.

#### 4.4 Maximale Anzahl hinzufügbarer Upsell-Produkte begrenzen

Aktivieren Sie diese Option, um die maximale Anzahl an Upsell-Produkten zu steuern, die ein Kunde aus dem Upsell-Bereich in seinen Warenkorb legen kann.&#x20;

Sobald das Limit erreicht ist, verschwindet der Upsell-Bereich automatisch.

<figure><img src="../../.gitbook/assets/unknown (40).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Diese Option ist nicht verfügbar, wenn die Methode „Produkte automatisch zum Warenkorb hinzufügen“ der Einstellung „Rabattcode erforderlich“ in der erweiterten Konfiguration verwendet wird.
{% endhint %}

### 4.5 Rabattart

<figure><img src="../../.gitbook/assets/image (54).png" alt=""><figcaption></figcaption></figure>

**Produktrabatt:** Ermöglicht Ihnen die Auswahl der Rabattart

* Prozentsatz: für einen prozentualen Rabatt
* Betrag: für einen festen Geldrabatt. Wenn Sie auch in verschiedenen Währungen verkaufen (eingerichtet in Shopify Markets), können Sie „Währung hinzufügen“ und **individuell festlegen, wie hoch der Rabattbetrag** in jeder Währung sein soll, anstatt die Wechselkurse von Shopify zu verwenden (z. B. SGD 10, CN¥8, A$12).

<figure><img src="../../.gitbook/assets/image (379).png" alt="" width="563"><figcaption></figcaption></figure>

### 4.6 Versandrabatt hinzufügen

<figure><img src="../../.gitbook/assets/image (380).png" alt="" width="461"><figcaption></figcaption></figure>

Es gibt zwei Arten von Versandrabatt:

* Prozentsatz: Ein Prozentsatz der Versandkosten wird abgezogen.
* Betrag: Ein fester Betrag wird von den gesamten Versandkosten abgezogen. Wenn Sie in verschiedenen Währungen verkaufen (eingerichtet in Shopify Markets), können Sie „Währung hinzufügen“ und **individuell festlegen, wie hoch der Versandrabattbetrag in jeder Währung** sein soll, anstatt die Wechselkurse von Shopify zu verwenden (z. B. SGD 10, €8, A$12).

**Beschriftung im Widget**: Dieser Text informiert Kunden darüber, ob das Bundle einen Versandrabatt enthält.

## 5. Erweiterte Konfiguration (optional)

1. **Produkte im Warenkorb ausschließen**

<figure><img src="../../.gitbook/assets/image (280).png" alt=""><figcaption></figcaption></figure>

Mit dieser Funktion können Sie Upsell-Produkte, die sich bereits im Warenkorb der Kunden befinden, ein- oder ausschließen.

{% hint style="info" %}
Diese Funktion arbeitet auf Produktebene. Wenn Ihr Warenkorb ein Produkt mit Variante A enthält, werden auch andere Varianten desselben Produkts (z. B. Variante B) ausgeblendet.
{% endhint %}

2. **Abgleich der Upsell-Produktvariante**

Diese Funktion gleicht die Variante des Upsell-Produkts automatisch mit der Variante des Produkts im Warenkorb des Kunden ab.

**Beispiel**: Wenn ein Kunde ein T-Shirt (Größe M) kauft, empfiehlt das Upsell-Widget ein weiteres T-Shirt (Größe M).

{% hint style="info" %}
Gilt nur für die Upsell-Methode „Manuell“.
{% endhint %}

3. **Rabattcode**

Sie können einen Rabattcode generieren, den Kunden manuell auf der Checkout-Seite eingeben müssen, um ihre Kaufabläufe effizient auszulösen.&#x20;

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXesoGHQspnuAcp993O2524cYImpeQ3cfJOvz7APcHKaCOAWL7QA9iMoqi4slaWTFOEkgbbX7g-MGHX1KMRC1sr1n7ScNzmQdOxUUYAc6p4YJU-QwHzlS8X1tldr7CXTMlVi9zoXPQ?key=h6X-GCR3Ue_E-vh3IcgWlzIw" alt=""><figcaption></figcaption></figure>

## 6. Rabattcode

**Einen benutzerdefinierten Rabattcode hinzufügen**

In diesem Bereich können Sie den Namen des Rabattcodes anpassen, damit er zu Ihrer Marke passt.<br>

<figure><img src="../../.gitbook/assets/image (322).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Der Name des Rabattcodes muss unter 256 Zeichen liegen und über alle Shopify-Rabatte hinweg eindeutig sein.
{% endhint %}

**Kombinationen**

<figure><img src="../../.gitbook/assets/image (323).png" alt=""><figcaption></figcaption></figure>

#### Bestellrabatte

Gibt an, ob der Upsell-Rabatt mit Rabatten auf Bestellebene kombiniert werden kann, wie zum Beispiel Aktionscodes oder automatischen Rabatten.

#### Versandrabatte

Gibt an, ob der Upsell-Rabatt mit Versandrabatten kombiniert werden kann, wie zum Beispiel kostenlosen oder reduzierten Versandaktionen.

## 7. Zusammenfassung

Das rechts fixierte Upsell-Zusammenfassungswidget aktualisiert alles, was Sie eingerichtet haben, zur einfachen Nachverfolgung.

## 8. Widget aktivieren

Stellen Sie sicher, dass Sie den Block „**BOGOS Checkout Upsell**“ in Ihrem **Theme-Editor** hinzugefügt haben, damit das Upsell-Widget beim Checkout erscheint.

**So geht's:**

1. Gehen Sie zu Ihrem **Shopify-Dashboard**
2. Navigieren Sie zu **Online-Shop > Themes**
3. Klicken Sie auf **Anpassen**
4. Wechseln Sie von **Startseite** > suchen und wählen Sie **Checkout und Kundenkonten**

<figure><img src="../../.gitbook/assets/image (348).png" alt=""><figcaption></figcaption></figure>

5. Klicken Sie in der Menüleiste auf **Abschnitt hinzufügen** > wählen Sie **BOGOS Checkout Upsell** und platzieren Sie es an der gewünschten Stelle

<figure><img src="../../.gitbook/assets/image (349).png" alt=""><figcaption></figcaption></figure>

## FAQs

<details>

<summary><strong>Kann ich beim Checkout ein kostenloses Geschenk per Rabattcode auslösen?</strong></summary>

Hier ist die vollständige Anleitung zum Erstellen eines Rabattcodes für Geschenkprodukte:

**Schritt 1 – Einen 0-€-Rabattcode in Shopify erstellen**

* Gehen Sie zu Shopify › Rabatte › Rabatt erstellen und wählen Sie Betrag vom Bestellwert abziehen.
* Legen Sie den Rabattcode fest, wählen Sie Fester Betrag = 0, und behalten Sie Alle Kunden bei.
* Wählen Sie bei Kombinationen Nur Produktrabatte und speichern Sie dann.

Dieser Rabattcode für den Checkout-Upsell dient tatsächlich dazu, zu erkennen, wann das Geschenk hinzugefügt werden soll. Sein Zweck ist nicht, den Preis zu senken. Unsere App übernimmt bereits die Preisreduzierung, die im Checkout-Upsell eingerichtet ist.

**Schritt 2 – Den Code zu Ihrem Checkout-Upsell in BOGOS hinzufügen**

* Gehen Sie in BOGOS zu Angebote › Erstellen › Upsell-Angebot › Checkout-Upsell.
* Fügen Sie in der erweiterten Konfiguration den genauen Rabattcode ein, den Sie erstellt haben.

**Schritt 3 – Veröffentlichen und testen**

Speichern Sie das Angebot und testen Sie es beim Checkout. Der Code sollte 0 € Rabatt anzeigen, und der Upsell wird wie erwartet ausgelöst.

</details>

<details>

<summary><strong>Kann ich Upsell-Produkte ausblenden, wenn der Kunde sie bereits im Warenkorb hat?</strong></summary>

**Ja, das können Sie!** Um sicherzustellen, dass Sie kein Produkt upsellen, das der Kunde bereits kauft, können Sie die Funktion **Ausschluss** verwenden.

**So richten Sie es ein:**

1. Gehen Sie zum Checkout-Upsell-Angebot
2. Gehen Sie zu Erweiterte Konfigurationen
3. Aktivieren Sie das Kästchen Produkte im Warenkorb ausschließen
4. Speichern

![](<../../.gitbook/assets/unknown (203).png>)

</details>

<details>

<summary><strong>Kann ich beim Checkout einfach dieselbe Größe für Produkte upsellen?</strong></summary>

Ja, das ist möglich. Bitte folgen Sie diesen Schritten:

1. Gehen Sie zum Checkout-Upsell-Angebot
2. Gehen Sie zu Erweiterte Konfigurationen > Abgleich der Upsell-Produktvariante
3. Aktivieren Sie das Kästchen Upsell-Produktvariante mit Warenkorb-Produkt abgleichen
4. Speichern

![](<../../.gitbook/assets/unknown (204).png>)

</details>
