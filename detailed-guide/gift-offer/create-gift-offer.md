# Geschenkangebot erstellen

**Bevor Sie beginnen:**&#x20;

Schauen Sie sich [diese Anleitung](https://youtu.be/R-DeHLuCFOw) an, um zu sehen, wie Sie mit BOGOS ein kostenloses Geschenk beim Kauf auf Shopify erstellen können.

{% embed url="https://youtu.be/R-DeHLuCFOw" %}

Das Erstellen eines Geschenkangebots besteht aus **5 grundlegenden Teilen**:

* Angebotsinformationen
* Hauptbedingung des Angebots
* Unterbedingung des Angebots&#x20;
* Geschenk auswählen
* Erweiterte Konfiguration (optional)

### 1. Angebotsinformationen

<div data-full-width="false"><figure><img src="../../.gitbook/assets/image (367).png" alt=""><figcaption></figcaption></figure></div>

#### 1.1. Angebotsname

Dieser Name dient nur der internen Verwaltung und ist für Kunden nicht sichtbar.

#### 1.2. Angebotstitel

Der Angebotstitel ist der Name des Angebots. Er erscheint auf der Verwaltungsseite „Alle Angebote“ und wird Kunden im Heute-Angebot-Widget, im Geschenk-Thumbnail und im Geschenk-Schieberegler angezeigt.

#### 1.3. Startzeit und Endzeit

* Startzeit: Der Zeitpunkt, zu dem das Angebot aktiv wird.
* Endzeit (optional): Der Zeitpunkt, zu dem das Angebot nicht mehr aktiv ist.&#x20;

### 2. Hauptbedingungen des Angebots

Die Hauptbedingung ist die Bedingung, die Kunden erfüllen müssen, um das Geschenk des Angebots zu erhalten.

<figure><img src="../../.gitbook/assets/image (95).png" alt="" width="496"><figcaption><p>Auswahlfenster für die Hauptbedingung</p></figcaption></figure>

#### **2.1. Zustand des Warenkorbwerts**

<figure><img src="../../.gitbook/assets/unknown (99).png" alt="" width="563"><figcaption></figcaption></figure>

* Mit dieser Bedingung können Sie den **minimalen und/oder maximalen Warenkorbwert** festlegen, den Kunden erreichen müssen, um sich für Ihr Geschenkangebot zu qualifizieren.
* Der eingegebene Warenkorbwert basiert auf der Hauptwährung Ihres Shops (z. B. SGD, wie im Bild gezeigt).
* **Für Shops mit eingerichtetem Shopify Markets:**

<figure><img src="../../.gitbook/assets/unknown (100).png" alt="" width="563"><figcaption></figcaption></figure>

Normalerweise rechnet BOGOS Ihre Hauptwährung automatisch anhand des Wechselkurses von Shopify in die Währung der Kunden um (z. B. 1 SGD = 0,666 €).

Wenn Sie jedoch stattdessen **benutzerdefinierte Warenkorbwerte für jede Währung festlegen** möchten, klicken Sie nach dem Festlegen des Werts für Ihren Hauptmarkt (Minimum ist 0) auf „Währung hinzufügen“ und geben Sie den Wert ein.&#x20;

_Beispiel: Kunden aus Europa müssen 300 € ausgeben, um das Geschenk zu erhalten, während australische Kunden nur 100 A$ ausgeben müssen._

* **Die Bedingung gilt für:**

▶ Beliebige Produkte: Alle Produkte im Warenkorb werden auf die Warenkorbwert-Bedingung angerechnet.

▶ Alle außer ausgewählte Produkte: Alle außer den ausgewählten Produkten werden auf die Warenkorbwert-Bedingung angerechnet.

▶ Alle außer ausgewählte Produktarten/Verkäufer/Sammlungen: Alle außer den Produkten, die durch die Bedingung Produktarten/Verkäufer/Sammlungen ausgewählt wurden, werden auf die Warenkorbwert-Bedingung angerechnet.

▶ Ausgewählte Produkte: Nur die unten ausgewählten Produkte werden auf die Warenkorbwert-Bedingung angerechnet.

▶ Produkte in ausgewählten Produktarten/Verkäufern/Sammlungen: Nur die Produkte, die durch die Bedingung Produktarten/Verkäufer/Sammlungen ausgewählt wurden, werden auf die Warenkorbwert-Bedingung angerechnet.

#### **2.2. Zustand der Warenkorbmenge**

<figure><img src="../../.gitbook/assets/image (97).png" alt=""><figcaption></figcaption></figure>

* Min: Mindestwarenkorbmenge, die Kunden erreichen müssen, um das Geschenk des Angebots zu erhalten.
* Max: Maximale Warenkorbmenge, die Kunden nicht überschreiten dürfen, um das Geschenk des Angebots zu erhalten.

**Die Bedingung gilt für:**

▶ Beliebige Produkte: Alle Produkte im Warenkorb werden auf die Warenkorbmengen-Bedingung angerechnet.

▶ Alle außer ausgewählte Produkte: Alle außer den ausgewählten Produkten werden auf die Warenkorbmengen-Bedingung angerechnet.

▶ Alle außer ausgewählte Produktarten/Verkäufer/Sammlungen: Alle außer den Produkten, die durch die Bedingung Produktarten/Verkäufer/Sammlungen ausgewählt wurden, werden auf die Warenkorbmengen-Bedingung angerechnet.

▶ Ausgewählte Produkte: Nur die unten ausgewählten Produkte werden auf die Warenkorbmengen-Bedingung angerechnet.

▶ Produkte in ausgewählten Produktarten/Verkäufern/Sammlungen: Nur die Produkte, die durch die Bedingung Produktarten/Verkäufer/Sammlungen ausgewählt wurden, werden auf die Warenkorbmengen-Bedingung angerechnet.

#### **2.3. Bedingung für ein bestimmtes Produkt**

<figure><img src="../../.gitbook/assets/image (98).png" alt=""><figcaption></figcaption></figure>

* Erforderliche Anzahl an Produkten: Anzahl der Produkte, die Kunden kaufen müssen, um Geschenke zu erhalten.
* Geschenke mit Anzahl der Produkte multiplizieren: Wenn Kunden mehr als die erforderlichen Produkte kaufen, erhalten sie mehr Geschenke.&#x20;

_Beispiel: Kaufen Sie 2, erhalten Sie 1; kaufen Sie 4, erhalten Sie 2; kaufen Sie 6, erhalten Sie 3, und so weiter._

* Geschenk ist identisch mit den ausgewählten Produkten: Mit diesem Feld können Sie wählen, ob das Geschenk dasselbe Produkt oder ein völlig anderes Geschenk ist.

#### **2.4. Bedingung für den Warenkorbwert-Multiplikator**

<figure><img src="../../.gitbook/assets/unknown (103).png" alt="" width="563"><figcaption></figcaption></figure>

* Mit dieser Bedingung können Sie einen Warenkorbwert-Schwellenwert festlegen, der die Anzahl der Geschenke, die Kunden erhalten können, vervielfacht.
* Der eingegebene Warenkorbwert basiert auf der Hauptwährung Ihres Shops (z. B. SGD, wie im Bild gezeigt).

_Beispiel: Kunden erhalten 1 Geschenk bei einem Einkaufswert von 200 $, 2 Geschenke bei 400 $ usw._

* **Für Shops mit eingerichtetem Shopify Markets:**

<figure><img src="../../.gitbook/assets/unknown (102).png" alt="" width="563"><figcaption></figcaption></figure>

Normalerweise rechnet BOGOS Ihre Hauptwährung automatisch anhand des Wechselkurses von Shopify in die Währung der Kunden um (z. B. 1 SGD = 0,666 €).

Wenn Sie jedoch stattdessen **benutzerdefinierte Warenkorbwerte für jede Währung festlegen** möchten, klicken Sie nach dem Festlegen des Warenkorbwerts für Ihren Hauptmarkt auf „Währung hinzufügen“ und geben Sie den Wert ein.

_Beispiel: Kunden aus Europa müssen 300 € ausgeben, um das Geschenk zu erhalten, während australische Kunden nur 100 A$ ausgeben müssen._

#### **2.5. Bedingung für ein Paket von Produkten**

<figure><img src="../../.gitbook/assets/image (102).png" alt=""><figcaption></figcaption></figure>

* Bedingung „Paket von Produkten“: Kunden erhalten die Geschenke nur, wenn sie alle ausgewählten Produkte kaufen.
* Bedingung „Paket von Produkten“ überprüfen:

▶ Nach Produkten: Kunden müssen mindestens eine Variante jedes ausgewählten Produkts kaufen, um Geschenke zu erhalten.

▶ Nach Varianten: Kunden müssen alle Varianten aller ausgewählten Produkte kaufen, um Geschenke zu erhalten.

* Geschenke mit Anzahl der Pakete multiplizieren: Je mehr Pakete gekauft werden, desto mehr Geschenke erhalten Kunden.

### 3. Unterbedingungen des Angebots&#x20;

Diese Unterbedingungen sind optional einzurichten. Sie fügen weitere Bedingungen hinzu, die Kunden erfüllen müssen, um die Geschenke zu erhalten. Alle Unterbedingungen finden Sie hier.

<figure><img src="../../.gitbook/assets/unknown (66).png" alt=""><figcaption></figcaption></figure>

Sie können beliebige Bedingungen miteinander kombinieren, um Angebote speziell für Ihre Kunden zu erstellen.

#### **3.1. Spezifische Linkadresse**

<figure><img src="../../.gitbook/assets/Specific link URL.jpg" alt=""><figcaption></figcaption></figure>

Diese Bedingung erlaubt nur Kunden, die über einen bestimmten Link auf Ihren Shop zugreifen, Geschenke zu erhalten. Geben Sie ein Wort ein, um die URL für jede Kampagne anzupassen. Diese Funktion eignet sich am besten für Social- und E-Mail-Kampagnen.

**Den Angebotslink anpassen:**

Alternativ können Sie, wenn Sie den Parameter zu einem bestehenden Link in Ihrem Shop hinzufügen möchten, die Option „Parameter kopieren“ verwenden, um nur den Parameter zu kopieren (z. B. ?freegifts\_code=summersale2024).

{% hint style="warning" %}
Wenn die URL, zu der Sie den Parameter hinzufügen, bereits ein ?-Symbol enthält (z. B. https://yourstore.com/product?variant=12345), **ändern Sie das ? im Parameter in &**:

**Ursprünglicher Parameter:** ?freegifts\_code=summersale2024

**Angepasster Parameter für eine bestehende Abfrage:** \&freegifts\_code=summersale2024
{% endhint %}

{% embed url="https://www.youtube.com/watch?v=1huoyancpmg&list=PLfZvxg1NZTJgkPK3iPXFBivJcXPpIHY33&index=4" %}

#### **3.2. Bestellhistorie der Kunden**

<figure><img src="../../.gitbook/assets/image (105).png" alt=""><figcaption></figcaption></figure>

Diese Unterbedingung schränkt das Angebot nur auf Kunden mit einer bestimmten Bestellhistorie ein.

* Gesamtausgaben in der Bestellhistorie: Gesamtbestellwert in der Bestellhistorie der Kunden.
* Ausgaben bei der letzten Bestellung: Wert der letzten Bestellung.
* Gesamtanzahl aufgegebener Bestellungen: Gesamtanzahl der Bestellungen in der Bestellhistorie.
* Auf eine Nutzung pro Kunde beschränken: Ein Kunde kann das Geschenk aus diesem Angebot nur einmal erhalten. Sobald eine Bestellung mit dem Geschenk dieses Angebots aufgegeben wurde, ist der Kunde für dieses Angebot nicht mehr berechtigt.

Sie können bei „Gesamtanzahl aufgegebener Bestellungen“ 0 als Maximum eingeben, um ein Angebot nur für Neukunden zu erstellen.\
Diese Unterbedingung erfordert, dass sich Kunden in Ihrem Shop anmelden.

{% embed url="https://youtu.be/Fngi7aS1AYU" %}

#### **3.3. Kundentags**

<figure><img src="../../.gitbook/assets/image (106).png" alt=""><figcaption></figcaption></figure>

Mit dieser Funktion können Sie das Angebot auf Kunden ausrichten, die bestimmte Tags haben oder nicht haben.\
Diese Unterbedingung erfordert, dass sich Kunden in Ihrem Shop anmelden.

{% embed url="https://www.youtube.com/watch?v=ZFce5y1g7Ws" %}

#### **3.4. Kundenstandort**

<figure><img src="../../.gitbook/assets/image (107).png" alt=""><figcaption></figcaption></figure>

Nutzen Sie diese Option, wenn Ihre Geschenkangebote **nur für Kunden aus einem bestimmten Land** verfügbar sein sollen.

Um umgekehrt Kunden aus einem bestimmten Land von Ihren Angeboten auszuschließen, wählen Sie dieses Land aus und aktivieren Sie das Kontrollkästchen „Kunden aus ausgewählten Standorten ausschließen“.

{% embed url="https://www.youtube.com/watch?v=aD5Kh6BJm1o&list=PLfZvxg1NZTJgkPK3iPXFBivJcXPpIHY33&index=3" %}

#### 3.5.  Märkte

<figure><img src="../../.gitbook/assets/unknown (105).png" alt=""><figcaption></figcaption></figure>

Nutzen Sie diese Option, wenn Ihr Angebot **nur Kunden aus Märkten angezeigt werden soll, die eine Gruppe von Ländern oder Regionen umfassen**, die bereits in Shopify Markets eingerichtet sein sollten.

* Wählen Sie zur Einrichtung einfach die Shopify-Märkte aus, in denen Ihre Geschenkangebote gelten sollen.
* Um umgekehrt Kunden aus bestimmten Märkten auszuschließen, wählen Sie diese Märkte aus und aktivieren Sie das Kontrollkästchen „Kunden aus ausgewählten Märkten ausschließen“.

{% hint style="warning" %}
Wenn Sie diesen gelben Hinweis sehen, bedeutet das, dass BOGOS Ihre Shopify-Markets-Daten nicht lesen kann. Klicken Sie auf „Berechtigungen aktualisieren“, um die Synchronisierung zu aktivieren.
{% endhint %}

<figure><img src="../../.gitbook/assets/unknown (106).png" alt="" width="456"><figcaption></figcaption></figure>

#### 3.6.  Abonnementprodukte

<figure><img src="../../.gitbook/assets/image (108).png" alt=""><figcaption></figcaption></figure>

Standardmäßig funktionieren BOGOS-Angebote sowohl mit Einmalkauf- als auch mit Abonnementprodukten.&#x20;

Mit dieser Funktion können Sie das Angebot auf nur eine Produktart einschränken.

#### 3.7. Verkaufskanäle

<figure><img src="../../.gitbook/assets/image (109).png" alt=""><figcaption></figcaption></figure>

Mit dieser Funktion können Sie Angebote für Kunden aus mehreren Verkaufskanälen erstellen: Online-Shop, mobile App und Point-of-Sale-Kanal.

#### **3.8. Produktmengenlimits**

<figure><img src="../../.gitbook/assets/unknown (67).png" alt=""><figcaption></figcaption></figure>

Verwenden Sie dies, um **zusätzliche Mengenregeln** für Ihre Hauptbedingung hinzuzufügen. Die Artikel im Warenkorb müssen diese Limits erfüllen, um sich für das Geschenk zu qualifizieren.

**Beliebte Anwendungsfälle:**

* Kaufen Sie mindestens 2 Artikel aus Sammlung A und 1 Artikel aus Sammlung B, um ein Geschenk zu erhalten.
* Geben Sie 250 $+ aus und legen Sie mindestens 1 Produkt A in den Warenkorb, um ein Geschenk zu erhalten.
* Kaufen Sie aus einer Sammlung (ausgenommen Produkt A), um ein Geschenk zu erhalten.
* Kaufen Sie aus Sammlung A (ausgenommen Produkte, die auch in Sammlung B vorkommen), um ein Geschenk zu erhalten.
* Kein Geschenk, wenn sich bestimmte Artikel im Warenkorb befinden, selbst wenn die Hauptbedingungen erfüllt sind.

**So richten Sie es ein:**

{% embed url="https://youtu.be/fQQSJ1LOJIg?si=Lys2gnF2Plyx25Oz" %}

1. Wählen Sie **Kunden müssen erreichen** (wenn Sie mehrere Regeln festlegen möchten):

* **Alle Regeln** (UND): Der Kunde muss alle unten festgelegten Regeln erfüllen, um das Geschenk zu erhalten.
* **Beliebige Regel** (ODER): Die Erfüllung nur einer Ihrer Regeln reicht aus, um sich zu qualifizieren.

2. Wählen Sie die Regel **Kaufen** aus und **geben Sie ein, wie viele Artikel** benötigt werden, um die Anforderung zu erfüllen.

* **Mindestens**: Der Warenkorb muss diese Anzahl an Artikeln aus Ihren ausgewählten Produkten enthalten, entsprechend oder größer (≥).
* **Höchstens:** Der Warenkorb darf höchstens (≤) diese Anzahl an Artikeln aus Ihren ausgewählten Produkten enthalten.

3. Wählen Sie die Regel **Von**, damit die oben festgelegte Menge auf die ausgewählten Produkte/Produktarten/Verkäufer/Sammlungen angewendet wird.
4. Wählen Sie die gewünschten Produkte/Produktarten/Verkäufer/Sammlungen aus.
5. Um mehrere Regeln zu stapeln, klicken Sie auf **Regel hinzufügen** und wiederholen Sie den Vorgang – sie folgen Ihrer Auswahl „Alle Regeln“/„Beliebige Regel“.

{% hint style="success" %}
* Um bestimmte Produkte **auszuschließen**, stellen Sie „Kaufen“ auf „Höchstens 0“ aus „ausgewählte Produkte: Produkt A“.
* Um eine **genaue Menge** an Artikeln zu verlangen, legen Sie „Alle Regeln“ mit sowohl „Mindestens X“ als auch „Höchstens X“ fest (mit derselben Zahl X).
{% endhint %}

{% hint style="warning" %}
**Kostenlose Geschenke aus anderen Angeboten zählen nicht für diese Regel**.&#x20;

Beispiel: Wenn Ihre Regel den Kauf von Produkt A erfordert, zählt ein kostenloses Produkt A, das durch ein anderes Angebot hinzugefügt wurde, nicht mit. Der Kunde muss ein weiteres Produkt A kaufen, um sich zu qualifizieren.
{% endhint %}

### 4. Geschenke auswählen

<figure><img src="../../.gitbook/assets/unknown (107).png" alt="" width="563"><figcaption></figcaption></figure>

Hier wählen Sie die Geschenke aus, die Sie anbieten möchten, und wenden Rabatte darauf an.

1. **Rabattart für das Geschenk wählen:**

▶ Wenn Sie **ein normales Produkt als Geschenk** wählen, gibt es 3 Rabattarten:

* **Prozentsatz:** Der Geschenkpreis wird vom Originalpreis um einen Prozentsatz des Originalpreises reduziert. 100 % bedeutet ein kostenloses Geschenk.
* **Betrag:** Der Geschenkpreis wird vom Originalpreis um einen Geldbetrag reduziert.
* **Festpreis:** Legen Sie einen Festpreis für Ihre Geschenke fest, der niedriger oder höher als der Originalpreis sein kann.

{% hint style="info" %}
**Bei der Gift Function** darf der Festpreis nicht höher sein als der Originalpreis des Produkts (aufgrund der Shopify-Regeln).&#x20;

Um einen höheren Festpreis festzulegen, wechseln Sie bitte den Geschenklogik-Mechanismus zu „Produkt klonen“.
{% endhint %}

▶ Wenn Sie **einen Versandrabatt als Geschenk** wählen, gibt es 2 Rabattarten:

<figure><img src="../../.gitbook/assets/unknown (108).png" alt="" width="563"><figcaption></figcaption></figure>

* **Prozentsatz:** Die ursprünglichen Versandkosten werden um einen Prozentsatz reduziert. 100 % bedeutet kostenloser Versand.
* **Betrag:** Die ursprünglichen Versandkosten werden um einen festen Betrag reduziert. Wenn Sie in verschiedenen Währungen verkaufen (in Shopify Markets eingerichtet), können Sie **„Währung hinzufügen“** verwenden und festlegen, wie hoch der Versandrabattbetrag in jeder Währung sein soll, anstatt die Wechselkurse von Shopify zu verwenden (z. B. SGD 100, 8 €, 12 A$).



2. **Wählen Sie, wie der Kunde das Geschenk erhält** (wählen Sie, wie Kunden ihre Geschenke erhalten):

* _Alle Geschenke automatisch:_ Sobald die Bedingung erfüllt ist, werden Geschenke automatisch dem Warenkorb des Kunden hinzugefügt.
* _Anzahl der Geschenke, die der Kunde erhält_: Sobald die Bedingung erfüllt ist, werden die Geschenke in einem Geschenk-Schieberegler angezeigt, aus dem Kunden auswählen können.

{% hint style="info" %}
Hinweis: Wenn Sie das Erscheinungsbild des Geschenk-Schiebereglers anpassen möchten, gehen Sie zu [Geschenk-Schieberegler anpassen](../customize/customize-gift-slider.md)
{% endhint %}

3. **Geschenke auswählen:**&#x20;

* Wählen Sie ein Produkt/mehrere Produkte oder Variante(n) aus, die als Geschenke angeboten werden.
* Legen Sie die Menge für jedes Geschenk fest (falls „Alle Geschenke automatisch“ ausgewählt ist). Wenn Kunden sich qualifizieren, werden Geschenke automatisch in den von Ihnen festgelegten Mengen dem Warenkorb hinzugefügt.

<figure><img src="../../.gitbook/assets/unknown (165).png" alt="" width="507"><figcaption></figcaption></figure>

{% hint style="warning" %}
Die folgenden Produktarten KÖNNEN NICHT als Geschenke ausgewählt werden und werden automatisch entfernt, wenn sie versehentlich ausgewählt wurden:

* Geklonte Geschenke (erstellt durch den Geschenk-Klon-Mechanismus).
* Bundle als separates Produkt (erstellt durch das klassische Bundle).
{% endhint %}

### 5. Erweiterte Konfiguration (optional)

#### 5.1. Funktioniert mit anderen Angeboten

<figure><img src="../../.gitbook/assets/image (111).png" alt=""><figcaption></figcaption></figure>

* _**Priorität:**_ Legen Sie eine numerische Prioritätsstufe für dieses Angebot fest. Angebote mit einer niedrigeren Zahl (z. B. 1) haben eine höhere Priorität als solche mit höheren Zahlen (z. B. 2, 3). Dies beeinflusst, wie mehrere Angebote angewendet werden, wenn Kunden sich für mehr als eines qualifizieren.



* _**Angebote mit niedrigerer Priorität stoppen:**_ Aktivieren Sie diese Einstellung, um Angebote mit niedrigerer Priorität automatisch zu stoppen, wenn Kunden die Bedingungen für dieses Angebot mit höherer Priorität erfüllen. Wenn dieses Angebot beispielsweise auf Priorität 1 gesetzt ist, werden Angebote mit Priorität 2, 3 usw. nicht angewendet, wenn die Bedingungen für Priorität 1 erfüllt sind.



* _**Geschenk wird auf andere Angebote angerechnet:**_ Wenn ausgewählt, wird der Wert des Geschenks in diesem Angebot auf die Mindestkaufanforderungen anderer Angebote angerechnet (nur wenn das Geschenk einen Preis über 0 $ hat). Dies kann Kunden helfen, sich leichter für mehrere Aktionen zu qualifizieren.

#### **5.2. Warenkorbnachricht**

<figure><img src="../../.gitbook/assets/image (112).png" alt=""><figcaption></figcaption></figure>

_**Warenkorbnachricht hinzufügen:**_ Mit dieser Option können Sie eine benutzerdefinierte Nachricht hinzufügen, die auf der Warenkorbseite angezeigt wird, wenn dieses Angebot aktiv ist.

Weitere Details finden Sie unter [Warenkorbnachricht anpassen](../customize/customize-cart-message.md).

#### **5.3. Heute-Angebot**

<figure><img src="../../.gitbook/assets/image (115).png" alt=""><figcaption></figcaption></figure>

* **Angebotstitel:** Geben Sie einen Titel ein, der im Heute-Angebot-Widget im Online-Shop Ihres Shops angezeigt wird. Eine Änderung hier ändert nicht den ursprünglichen Titel des Angebots.
* **Weiterleitungsschaltfläche hinzufügen:** Sie können dem Heute-Angebot-Widget eine anklickbare Schaltfläche hinzufügen, die zu dem Ort führt, an dem Kunden das Angebot einlösen sollen.

Weitere Details finden Sie unter [Heute-Angebot anpassen](../boosters/create-today-offer-widget.md).

#### **5.4. Benutzerdefinierten Rabattcode hinzufügen**

In diesem Abschnitt können Sie den Namen des Rabattcodes an Ihre Marke anpassen.

<figure><img src="../../.gitbook/assets/image (320).png" alt=""><figcaption></figcaption></figure>

\
**Bitte beachten:**&#x20;

* Diese Option erscheint automatisch, wenn Ihre Geschenklogik auf „Gift Function“ eingestellt ist.
* Wenn Ihr Shop die Geschenk-Klon-Logik verwendet, ist diese Option nur verfügbar, wenn Sie den Versandrabatt als Geschenk auswählen.
* Der Name des Rabattcodes muss unter 256 Zeichen liegen und über alle Shopify-Rabatte hinweg eindeutig sein.

Wählen Sie dann, ob das Angebot mit **Bestellungsrabatten** oder **Versandrabatten** kombiniert werden soll.

### Häufig gestellte Fragen

<details>

<summary><strong>Wie kann ich Kunden erlauben, ihr Geschenk auszuwählen?</strong></summary>

Sie können Kunden ihr eigenes Geschenk auswählen lassen, anstatt es automatisch dem Warenkorb hinzuzufügen. Es gibt zwei Möglichkeiten, dies in BOGOS einzurichten:

**Option 1: In dem Geschenkangebot einrichten**

Wählen Sie beim Erstellen oder Bearbeiten eines Geschenkangebots unter „Geschenke auswählen“ > „Wählen Sie, wie der Kunde das Geschenk erhält“ die Option „Anzahl der Geschenke, die der Kunde erhält“ aus und geben Sie ein, wie viele Geschenke der Kunde auswählen kann.

**Option 2: Automatisches Hinzufügen in den Einstellungen deaktivieren**

Gehen Sie zu Einstellungen → Geschenkbedingung und deaktivieren Sie „Geschenk automatisch zum Warenkorb hinzufügen“. Dadurch wird der Geschenk-Schieberegler immer angezeigt – selbst wenn Sie in Ihrem Geschenkangebot „Alle Geschenke automatisch“ ausgewählt haben.

Wenn Kunden sich für das Angebot qualifizieren, erscheint ein Geschenk-Schieberegler mit allen verfügbaren Optionen zur Auswahl. Sie können den Text, die Farben, das Layout und die Produktanzeige des Schiebereglers unter Anpassen → Geschenk-Schieberegler ändern.

</details>

<details>

<summary><strong>Kann ich meine Geschenkangebote auf Kunden in bestimmten Ländern beschränken?</strong></summary>

Ja. Unter **Unterbedingungen** können Sie die Funktion **Kundenstandort** oder **Märkte** verwenden, um sicherzustellen, dass Geschenke nur Kunden in Ihren ausgewählten Regionen zur Verfügung stehen, synchronisiert direkt mit Shopify Markets.

{% hint style="info" %}
Die Standorteinstellung basiert auf der aktuellen Verbindung des Kunden (dessen IP-Adresse oder VPN), während die Markteinstellung den spezifischen Daten und Regionen folgt, die Sie bereits in Ihren Shopify-Markets-Einstellungen festgelegt haben.
{% endhint %}

**Bitte folgen Sie diesen Schritten:**\
1\. Gehen Sie zum Angebot\
2\. Fügen Sie die Unterbedingung hinzu.

![](<../../.gitbook/assets/unknown (196).png>)\
\
3\. Wählen Sie Kundenstandort oder Kundenmärkte<br>

![](<../../.gitbook/assets/unknown (197).png>)

4\. Fügen Sie das gewünschte Land oder die gewünschten Märkte hinzu\
5\. Speichern

</details>

<details>

<summary><strong>Ich möchte nur meine VIP-Kunden belohnen. Ist das möglich?</strong></summary>

Ja! Sie können eine **Kundentag**-Unterbedingung festlegen. Das Geschenk wird nur angemeldeten Kunden angeboten, die das bestimmte Tag (z. B. „VIP“ oder „Mitglied“) in ihrem Shopify-Profil haben.\
\
**Bitte folgen Sie diesen Schritten:**\
1\. Gehen Sie zum Angebot\
2\. Unterbedingung hinzufügen<br>

![](<../../.gitbook/assets/unknown (198).png>)

3\. Wählen Sie Kundentags<br>

![](<../../.gitbook/assets/unknown (199).png>)

4\. Fügen Sie das gewünschte Tag hinzu<br>

![](<../../.gitbook/assets/unknown (200).png>)

5\. Speichern.

</details>

<details>

<summary><strong>Gibt es eine Möglichkeit, Geschenke ausschließlich über eine Marketing-E-Mail oder einen Influencer-Link anzubieten?</strong></summary>

Ja. Sie können die Unterbedingung **Spezifische Linkadresse** verwenden. Dadurch wird sichergestellt, dass nur Kunden, die über diese eindeutige URL Ihren Shop betreten, das Geschenkangebot sehen und erhalten.\
\
**Bitte folgen Sie diesen Schritten:**\
1\. Gehen Sie zum Angebot\
2\. Unterbedingung hinzufügen<br>

![](<../../.gitbook/assets/unknown (201).png>)

3\. Klicken Sie auf Spezifische Linkadresse<br>

![](<../../.gitbook/assets/unknown (202).png>)

4\. Fügen Sie einen einfachen Text hinzu, damit die App den Link generiert

![](<../../.gitbook/assets/unknown (37).png>)

5\. Kopieren Sie den Link und speichern Sie. Anschließend können Sie den Link per E-Mail-Kampagne an die Personen senden, die Sie belohnen möchten.

</details>

<details>

<summary><strong>Was ist der Unterschied zwischen den Geschenk-App-Mechanismen?</strong></summary>

**1. Produkte klonen:** Geschenkprodukte werden indirekt dem Warenkorb hinzugefügt, indem mithilfe der BOGOS-Funktion doppelte Versionen des Originalprodukts mit einem reduzierten Preis erstellt werden. Dies ermöglicht es Kunden, an der Kasse einen Rabattcode zu verwenden. Sie können das Geschenkinventar in den Einstellungen verwalten.

[Anleitung ansehen.](https://youtu.be/gXwkfsbsWgI?si=M0TTUqjOFRReHsmb\&t=90)

**2. Gift Function:** Diese Option erstellt keine geklonten Produkte. Geschenkprodukte werden direkt als Originalprodukte dem Warenkorb hinzugefügt und mit der integrierten Rabattfunktion von Shopify reduziert.

[Anleitung ansehen.](https://youtu.be/gXwkfsbsWgI?si=XynDYGtVgg_Gdq6-\&t=147)

</details>

<details>

<summary><strong>Wie biete ich ein kostenloses Geschenk mit einem Rabattcode an?</strong></summary>

Die einzige Möglichkeit, einem Kunden ein kostenloses Geschenk anzubieten, nachdem er einen Rabattcode bei Shopify eingegeben hat, besteht darin, einen **Checkout-Upsell** einzurichten – dies ist jedoch **nur für Shopify-Plus-Shops verfügbar**.

**So richten Sie es ein:**

1. Richten Sie zunächst einen Rabattcode in den integrierten Rabatten von Shopify ein. Wählen Sie „Betrag auf Produkte“ > geben Sie Ihren bevorzugten Code ein > geben Sie 0 als Rabattwert ein > aktivieren Sie unter „Kombinationen“ die Option „Produktrabatte“ > Speichern
2. Gehen Sie zu „Alle Angebote“ > „Upsell-Angebot erstellen“ > wählen Sie „Checkout-Upsell“
3. Wählen Sie einen Upsell-Auslöser
4. Wählen Sie eine Upsell-Methode
5. Stellen Sie die Rabattart auf „Prozentsatz“ ein und geben Sie 100 ein, um es kostenlos zu machen
6. Aktivieren Sie unter „Erweiterte Konfiguration“ die Option „Rabattcode“ > geben Sie genau den Rabattcode aus Schritt 1 ein
7. Wählen Sie entweder „Produkte auf der Checkout-Seite anzeigen“ oder „Produkte automatisch zum Warenkorb hinzufügen“
8. Klicken Sie auf „Veröffentlichen“

[Anleitung ansehen.](https://youtu.be/kWeZvSDxRkg?si=m4YcbI_3FLev32b3)

</details>

<details>

<summary><strong>Wie richte ich eine Geschenkkarte korrekt als Geschenk ein?</strong></summary>

Sie können Ihre Kunden ganz einfach mit einer digitalen Geschenkkarte belohnen, wenn sie bestimmte Artikel kaufen. So richten Sie es ein:

**1. Erstellen Sie Ihr Angebot**

* Gehen Sie zu „Alle Angebote“ > „Geschenkangebot erstellen“.
* Wählen Sie unter „Hauptbedingung“ die spezifischen Produkte aus, die Kunden kaufen müssen, um sich zu qualifizieren.
* Scrollen Sie nach unten zum Abschnitt „Geschenkauswahl“ und wählen Sie Ihr Geschenkkartenprodukt aus.

**2. Einstellungen für Nutzer von „Produkt klonen“ anpassen**&#x20;

Wenn Ihr Shop den Mechanismus „Produkt klonen“ verwendet, müssen Sie eine kurze Anpassung vornehmen, um sicherzustellen, dass die Geschenkkarten geliefert werden:

* Navigieren Sie zu BOGOS-Einstellungen > Draft-Order-API.
* Aktivieren Sie die Draft-Order-API.
* Stellen Sie sicher, dass Sie für beide Optionen „Rabatt nicht zulassen“ auswählen.

**So funktioniert es:** Sobald die Bestellung abgeschlossen ist, erhalten Ihre Kunden automatisch ihren Geschenkkartencode per E-Mail.

{% hint style="success" %}
Profi-Tipp: Wenn Sie eine einfachere Einrichtung bevorzugen, können Sie Ihren App-Mechanismus in den Einstellungen auf **Gift Function** umstellen. Dadurch können Sie Geschenkkarten wie jedes andere Standardgeschenk in Ihrer Angebotseinrichtung auswählen und verwalten.
{% endhint %}

</details>
