# Checkout Shipping Step Completed

### 

## Javascript Code
```js
window.appEventData23 = window.appEventData23 || [];
appEventData23.push({
  "event": "Checkout Shipping Step Completed",
    "product": [
        {
            "price": {
                "priceType": "<priceType>"
            },
            "productInfo": {
                "brand": "<brand>",
                "name": "<name>",
                "sku": "<sku>"
            }
        }
    ]
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|brand|string|Describes the brand of a product or offering.|Ford, Chevrolet, Dodge, Levis, Columbia, Patagonia|||||||
|priceType|string|Describes the type of price offered using commonly used terms. |1st mark, 2nd mark, 3rd mark, clearance, sale, doorbuster|||||||
|sku|string|Stock Keeping Unit (SKU) Unique Identifier of specific item (typically) held in inventory.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level below productID for products with SKU variants. |34567890, 4567890, 00155-large-cornflower|||||||
