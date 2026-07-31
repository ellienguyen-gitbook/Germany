# Mit Shopify POS arbeiten

BOGOS ermöglicht es Ihnen, **Gift-with-Purchase-Angebote direkt am Shopify Point of Sale (POS)** durchzuführen, sodass Sie Kunden in Ihren physischen Geschäften genauso einfach belohnen können wie online.

{% hint style="info" %}
**Bevor Sie beginnen, lesen Sie bitte zunächst diese Hinweise:**

1. **Alle an den Angeboten beteiligten Produkte** müssen für den POS-Kanal veröffentlicht sein.
2. Sowohl die Mechanismen **Gift Clone als auch Gift Function** unterstützen Shopify POS.
3. **Bei Angeboten, die für Sammlungen gelten** (nur ausgewählte Sammlungen, alle außer ausgewählte Sammlungen), müssen Sie sowohl diese Sammlungen als auch alle ihre Produkte für Ihren Online-Shop veröffentlichen.
4. POS unterstützt derzeit **KEINE** Geschenkangebote mit:

* Unterbedingungen (außer für Vertriebskanäle).
* Geschenkprodukten als Geschenkkarten (aufgrund der Shopify-Regeln).
{% endhint %}

{% embed url="https://youtu.be/P4uPN8PXNCA" %}

## BOGOS auf Shopify POS einrichten

Bitte stellen Sie sicher, dass **BOGOS in Ihrem Adminbereich installiert** ist und **Shopify POS auf Ihrem Gerät installiert** ist (iOS oder Android).&#x20;

**Sobald das erledigt ist:**

1. Öffnen Sie auf Ihrem Gerät die Shopify-POS-App.
2. Tippen Sie im POS-Startbildschirm auf Kachel hinzufügen
3. Tippen Sie auf die Option App
4. Wählen Sie auf dem Bildschirm BOGOS.io: Free gift
5. Fügen Sie die BOGOS-POS-UI-Erweiterung hinzu
6. Klicken Sie auf Speichern.

<figure><img src="../.gitbook/assets/unknown (166).png" alt=""><figcaption></figcaption></figure>

## Geschenk(e) zu einer Bestellung am POS hinzufügen

**So gehen Sie vor:**

1. Veröffentlichen Sie ein oder mehrere Geschenkangebote in der BOGOS-App.
2. Veröffentlichen Sie alle am Angebot beteiligten Produkte für den POS-Kanal.
3. Öffnen Sie Shopify POS. Sie können dann Geschenke basierend auf Ihrer Angebotseinrichtung zum Warenkorb hinzufügen:

* [Geschenk(e) automatisch zum Warenkorb hinzufügen](work-with-shopify-pos.md#automatically-add-gift-s-to-cart-on-pos)
* [Geschenk(e) aus einer Liste auswählen](work-with-shopify-pos.md#choose-a-gift-s-from-a-list-on-pos)

{% hint style="warning" %}
Beim Gift-Clone-Mechanismus werden Geschenk-Klonprodukte in der Regel erst nach der Erstellung eines Angebots angelegt. Prüfen Sie daher unbedingt, ob die **Geschenk-Klonprodukte für den POS-Kanal veröffentlicht** sind.
{% endhint %}

### Geschenk(e) automatisch zum Warenkorb am POS hinzufügen

Wenn der POS-Warenkorb Ihre Angebotsbedingungen erfüllt, wird der Bestellung automatisch ein oder mehrere Geschenke hinzugefügt.

**So verwenden Sie diese Option:**

1. Überprüfen Sie, ob die Einstellung „Geschenk automatisch zum Warenkorb hinzufügen“ unter Einstellungen → Geschenkbedingung aktiviert ist.

<figure><img src="../.gitbook/assets/unknown (167).png" alt=""><figcaption></figcaption></figure>

2. Wählen Sie bei der Erstellung des Angebots „Alle Geschenke automatisch hinzufügen“.

<figure><img src="../.gitbook/assets/unknown (168).png" alt="" width="495"><figcaption></figcaption></figure>

_Weitere Details finden Sie im Leitfaden_ [_Geschenkangebot erstellen_](../detailed-guide/gift-offer/create-gift-offer.md#id-4.-select-gifts)_._

### Ein Geschenk/Geschenke aus einer Liste am POS auswählen

Wenn der POS-Warenkorb Ihre Angebotsbedingungen erfüllt, erhalten Kunden eine Echtzeit-Benachrichtigung und können das/die gewünschte(n) Geschenk(e) aus einer Geschenkliste auswählen.&#x20;

**So fügen Sie Geschenke zu ihrer Bestellung hinzu:**

1. Fügen Sie Produkte zu Ihrem Warenkorb hinzu. Stellen Sie sicher, dass der Warenkorb die Bedingung Ihres Angebots erreicht
2. Navigieren Sie zum POS-Startbildschirm > Tippen Sie auf Bogos Pos
3. Klicken Sie in der Liste der verfügbaren Geschenkprodukte auf Geschenk einlösen
4. Das Geschenk ist nun hinzugefügt. Schließen Sie die Bestellung ab und gehen Sie zur Kasse

<figure><img src="../.gitbook/assets/unknown (169).png" alt=""><figcaption></figcaption></figure>

**So verwenden Sie diese Option bei der Erstellung des Angebots:**

1. Wählen Sie „Anzahl der Geschenke, die der Kunde erhält“.
2. Geben Sie die Anzahl der Geschenke ein, für die Kunden berechtigt sein sollen.

<figure><img src="../.gitbook/assets/unknown (170).png" alt="" width="496"><figcaption></figcaption></figure>

_Weitere Details finden Sie im Leitfaden_ [_Geschenkangebot erstellen_](../detailed-guide/gift-offer/create-gift-offer.md#id-4.-select-gifts)_._

### Geschenkangebot nur auf dem POS-Kanal/bestimmten POS-Standorten ausführen

Diese Funktion erstellt Geschenkangebote, die ausschließlich auf POS oder bestimmten Standorten verfügbar sind, das heißt, sie sind nur beim Kauf über Ihre bestimmten physischen Geschäfte verfügbar.

So richten Sie es ein:

1. Öffnen Sie die BOGOS-App > erstellen Sie ein neues Geschenkangebot oder wählen Sie ein bestehendes aus.
2. Fügen Sie eine Unterbedingung des Angebots hinzu > Fügen Sie die Bedingung Vertriebskanal hinzu
3. Aktivieren Sie Kanalpunkt
4. Wählen Sie Ihren gewünschten POS-Standort aus (optional)
5. Klicken Sie auf Ihr Angebot veröffentlichen.

<figure><img src="../.gitbook/assets/unknown (68).png" alt=""><figcaption></figcaption></figure>

### Geschenkbestand am POS verwalten

**Bei Gift-Function-Mechanismen** werden die Geschenkmengen automatisch mit Ihrer Bestandseinrichtung in Shopify synchronisiert. Wenn der Bestand 0 erreicht, läuft das Angebot nicht auf POS.

**Beim Gift-Clone-Mechanismus** folgt die Geschenkmenge Ihrer Einrichtung in den Einstellungen:

* _Menge der Klonprodukte automatisch mit den Originalen synchronisieren_: Die Geschenkmenge in POS bleibt mit dem Original-Produktbestand synchron.
* _Bestand des Geschenkprodukts manuell eingeben:_ Sie steuern die Geschenkmenge manuell, unabhängig vom Originalprodukt.

<figure><img src="../.gitbook/assets/unknown (171).png" alt=""><figcaption></figcaption></figure>

_Weitere Details zur Verwaltung des Geschenkbestands finden Sie im Leitfaden_ [_Einstellungen_](../detailed-guide/settings.md#id-5.-gift-inventory-management)_._
