# Settings

## 1. General settings

<figure><img src="../.gitbook/assets/image (197).png" alt=""><figcaption></figcaption></figure>

* **BOGOS status**: Enable BOGOS status for app to work on your online store.&#x20;
* **Timezone**: Time will be displayed based on your device's timezone&#x20;
* **App language**: Change app language to match with your native language&#x20;

## 2. Gift logic mechanism

{% embed url="https://youtu.be/gXwkfsbsWgI?si=1BbGRUUuEAqNRGNJ" %}

<figure><img src="../.gitbook/assets/image (253).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Changing the logic will affect all offers and remove any existing cloned products from your store. You may need to re-enable offers once the app completes the logic switch.

**BOGOS recommends contacting support** before changing the logic to ensure a smooth transition.
{% endhint %}

BOGOS offers two gift logic mechanisms:

### **2.1. Clone Product (Default)**

{% hint style="success" %}
Compatible with POS, Mobile app, Headless, Third-party checkout, Fulfillment app.
{% endhint %}

When a gift offer is created, BOGOS automatically creates a duplicate (a "clone") of the original gift product in the merchant's Shopify product catalog.

These cloned products/gifts:

* are hidden from the storefront/store search
* are tagged "bogos-gift"
* adds that cloned copy to the cart instead of the original products.

{% hint style="info" %}
Because it's a separate product entry, it gives BOGOS much more flexibility: hide gifts from search (to make a mystery gift), unique image/title for those cloned gifts, no limit on number of gift offers created,...)
{% endhint %}

{% hint style="warning" %}
To manage the cloned gifts' inventory (like syncing with the original products' stock), please read [5. Gift Inventory Management](settings.md#id-5.-gift-inventory-management).
{% endhint %}

### **2.2. Gift Function**

{% hint style="warning" %}
Not compatible with Mobile app, Headless, or Third-party checkout.
{% endhint %}

Gifts are added to the cart as your original Shopify products, discounted via Shopify's native discount function.

For example: it can't exceed the 100 discount limits across store.

## 3. Gift condition

<figure><img src="../.gitbook/assets/image (198).png" alt=""><figcaption></figcaption></figure>

### 3.1. Automatically add gift to cart&#x20;

When there is only one gift selected in the offer, this gift will be automatically added to customers' carts. If you disable this feature, gift products will always show up in a gift slider.

### 3.2. Gift discount calculated by <a href="#gift-discount-calculated-by" id="gift-discount-calculated-by"></a>

The gift discount percentage can be calculated based on the Current price or the Compare-at price.

### 3.3. Gift price must be less than/equal to products

This feature restricts customers to only getting gifts at a lower price than the items in their cart. The gift item's price can be calculated based on the Current price or the Compare-at price.

### 3.4. Limit one selection per gift&#x20;

This feature restricts customers from picking a gift item a **Second time** from the gift slider. They can no longer select this gift item even if they meet the conditions of other offers with the same gift.

### 3.5. Exclude added product&#x20;

This feature restricts customers from getting a gift if they already have the same item in the cart.

## 4. Gift product&#x20;

{% embed url="https://youtu.be/2-Bg_Ep7W5s?si=iQ9xVWQ6AiVyUGFQ" %}

Setting inherit information of gift product from the original product&#x20;

<figure><img src="../.gitbook/assets/image (199).png" alt=""><figcaption></figcaption></figure>

### 4.1. Delete gift products after turning off the offers&#x20;

This feature is always enabled by default, so all cloned products can be removed after deactivating the offers.&#x20;

### 4.2. Include compare-at price in gift product

If you enable this feature, the gift product will show. Once this setting is enabled, the gift product will show up with a crossed price on the customer's cart.

### 4.3. Gift products' SKU/Barcode format

By default, the gift products cloned by our app will have the same as the original SKU/Barcode.

You can also customize your SKU/Barcode format between the following options:&#x20;

* Same as original product&#x20;
* Same as original product with a suffix. E.g., SKU (100%OFF)
* Blank&#x20;

This will help if you use an inventory management system or 3rd party fulfillment for your store.

### 4.4. Gift product title format&#x20;

Please choose your preferred format, it would be among the 3 below. Please reactivate the offers once you've changed this setting.

<figure><img src="../.gitbook/assets/image (200).png" alt=""><figcaption></figcaption></figure>

### 4.5. Sale channels&#x20;

By default, the gift products will be published only on Online Store. If you have other sales channels such as POS or Mobile app, you can automatically publish them using this feature.

{% hint style="warning" %}
Please carefully revise your campaign and contact our support team if you plan to execute the offers on many different channels.
{% endhint %}

### 4.6. Include other original product details

By default, we will not duplicate the information on the original products in the gift products. However, this setting allows you to automatically include them.

* Product type
* Tags

## 5. Gift inventory management&#x20;

{% hint style="warning" %}
Only available for the [Gift Clone mechanism](settings.md#id-2.-gift-logic-mechanism).
{% endhint %}

<img src="../.gitbook/assets/unknown (286).png" alt="" height="263" width="624">

### **5.1. Track and adjust the cloned gift's inventory**

By default, the cloned gift's inventory is not tracked, so gifts can keep being added to carts as long as the offer is running.

If you want to limit how many gifts can be given out, you can t**rack and input inventory directly on the cloned product**:

1. Go to Shopify admin > Products.
2. Open the cloned gift's page.
3. Enable Inventory tracked.
4. Input the inventory quantity.

{% hint style="success" %}
To quickly find all cloned gift products created by BOGOS, filter your product list by the tag “**bogos-gift**”.
{% endhint %}

<img src="../.gitbook/assets/unknown (287).png" alt="" height="264" width="624">

### 5.2 Deduct inventory from original product

<img src="../.gitbook/assets/unknown (288).png" alt="" height="179" width="624">

This setting controls whether BOGOS deducts inventory from the original product when a cloned gift is purchased or not.

* **If turned off:** BOGOS only deducts inventory from the cloned product.
* **If turned on**: BOGOS deducts inventory from **both the cloned product and the original product**, so the original product’s inventory stays in sync with gift usage. The offer will then stop or continue based on the original product’s inventory settings in the Shopify admin.

### **5.3 Display out-of-stock gift items**

This setting controls how out-of-stock gifts appear in the BOGOS gift slider.

Select one of the 2 options:

* **Hide out-of-stock items**: Out-of-stock gifts are hidden from the gift slider.
* **Show out-of-stock items with an Out-of-stock status**: Out-of-stock gifts remain visible on the gift slider, marked with an Out-of-stock status.

<img src="../.gitbook/assets/unknown (289).png" alt="" width="563">

## 6. Advanced/ Draft-Order API

{% embed url="https://youtu.be/82iWUvMSP0E?si=B5WHuTsLlhyneNj1" %}

<figure><img src="../.gitbook/assets/image (235).png" alt=""><figcaption></figcaption></figure>

Draft-Order API is used for customer to checkout with original price at a discount instead of the gift products. Read more about Draft-Order API [here](https://help.shopify.com/en/manual/orders/create-orders).

Draft-Order API allows you to control how discounts apply to draft orders with an option to enable or disable discounts.

* Allow: This option enables the combination of automatic discounts or discount codes with the draft order created by the BOGOS app.
* Do Not Allow: This option blocks discounts when a gift is already included in the draft order, maintaining the previous behavior.&#x20;

## 7. Fraud protection&#x20;

<figure><img src="../.gitbook/assets/image (202).png" alt=""><figcaption></figcaption></figure>

### 7.1. Notify via email&#x20;

You can receive email notifications about fraud orders. The email will contain a summary of the order considered fraudulent.

### 7.2. Activate Fraud protection with Orders&#x20;

To activate this feature, you must first grant us permission to edit orders. By clicking Continue, you will be redirected to Shopify's access-granting page.

<figure><img src="../.gitbook/assets/image (203).png" alt=""><figcaption></figcaption></figure>

There are two levels of protection, you can enable the one that works with your store's situation.

#### Basic protection&#x20;

When you enable this level of protection, the app will automatically cancel orders with _only gifts_ and _no other condition products_.

#### Advanced protection&#x20;

When you enable this level of protection, the app will re-check all the orders based on their offer status and offer main conditions.

If BOGOS detects orders include gifts taken from _expired_, _scheduled_ offers, or the _number of gifts_ appears suspicious then the app can automatically do one of the following actions:

* Hold fulfillment&#x20;
* Cancel order&#x20;

### 7.3. Activate Fraud protection with Cart and Checkout

BOGOS has integrated the Shopify Checkout Validation right into app settings. When you enable this feature, customers' carts must meet these conditions to successfully checkout in your store.

* Minimum cart value: Customers can't checkout with gifts if their cart value is below this min
* Minimum cart quantity: Customers can't checkout with gifts if their cart quantity is below this min
* Maximum number of gifts per order: Customers can't checkout with gifts if their total gift number exceeds this max

{% hint style="warning" %}
Since this setting is more advanced, we recommend you **chat directly with the Support team**. Our agents will consult you on suitable checkout rules to better protect your store.
{% endhint %}

<figure><img src="../.gitbook/assets/image (204).png" alt=""><figcaption></figcaption></figure>
