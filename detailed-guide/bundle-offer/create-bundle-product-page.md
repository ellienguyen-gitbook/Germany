# Bundle-Produktseite erstellen

Mit der Bundle-Produktseite von BOGOS können Sie **eine dedizierte Produktseite für Ihr Bundle erstellen,** auf der Kunden Produkte mischen und kombinieren, Varianten auswählen und Mengen direkt auf der Seite anpassen können.&#x20;

[Sehen Sie es in Aktion](https://demo-store-by-bogos.myshopify.com/products/bundle-product-page?utm_source=HelpDoc\&utm_medium=Bundleproductpage\&utm_campaign=create).

{% hint style="warning" %}
Kunden müssen **genau die von Ihnen festgelegte Menge bündeln, um den passenden Rabatt zu erhalten**. Wenn Sie Pakete mit 2 und 4 Artikeln festlegen, erhält ein Bundle mit 3 Artikeln KEINEN Rabatt und wird nicht zum Warenkorb Ihres Stores hinzugefügt.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (419).png" alt=""><figcaption></figcaption></figure>

{% embed url="https://youtu.be/81HJcRiLcEs?si=uxxGZgDqx0CjtAt0" %}

**Das Einrichten einer Bundle-Produktseite umfasst 8 Schritte:**

1. Öffnen Sie die BOGOS-App > Angebot erstellen > Bundle > Bundle-Produktseite
2. [Bundle-Informationen ausfüllen](create-bundle-product-page.md#fill-in-bundle-information)
3. [Das Paket einrichten](create-bundle-product-page.md#set-up-the-pack)
4. [Den Abschnitt einrichten](create-bundle-product-page.md#set-up-the-section)
5. [Das Bundle anzeigen](create-bundle-product-page.md#display-the-bundle)
6. [Ihr Setup in der Vorschau ansehen](create-bundle-product-page.md#preview-your-setup) & Änderungen vornehmen
7. Veröffentlichen
8. [Produktdetails bearbeiten](create-bundle-product-page.md#edit-product-details)

## Bundle-Informationen ausfüllen

Füllen Sie die folgenden Felder aus:

![](<../../.gitbook/assets/unknown (294).png>)

* **Bundle-Name**: Wird nur verwendet, um Ihnen zu helfen, dieses Angebot einfach zu verwalten und von anderen Angeboten in der BOGOS-App zu unterscheiden.&#x20;
* **Produktname**: Der Name, der auf der Bundle-Produktseite angezeigt wird und den Kunden sehen.
* **Startzeit / Endzeit:** Wählen Sie, wann das Angebot beginnt und endet.

## Die Bundle-Größen einrichten

Ein Paket legt die Anzahl der Produkte fest, die Kunden hinzufügen müssen, um einen Rabatt zu erhalten.&#x20;

**Fügen Sie mehrere Paketgrößen hinzu**, um gestaffelte mengenbasierte Rabatte anzubieten.

### a) Eine Paketgröße hinzufügen

Klicken Sie auf **Paketgröße hinzufügen**, um ein neues Paket hinzuzufügen.&#x20;

{% hint style="warning" %}
Kunden müssen **genau die Menge bündeln, um den Rabatt des Pakets zu erhalten**. Wenn Sie Pakete mit 2 und 4 Artikeln festlegen, erhält ein Bundle mit 3 Artikeln KEINEN Rabatt und wird zum Warenkorb Ihres Stores hinzugefügt.
{% endhint %}

Füllen Sie dann die folgenden Felder aus:

![](<../../.gitbook/assets/unknown (295).png>)

* **Menge**: Die Anzahl der Artikel, die ein Kunde hinzufügen muss, um sich für den Rabatt zu qualifizieren.
* **Rabattart**: Wählen Sie eine von Prozentsatz, Fester Betrag, Festpreis.
* **Rabattwert**: Geben Sie den Rabattbetrag ein, wenn Kunden sich für dieses Paket qualifizieren.&#x20;

{% hint style="info" %}
Für Fester Betrag und Festpreis können Sie auf Währung hinzufügen klicken, um benutzerdefinierte Rabattbeträge für jeden Shopify-Markt festzulegen.
{% endhint %}

* **Größenbeschriftung**: Der Text, der anzeigt, wie viele Artikel Kunden kaufen müssen.
* **Rabattbeschriftung**: Der Text, der den Rabatt neben dem Paket anzeigt.
* **Bild hinzufügen** (optional): Laden Sie ein Bild hoch, um diese Paketgröße darzustellen.
* **Abzeichen hinzufügen** (optional): Fügen Sie ein Text- oder Bildabzeichen hinzu, um diese Paketgröße hervorzuheben.

![](<../../.gitbook/assets/unknown (296).png>)

### b) Ein unbegrenztes Paket hinzufügen

Klicken Sie auf **Unbegrenztes Paket hinzufügen**, wenn der Rabatt weiterhin gelten soll, nachdem Kunden die zuletzt definierte Paketgröße überschreiten.

Beispiel:&#x20;

* Paket 1 = Bundle aus 2 Artikeln
* Paket 2 = Bundle aus 4 Artikeln
* Unbegrenztes Paket = Bundle aus mehr als 4 Artikeln, wie z. B. 5 oder 6.

![](<../../.gitbook/assets/unknown (297).png>)

### c) Das Paket anpassen

Klicken Sie auf **Anpassen**, um den Vollbildeditor zu öffnen und Ihre Paketanzeige im Storefront anzupassen.

{% hint style="info" %}
Diese Anpassung gilt nur für diese Bundle-Produktseite. Andere Bundle-Produktseiten werden nicht beeinflusst.&#x20;
{% endhint %}

![](<../../.gitbook/assets/unknown (298).png>)

Weitere Details finden Sie unter \[[Das Paket anpassen](../customize/customize-bundle-product-page.md#customize-the-pack-pack-select-field)].

## Den Abschnitt einrichten

Ein Abschnitt legt die Produkte fest, aus denen Kunden ihr Bundle zusammenstellen können.

Sie können alle Produkte in einem Schritt anzeigen oder sie in mehrere Schritte aufteilen, um Kunden durch die Auswahl zu führen, zum Beispiel bei der Zusammenstellung einer Routine.

### a) Einen Schritt hinzufügen

Klicken Sie auf **+ Schritt hinzufügen**, um einen neuen Schritt hinzuzufügen. Folgen Sie dann diesen Anleitungen, um einen Schritt zu erstellen:

<img src="../../.gitbook/assets/unknown (299).png" alt="" height="380" width="483">

1. Füllen Sie die **Schrittüberschrift** aus: Der Name, der für diesen Auswahlschritt auf der Bundle-Produktseite angezeigt wird.
2. Wählen Sie den **Anzeigetyp**:

* **Nach Produkt**: Zeigt jedes Produkt mit mehreren Varianten als ein Element an. Kunden wählen Varianten aus einer Dropdown-Liste aus.
* **Nach Variante**: Wenn ein Produkt mehrere Varianten hat, wird jede Variante als separates Element zur Auswahl angezeigt.

3. Klicken Sie auf **Produkte auswählen**, um festzulegen, welche Produkte in diesem Schritt verfügbar sind.
4. Öffnen Sie **Erweiterte Einstellungen**, um eine Mindest- oder Höchstmenge festzulegen, die ein Kunde in diesem Schritt auswählen kann.

### b) Den Abschnitt anpassen

Klicken Sie auf **Anpassen**, um den Vollbildeditor zu öffnen und das Erscheinungsbild der Produktliste im Storefront anzupassen.

{% hint style="info" %}
Diese Anpassung gilt für jedes Bundle-Produktseiten-Angebot. Andere Bundle-Produktseiten werden nicht beeinflusst.&#x20;
{% endhint %}

![](<../../.gitbook/assets/unknown (300).png>)

Weitere Details finden Sie unter \[[Den Abschnitt anpassen](../customize/customize-bundle-product-page.md#customize-the-section)].

## Das Bundle anzeigen

Das Panel **Das Bundle anzeigen** auf der rechten Seite der Setup-Seite bietet zwei Optionen, um zu steuern, wie das Bundle in Ihrem Store angezeigt wird.

![](<../../.gitbook/assets/unknown (301).png>)

### a) Die Seite anpassen (Global Customize)

Diese Anpassung wird auf alle Bundle-Produktseiten in Ihrem Store angewendet.

Klicken Sie auf **Global customize**, um den Anpassungseditor zu öffnen. Passen Sie dann alle verfügbaren Optionen an:

<img src="../../.gitbook/assets/unknown (302).png" alt="" height="308" width="624">

Weitere Details finden Sie unter \[[Global Customize](../customize/customize-bundle-product-page.md#global-customize)].

### b) Widget auf der Produktseite des Kindprodukts

Aktivieren Sie **Widget auf der Seite des Kindprodukts hinzufügen**, um ein Widget auf den einzelnen Produktseiten aller in diesem Bundle enthaltenen Artikel anzuzeigen. Dieses Widget ermöglicht es Kunden, direkt zur Bundle-Produktseite zu navigieren.

Um die Anzeige des Widgets anzupassen, klicken Sie auf **Widget customize**.

<img src="../../.gitbook/assets/unknown (303).png" alt="" height="309" width="624">

Weitere Details finden Sie unter \[[Widget auf der Produktseite des Kindprodukts anpassen](../customize/customize-bundle-product-page.md#widget-on-child-product-page)].

## Ihr Setup in der Vorschau ansehen

Sobald alle erforderlichen Informationen ausgefüllt sind, klicken Sie auf Seite in der Vorschau ansehen, um den Vollbildeditor zu öffnen. Hier können Sie die Bundle-Produktseite in der **Vorschau ansehen** und die Anzeige bei Bedarf erneut **anpassen**, bevor Sie speichern.

![](<../../.gitbook/assets/unknown (304).png>)

## Produktdetails bearbeiten

Nach der Veröffentlichung der Bundle-Produktseite:

1. Kehren Sie zum Setup-Bildschirm zurück
2. Klicken Sie auf **Details bearbeiten**, um den Produkteditor zu öffnen.

![](<../../.gitbook/assets/unknown (305).png>)

3. **Aktualisieren Sie die Produktdetails**, die in Ihrem Store angezeigt werden, wie zum Beispiel den Produkttitel, die Beschreibung und das Bild.

{% hint style="info" %}
Richten Sie keinen Lagerbestand ein und fügen Sie keine Varianten hinzu. Diese Einstellungen würden das Erscheinungsbild der Bundle-Produktseite verändern und Kunden verwirren.
{% endhint %}

![](<../../.gitbook/assets/unknown (306).png>)

## Brauchen Sie Hilfe?

Wenn Sie Unterstützung benötigen, wenden Sie sich gerne über den Live-Chat innerhalb der BOGOS-App an unser Kundensupport-Team.
