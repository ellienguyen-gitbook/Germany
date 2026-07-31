---
description: This guide explains how to adjust the BOGOS blocks on your Shopify store.
icon: grip-vertical
---

# BOGOS-Blöcke anpassen

<figure><img src="../.gitbook/assets/unknown (144).png" alt=""><figcaption></figcaption></figure>

Normalerweise werden bestimmte BOGOS-Blöcke **automatisch in Ihrem Shopify-Onlineshop angezeigt.**

Sie **müssen BOGOS-Blöcke jedoch manuell anpassen**, wenn Sie:

* die Widgets nicht auf Ihren bevorzugten Seiten sehen
* [Checkout-Upsell](../detailed-guide/upsell-offer/create-checkout-upsell.md) oder [Danke-Seite-Upsell](../detailed-guide/upsell-offer/create-thank-you-page-upsell.md) verwenden
* die Position der Widgets ändern möchten
* neue Blöcke auf Produktseiten oder anderen Seiten Ihres Shops hinzufügen möchten

{% embed url="https://www.youtube.com/watch?v=w4KFLP1cUgY" %}

**Das Anpassen von BOGOS-Blöcken umfasst 6 wesentliche Schritte:**

1. Navigieren Sie zu Ihrem Theme-Editor > [Wählen Sie die Seite aus, auf der Sie einen Block hinzufügen möchten.](adjust-bogos-blocks.md#choose-the-page-to-adjust-blocks)
2. Klicken Sie auf [Abschnitt hinzufügen oder Block hinzufügen > Apps](adjust-bogos-blocks.md#add-a-new-bogos-block).
3. Suchen und wählen Sie den gewünschten BOGOS-Block aus.
4. [Geben Sie die Angebots-/Booster-ID ein](https://bogos-guideline.gitbook.io/user-guide/user-guide/customize/customize-bogos-blocks#enter-id-if-required) (falls erforderlich).
5. [Ziehen Sie den Block per Drag-and-Drop](adjust-bogos-blocks.md#move-an-existing-bogos-block) an Ihre bevorzugte Position.
6. Klicken Sie auf Speichern.

**Für eine detailliertere Anleitung** lesen Sie bitte den folgenden Leitfaden:

### Wählen Sie die Seite aus, auf der Blöcke angepasst werden sollen

Bevor Sie einen BOGOS-Block hinzufügen oder verschieben, entscheiden Sie, auf welcher Seite er angezeigt werden soll.

1. Gehen Sie zu Shopify-Admin > Onlineshop > Themes > Theme bearbeiten.
2. Wählen Sie in der Mitte der Kopfzeile die Seite aus, die Sie bearbeiten möchten.&#x20;

<figure><img src="../.gitbook/assets/unknown (145).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Jeder Seitentyp unterstützt unterschiedliche BOGOS-Blöcke:**

* Produktseite (alle BOGOS-Blöcke)
* Startseite, Sammlungsseite, Warenkorbseite (nur bestimmte Blöcke)
* Checkout-Seite (Checkout-Upsell-Block – nur für Shopify Plus)
* Danke-Seite (Danke-Upsell-Block)
* Benutzerdefinierte Seite (nur bestimmte Blöcke)
{% endhint %}

Nachdem Sie zur gewünschten Seite navigiert sind, können Sie mit dem Hinzufügen oder Verschieben von BOGOS-Blöcken beginnen.

### Einen neuen BOGOS-Block hinzufügen

Sie können einen BOGOS-Block entweder **innerhalb eines bestehenden Abschnitts** oder **als Teil eines neuen Abschnitts** hinzufügen, je nach Ihrem Theme-Layout und Ihrer Anzeigepräferenz.

1. Wählen Sie aus, wie Sie den Block hinzufügen möchten:

* Klicken Sie auf den bestehenden Abschnitt, oder
* Klicken Sie auf Abschnitt hinzufügen, wenn Sie einen neuen erstellen möchten

2. Block hinzufügen > Apps > Wählen Sie den gewünschten Block aus.

<figure><img src="../.gitbook/assets/image (385).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Nur Blöcke, die auf dieser Seite funktionieren, werden in der Liste angezeigt. Wenn ein Block nicht in der Liste erscheint, wird er auf dieser Seite nicht unterstützt.
{% endhint %}

2. [Geben Sie die ID ein](adjust-bogos-blocks.md#enter-id) (falls erforderlich).
3. Ziehen Sie den Block oder Abschnitt per Drag-and-Drop an Ihre bevorzugte Position.
4. Klicken Sie auf Speichern.

### Einen bestehenden BOGOS-Block verschieben

Um die Position eines Blocks innerhalb eines bestehenden Abschnitts zu ändern:

1. Suchen Sie den Abschnitt, der den BOGOS-Block enthält, den Sie verschieben möchten.
2. Ziehen Sie den Block per Drag-and-Drop an die gewünschte Position innerhalb des Abschnitts.
3. Klicken Sie auf Speichern.

**Hinweis:**&#x20;

* Blöcke können nur innerhalb ihres aktuellen Abschnitts verschoben werden.&#x20;
* Wenn Sie **einen Block in einen anderen Abschnitt verschieben** möchten, müssen Sie:

1. Den bestehenden BOGOS-Block auswählen und löschen.
2. Den neuen Abschnitt suchen > Block hinzufügen > Apps.
3. Den zu verschiebenden Block suchen und erneut auswählen.
4. Den Block per Drag-and-Drop an Ihre bevorzugte Position ziehen.
5. Auf Speichern klicken.

### ID eingeben (falls erforderlich)

Eine Angebots-ID oder Booster-ID ist eine eindeutige Kennung für jedes Angebot und jeden Booster in BOGOS. Sie ermöglicht es, den richtigen Block mit der von Ihnen eingegebenen ID anzuzeigen.

<figure><img src="../.gitbook/assets/unknown (146).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Bei bestimmten Funktionen, wie dem Geschenkschieberegler, dem Checkout-Upsell und der Geschenk-Miniaturansicht, ist die Eingabe einer ID nicht möglich. Stattdessen erscheinen diese Blöcke automatisch, wenn Kunden die angegebenen Bedingungen erfüllen.
{% endhint %}

<details>

<summary><strong>🔻 Auf der Produktseite ist die ID optional</strong></summary>

**In den meisten Fällen müssen Sie** auf der Produktseite **keine ID eingeben.** BOGOS gleicht automatisch ab und zeigt das Widget mit relevantem Inhalt für dieses Produkt an.&#x20;

Z. B.: Ein Classic-Bundle-Widget erscheint automatisch auf Produktseiten für alle im Bundle enthaltenen Produkte.

**Sie müssen nur dann eine ID eingeben**, wenn:

* Sie mehrere [Fortschrittsbalken](../detailed-guide/boosters/create-progress-bar.md) oder [Heute-Angebot-Blöcke](../detailed-guide/boosters/create-today-offer-block.md) haben und den richtigen auf jeder Produktseite anzeigen möchten. (Wenn Sie keine ID angeben, werden standardmäßig alle Fortschrittsbalken oder Heute-Angebot-Blöcke angezeigt.)
* Sie einen anderen Block anzeigen möchten als den, den BOGOS automatisch auswählt.

</details>

<details>

<summary><strong>🔻 Auf anderen Seiten ist die ID zwingend erforderlich</strong></summary>

Wenn Sie BOGOS-Blöcke zur Startseite, zu Sammlungsseiten, zur Warenkorbseite oder zu Ihren benutzerdefinierten Seiten hinzufügen, **müssen Sie** eine bestimmte ID eingeben, um festzulegen, welcher Block angezeigt werden soll.

</details>

#### 🔻 Wie man eine ID findet und eingibt

1. Öffnen Sie die BOGOS-App > Navigieren Sie zum Einrichtungsbildschirm des Angebots oder Boosters, das/den Sie anzeigen möchten.
2. Kopieren Sie Ihre ID am Ende des URL-Links (z. B. 15556)

<figure><img src="../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

1. Wählen Sie im Theme-Editor den benötigten BOGOS-Block aus.
2. Suchen Sie das ID-Feld in den Blockeinstellungen.
3. Geben Sie die richtige ID ein (z. B. 15556).
4. Klicken Sie auf Speichern.

### Häufig gestellte Fragen (FAQs)

<details>

<summary><strong>Warum erscheint mein Angebot nicht in meinem Shop, obwohl es aktiviert ist?</strong></summary>

**A1:** Wenn Ihr Angebot aktiviert ist, aber nicht in Ihrem Shop angezeigt wird, überprüfen Sie Folgendes:

* Prüfen Sie, ob die Bedingungen erfüllt sind oder nicht, da einige Widgets nur bei erfüllten Bedingungen angezeigt werden (z. B. richtige Produkte, Sammlungen oder Warenkorbbedingungen).
* Stellen Sie sicher, dass der Angebotsblock zu Ihrem Theme hinzugefügt wurde. Navigieren Sie zu Ihrem Theme-Editor und überprüfen Sie, ob der BOGOS-Block auf der Seite erscheint. Wenn er nicht erscheint, [fügen Sie den Angebotsblock](adjust-bogos-blocks.md#add-a-new-bogos-block) zu Ihrer Seite hinzu.
* Wenn Sie eine Angebots-ID verwenden, bestätigen Sie, dass Sie die richtige ID in den Blockeinstellungen eingegeben haben.

</details>

<details>

<summary><strong>Wie kann ich ein Widget so einschränken, dass es nur auf bestimmten Seiten erscheint?</strong></summary>

**A2:** Um einen BOGOS-Block nur auf bestimmten Seiten anzuzeigen, nicht auf allen Ihren Seiten, müssen Sie [eine benutzerdefinierte Seitenvorlage erstellen](https://help.shopify.com/en/manual/online-store/themes/theme-structure/templates):

1. Gehen Sie zu Shopify-Admin > Onlineshop > Themes > Theme bearbeiten.
2. Klicken Sie auf das Dropdown-Menü der Startseite > Wählen Sie Seiten > Vorlage erstellen.
3. Passen Sie die Seite nach Wunsch an.
4. [Fügen Sie den Block hinzu](adjust-bogos-blocks.md#add-a-new-bogos-block), der angezeigt werden soll.

</details>

<details>

<summary><strong>In welchen Fällen wird die Angebots-ID benötigt?</strong></summary>

Sie müssen nur in diesen Fällen eine Angebots-ID (oder Booster-ID) eingeben:

* Auf Produktseiten:
  * Normalerweise müssen Sie keine ID eingeben – BOGOS zeigt automatisch das richtige Widget an (z. B. das Bundle für dieses Produkt).
  * Geben Sie eine ID nur ein, wenn:
    * Sie mehrere Fortschrittsbalken oder Heute-Angebot-Blöcke haben und einen bestimmten pro Produktseite anzeigen möchten, oder
    * Sie einen anderen Block anzeigen möchten als den, den BOGOS automatisch auswählt.
* Auf anderen Seiten (Startseite, Sammlung, Warenkorb, benutzerdefinierte Seiten):

Die ID ist erforderlich. Wenn Sie einen BOGOS-Block im Theme-Editor hinzufügen, müssen Sie die richtige ID eingeben, damit Shopify weiß, welches Angebot/welchen Block es anzeigen soll.\
\
Bei Blöcken wie dem Geschenkschieberegler, Checkout-Upsell und der Geschenk-Miniaturansicht müssen Sie keine ID eingeben, sie werden automatisch angezeigt, wenn die Bedingungen erfüllt sind.

</details>

<details>

<summary><strong>Wo finde ich meine Angebots-ID?</strong></summary>

Bitte befolgen Sie die folgenden Schritte:

Schritt 1. Öffnen Sie die BOGOS-App in Ihrem Shopify-Admin.

Schritt 2. Gehen Sie zu dem gewünschten Angebot/Booster (z. B. Classic Bundle, Fortschrittsbalken, Heute-Angebot-Block) und klicken Sie, um es zu bearbeiten.

Schritt 3. Sehen Sie sich die URL Ihres Browsers an – der numerische Wert ganz am Ende ist die ID (zum Beispiel: .../mix-match/22643 → ID = 22643).

<div align="left"><img src="../.gitbook/assets/unknown (285).png" alt="" height="132" width="532"></div>

Schritt 4. Kopieren Sie diese Zahl und fügen Sie sie in das Feld Angebots-ID / Booster-ID in Ihren Theme-Blockeinstellungen ein (Onlineshop → Anpassen → BOGOS-Block auswählen → ID einfügen → Speichern).

</details>
