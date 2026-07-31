# Anpassung mithilfe von Events

{% hint style="info" %}
Hinweis:&#x20;

* Falls Sie die untenstehenden Events für die Anpassung verwenden, stellen Sie bitte sicher, dass Sie CSS verwenden, um die Standardkomponente von BOGOS auszublenden.&#x20;
* Alle Anpassungen sollten innerhalb der Datei snippet/freegifts-snippet.liquid implementiert werden
{% endhint %}

```typescript
type GiftVariant {
  id: number,
  title: string,
  price: number,
  original_price: number,
  thumbnail: string,
  discount_type: "percentage" | "fixed_amount",
  discount_value: number
}

type GiftProduct {
  id: number,
  title: string,
  handle: string,
  thumbnail: string,
  belongs_to_offer?: string | string[],
  variants: GiftVariant[]
}

type TodayOffer {
  id: string,
  title: string,
  gifts: GiftProduct[]
}

type CartMessage {
  value: string,
  offer_root: string, // offer id
}
```



### 1. Event zur Anpassung des Geschenk-Sliders

```javascript
document.addEventListener("fg-gifts:show-slider", (e) => {
  /* Event for customizing the gift slider */
  // Hidden default 
  // #freegifts-main-popup-container.sca-modal-fg {
  //   display: none !important;
  // }
  console.log("fg-gifts:show-slider", e.detail)
  // Data type of e.detail: {
  // addGiftToCartFunc: async (variantID, quantity, offerId) => void, // function handle add gift to cart by BOGOS
  // gifts: GiftProduct[] // array of gift products to show
  // }
})
```

{% hint style="info" %}
Hinweis: Stellen Sie sicher, dass Sie das untenstehende CSS verwenden, um die Standardkomponente von BOGOS für den Geschenk-Slider auszublenden
{% endhint %}

```css
#freegifts-main-popup-container.sca-modal-fg {
  display: none !important;
}
```

### 2. Event zur Anpassung des Geschenksymbols und der Geschenk-Miniaturansicht auf der Produktseite

```javascript
document.addEventListener("fg-gifts:gift-icon", (e) => {
  /* Event for customizing the Gift icon, and Gift thumbnail on product page */
  // Hidden default 
  // #sca-gift-icon, #sca-gift-thumbnail {
  //   display: none !important;
  // }
  console.log("fg-gifts:gift-icon", e.detail)
  // Data type of e.detail: {
  // icon: string, // url gift icon if products has gift
  // gifts: GiftProduct[] // gift can be added when buy that product
  // product: {
  //    handle: string,
  //    variant: number, // variant id selected
  // }
  // }
})
```

{% hint style="info" %}
Hinweis: Stellen Sie sicher, dass Sie das untenstehende CSS verwenden, um die Standardkomponente von BOGOS für das Geschenksymbol und die Geschenk-Miniaturansicht auszublenden
{% endhint %}

```css
#sca-gift-icon, #sca-gift-thumbnail {
  display: none !important;
}
```

### 3. Event zur Anpassung des Heutigen Angebots&#x20;

```javascript
document.addEventListener("fg-today-offer:render", (e) => {
  /* Event for customizing the rendering of Today offer */
  // Hidden default 
  // #sca-fg-today-offer-widget, #sca-fg-today-offer-iframe {
  //   display: none !important;
  // }
  console.log("fg-today-offer:render", e.detail)
  // Data type of e.detail: {
  // todayOffers: TodayOffer[] 
  // }
})
```

{% hint style="info" %}
Hinweis: Stellen Sie sicher, dass Sie das untenstehende CSS verwenden, um die Standardkomponente von BOGOS für das Heutige Angebot auszublenden
{% endhint %}

```css
#sca-fg-today-offer-widget, #sca-fg-today-offer-iframe {
   display: none !important;
}
```

***

```javascript
document.addEventListener("fg-today-offer:success", (e) => {
  /* Event for customizing the Today offer when the state of the offer is changed. E.g. success, not reach,.. */
  console.log("fg-today-offer:success", e.detail)
  // Data type of e.detail: {
  //   idOffersSuccess: number[], // offers id success
  // } 
})
```

### 4. Event zur Anpassung der Warenkorbnachricht

```javascript
document.addEventListener("fg-messages:render", (e) => {
  /* Event for customizing the Cart message */
  // Hidden default 
  // #sca-promotion-message-layout {
  //   display: none !important;
  // }
  console.log("fg-messages:render", e.detail)
  // Data type of e.detail: {
  // data: CartMessage[] 
  // }
})
```

{% hint style="info" %}
Hinweis: Stellen Sie sicher, dass Sie das untenstehende CSS verwenden, um die Standardkomponente von BOGOS für die Warenkorbnachricht auszublenden
{% endhint %}

```css
#sca-promotion-message-layout {
  display: none !important;
}
```
