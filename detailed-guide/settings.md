# Einstellungen

## 1. Allgemeine Einstellungen

<figure><img src="../.gitbook/assets/image (197).png" alt=""><figcaption></figcaption></figure>

* **BOGOS-Status**: Aktivieren Sie den BOGOS-Status, damit die App in Ihrem Onlineshop funktioniert.&#x20;
* **Zeitzone**: Die Uhrzeit wird basierend auf der Zeitzone Ihres Geräts angezeigt&#x20;
* **App-Sprache**: Ändern Sie die App-Sprache passend zu Ihrer Muttersprache&#x20;

## 2. Geschenklogik-Mechanismus

{% embed url="https://youtu.be/gXwkfsbsWgI?si=1BbGRUUuEAqNRGNJ" %}

<figure><img src="../.gitbook/assets/image (253).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Eine Änderung der Logik wirkt sich auf alle Angebote aus und entfernt alle vorhandenen geklonten Produkte aus Ihrem Shop. Möglicherweise müssen Sie Angebote erneut aktivieren, nachdem die App den Logikwechsel abgeschlossen hat.

**BOGOS empfiehlt, den Support zu kontaktieren**, bevor Sie die Logik ändern, um einen reibungslosen Übergang sicherzustellen.
{% endhint %}

BOGOS bietet zwei Geschenklogik-Mechanismen:

### **2.1. Produkt klonen (Standard)**

{% hint style="success" %}
Kompatibel mit POS, Mobile App, Headless, Drittanbieter-Checkout, Fulfillment-App.
{% endhint %}

Wenn ein Geschenkangebot erstellt wird, erstellt BOGOS automatisch ein Duplikat (einen „Klon“) des ursprünglichen Geschenkprodukts im Shopify-Produktkatalog des Händlers.

Diese geklonten Produkte/Geschenke:

* sind im Storefront/in der Shop-Suche ausgeblendet
* sind mit „bogos-gift“ getaggt
* fügen dem Warenkorb die geklonte Kopie anstelle der Originalprodukte hinzu.

{% hint style="info" %}
Da es sich um einen separaten Produkteintrag handelt, bietet dies BOGOS deutlich mehr Flexibilität: Geschenke aus der Suche ausblenden (um ein Überraschungsgeschenk zu erstellen), individuelles Bild/Titel für diese geklonten Geschenke, keine Begrenzung der Anzahl erstellter Geschenkangebote usw.)
{% endhint %}

{% hint style="warning" %}
Um den Lagerbestand der geklonten Geschenke zu verwalten (z. B. Synchronisation mit dem Lagerbestand der Originalprodukte), lesen Sie bitte [5. Verwaltung des Geschenkbestands](settings.md#id-5.-gift-inventory-management).
{% endhint %}

### **2.2. Geschenkfunktion**

{% hint style="warning" %}
Nicht kompatibel mit Mobile App, Headless oder Drittanbieter-Checkout.
{% endhint %}

Geschenke werden als Ihre Original-Shopify-Produkte zum Warenkorb hinzugefügt und über die native Rabattfunktion von Shopify rabattiert.

Zum Beispiel: Das Limit von 100 Rabatten pro Shop darf nicht überschritten werden.

## 3. Geschenkbedingung

<figure><img src="../.gitbook/assets/image (198).png" alt=""><figcaption></figcaption></figure>

### 3.1. Geschenk automatisch zum Warenkorb hinzufügen&#x20;

Wenn im Angebot nur ein Geschenk ausgewählt ist, wird dieses Geschenk automatisch zum Warenkorb der Kunden hinzugefügt. Wenn Sie diese Funktion deaktivieren, werden Geschenkprodukte immer in einem Geschenk-Slider angezeigt.

### 3.2. Geschenkrabatt berechnet nach <a href="#gift-discount-calculated-by" id="gift-discount-calculated-by"></a>

Der Geschenkrabattprozentsatz kann basierend auf dem Derzeitigen Preis oder dem Vergleichspreis berechnet werden.

### 3.3. Geschenkpreis muss geringer als/gleich den Produkten sein

Diese Funktion beschränkt Kunden darauf, nur Geschenke mit einem niedrigeren Preis als die Artikel in ihrem Warenkorb zu erhalten. Der Preis des Geschenkartikels kann basierend auf dem Derzeitigen Preis oder dem Vergleichspreis berechnet werden.

### 3.4. Beschränken Sie eine Auswahl pro Geschenk auf dem Geschenkschieberegler&#x20;

Diese Funktion hindert Kunden daran, einen Geschenkartikel ein **zweites Mal** aus dem Geschenk-Slider auszuwählen. Sie können diesen Geschenkartikel nicht mehr auswählen, selbst wenn sie die Bedingungen anderer Angebote mit demselben Geschenk erfüllen.

### 3.5. Produkt im Warenkorb ausschließen&#x20;

Diese Funktion hindert Kunden daran, ein Geschenk zu erhalten, wenn sie denselben Artikel bereits im Warenkorb haben.

## 4. Klon-Geschenkprodukt&#x20;

{% embed url="https://youtu.be/2-Bg_Ep7W5s?si=iQ9xVWQ6AiVyUGFQ" %}

Legen Sie fest, welche Informationen das Geschenkprodukt vom Originalprodukt übernimmt&#x20;

<figure><img src="../.gitbook/assets/image (199).png" alt=""><figcaption></figcaption></figure>

### 4.1. Geschenkprodukte nach dem Deaktivieren der Angebote löschen&#x20;

Diese Funktion ist standardmäßig immer aktiviert, sodass alle geklonten Produkte nach der Deaktivierung der Angebote entfernt werden können.&#x20;

### 4.2. Vergleichspreis im Geschenkprodukt einbeziehen

Wenn Sie diese Funktion aktivieren, wird das Geschenkprodukt angezeigt. Sobald diese Einstellung aktiviert ist, wird das Geschenkprodukt mit einem durchgestrichenen Preis im Warenkorb des Kunden angezeigt.

### 4.3. SKU/Barcode-Format der Geschenkprodukte

Standardmäßig haben die von unserer App geklonten Geschenkprodukte dieselbe SKU/denselben Barcode wie das Original.

Sie können Ihr SKU/Barcode-Format auch zwischen den folgenden Optionen anpassen:&#x20;

* Wie das Originalprodukt&#x20;
* Wie das Originalprodukt mit einem Suffix. Z. B. SKU (100%OFF)
* Leer&#x20;

Dies hilft, wenn Sie ein Bestandsverwaltungssystem oder einen Drittanbieter-Fulfillment-Dienst für Ihren Shop verwenden.

### 4.4. Titelformat des Geschenkprodukts&#x20;

Bitte wählen Sie Ihr bevorzugtes Format aus den folgenden 3 Optionen. Bitte aktivieren Sie die Angebote erneut, nachdem Sie diese Einstellung geändert haben.

<figure><img src="../.gitbook/assets/image (200).png" alt=""><figcaption></figcaption></figure>

### 4.5. Verkaufskanäle&#x20;

Standardmäßig werden die Geschenkprodukte nur im Onlineshop veröffentlicht. Wenn Sie andere Verkaufskanäle wie POS oder Mobile App haben, können Sie diese mit dieser Funktion automatisch veröffentlichen.

{% hint style="warning" %}
Bitte überprüfen Sie Ihre Kampagne sorgfältig und kontaktieren Sie unser Support-Team, wenn Sie planen, die Angebote auf vielen verschiedenen Kanälen auszuführen.
{% endhint %}

### 4.6. Weitere Originalproduktdetails einbeziehen

Standardmäßig duplizieren wir die Informationen der Originalprodukte nicht in den Geschenkprodukten. Diese Einstellung ermöglicht es Ihnen jedoch, sie automatisch einzubeziehen.

* Produktart
* Stichworte

## 5. Verwaltung des Geschenkbestands&#x20;

{% hint style="warning" %}
Nur verfügbar für den [Mechanismus zum Klonen von Geschenken](settings.md#id-2.-gift-logic-mechanism).
{% endhint %}

<img src="../.gitbook/assets/unknown (286).png" alt="" height="263" width="624">

### **5.1. Lagerbestand des geklonten Geschenks verfolgen und anpassen**

Standardmäßig wird der Lagerbestand des geklonten Geschenks nicht verfolgt, sodass Geschenke weiterhin zum Warenkorb hinzugefügt werden können, solange das Angebot läuft.

Wenn Sie einschränken möchten, wie viele Geschenke ausgegeben werden können, können Sie den Lagerbestand **direkt am geklonten Produkt verfolgen und eingeben**:

1. Gehen Sie zu Shopify-Adminbereich > Produkte.
2. Öffnen Sie die Seite des geklonten Geschenks.
3. Aktivieren Sie „Lagerbestand verfolgt“.
4. Geben Sie die Lagerbestandsmenge ein.

{% hint style="success" %}
Um schnell alle von BOGOS erstellten geklonten Geschenkprodukte zu finden, filtern Sie Ihre Produktliste nach dem Tag „**bogos-gift**“.
{% endhint %}

<img src="../.gitbook/assets/unknown (287).png" alt="" height="264" width="624">

### 5.2 Lagerbestand vom Originalprodukt abziehen

<img src="../.gitbook/assets/unknown (288).png" alt="" height="179" width="624">

Diese Einstellung steuert, ob BOGOS den Lagerbestand vom Originalprodukt abzieht, wenn ein geklontes Geschenk gekauft wird.

* **Wenn deaktiviert:** BOGOS zieht den Lagerbestand nur vom geklonten Produkt ab.
* **Wenn aktiviert**: BOGOS zieht den Lagerbestand sowohl **vom geklonten Produkt als auch vom Originalprodukt** ab, sodass der Lagerbestand des Originalprodukts mit der Geschenknutzung synchron bleibt. Das Angebot wird dann basierend auf den Lagerbestandseinstellungen des Originalprodukts im Shopify-Adminbereich gestoppt oder fortgesetzt.

### **5.3 Nicht vorrätige Geschenkartikel anzeigen**

Diese Einstellung steuert, wie nicht vorrätige Geschenke im BOGOS-Geschenk-Slider angezeigt werden.

Wählen Sie eine der 2 Optionen:

* **Nicht vorrätige Artikel ausblenden**: Nicht vorrätige Geschenke werden aus dem Geschenk-Slider ausgeblendet.
* **Nicht vorrätige Artikel mit Status „Nicht vorrätig“ anzeigen**: Nicht vorrätige Geschenke bleiben im Geschenk-Slider sichtbar und werden mit dem Status „Nicht vorrätig“ markiert.

<img src="../.gitbook/assets/unknown (289).png" alt="" width="563">

## 6. Erweitert/Draft-Order-API

{% embed url="https://youtu.be/82iWUvMSP0E?si=B5WHuTsLlhyneNj1" %}

<figure><img src="../.gitbook/assets/image (235).png" alt=""><figcaption></figcaption></figure>

Die Draft-Order-API wird verwendet, damit Kunden zum Originalpreis mit Rabatt statt mit den Geschenkprodukten zur Kasse gehen können. Erfahren Sie mehr über die Draft-Order-API [hier](https://help.shopify.com/en/manual/orders/create-orders).

Mit der Draft-Order-API können Sie steuern, wie Rabatte auf Entwurfsbestellungen angewendet werden, mit der Option, Rabatte zu aktivieren oder zu deaktivieren.

* Erlauben: Diese Option ermöglicht die Kombination automatischer Rabatte oder Rabattcodes mit der von der BOGOS-App erstellten Entwurfsbestellung.
* Nicht erlauben: Diese Option blockiert Rabatte, wenn bereits ein Geschenk in der Entwurfsbestellung enthalten ist, und behält so das bisherige Verhalten bei.&#x20;

## 7. Schutz vor Betrug&#x20;

<figure><img src="../.gitbook/assets/image (202).png" alt=""><figcaption></figcaption></figure>

### 7.1. Per E-Mail benachrichtigen&#x20;

Sie können E-Mail-Benachrichtigungen über betrügerische Bestellungen erhalten. Die E-Mail enthält eine Zusammenfassung der als betrügerisch eingestuften Bestellung.

### 7.2. Betrugsschutz mit Bestellungen aktivieren&#x20;

Um diese Funktion zu aktivieren, müssen Sie uns zunächst die Berechtigung zum Bearbeiten von Bestellungen erteilen. Durch Klicken auf „Weiter“ werden Sie zur Zugriffsseite von Shopify weitergeleitet.

<figure><img src="../.gitbook/assets/image (203).png" alt=""><figcaption></figcaption></figure>

Es gibt zwei Schutzstufen. Sie können diejenige aktivieren, die zur Situation Ihres Shops passt.

#### Grundschutz&#x20;

Wenn Sie diese Schutzstufe aktivieren, storniert die App automatisch Bestellungen, die _nur Geschenke_ und _keine anderen Bedingungsprodukte_ enthalten.

#### Erweiterter Schutz&#x20;

Wenn Sie diese Schutzstufe aktivieren, überprüft die App alle Bestellungen erneut basierend auf ihrem Angebotsstatus und den Hauptbedingungen des Angebots.

Wenn BOGOS feststellt, dass Bestellungen Geschenke aus _abgelaufenen_ oder _geplanten_ Angeboten enthalten oder die _Anzahl der Geschenke_ verdächtig erscheint, kann die App automatisch eine der folgenden Aktionen ausführen:

* Erfüllung zurückhalten&#x20;
* Bestellung stornieren&#x20;

### 7.3. Betrugsschutz mit Warenkorb und Checkout aktivieren

BOGOS hat die Shopify-Checkout-Validierung direkt in die App-Einstellungen integriert. Wenn Sie diese Funktion aktivieren, müssen die Warenkörbe der Kunden diese Bedingungen erfüllen, um erfolgreich in Ihrem Shop zur Kasse zu gehen.

* Mindestwert im Warenkorb: Kunden können nicht mit Geschenken zur Kasse gehen, wenn ihr Warenkorbwert unter diesem Mindestwert liegt
* Mindestmenge im Warenkorb: Kunden können nicht mit Geschenken zur Kasse gehen, wenn ihre Warenkorbmenge unter diesem Mindestwert liegt
* Maximale Anzahl an Geschenken pro Bestellung: Kunden können nicht mit Geschenken zur Kasse gehen, wenn ihre Gesamtanzahl an Geschenken dieses Maximum überschreitet

{% hint style="warning" %}
Da diese Einstellung fortgeschrittener ist, empfehlen wir Ihnen, **direkt mit dem Support-Team zu chatten**. Unsere Mitarbeiter beraten Sie zu passenden Checkout-Regeln, um Ihren Shop besser zu schützen.
{% endhint %}

<figure><img src="../.gitbook/assets/image (204).png" alt=""><figcaption></figcaption></figure>
