# CLI app using Node.js & MySQL
Once you download the app,
```javascript
run npm install
```
## customer side

 The app will show users with two messages.

   * The first should ask them the ID of the product they would like to buy.
   * The second message should ask how many units of the product they would like to buy.

```javascript 
run node bamazon
```

Then you will see
![Image description](https://isabellaWang0108.github.io/cli-apps/bamazon/images/1.png)

Once the customer has placed the order, your application should check if your store has enough of the product to meet the customer's request.
![Image description](https://isabellaWang0108.github.io/cli-apps/bamazon/images/2.png)

If not, the app should log a phrase like `Insufficient quantity!`, and then prevent the order from going through.
![Image description](https://isabellaWang0108.github.io/cli-apps/bamazon/images/4.png)

Iif your store _does_ have enough of the product, you we will fulfill the customer's order.
![Image description](https://isabellaWang0108.github.io/cli-apps/bamazon/images/3.png)




## Manager side
```javascript 
run node bamazonManager
```

Then you will see
![Image description](https://isabellaWang0108.github.io/cli-apps/bamazon/images/5.png)

If a manager selects `View Products for Sale`, the app should list every available item: the item IDs, names, prices, and quantities.
![Image description](https://isabellaWang0108.github.io/cli-apps/bamazon/images/6.png)

 If a manager selects `View Low Inventory`, then it should list all items with an inventory count lower than five.
![Image description](https://isabellaWang0108.github.io/cli-apps/bamazon/images/7.png)

If a manager selects `Add to Inventory`, your app should display a prompt that will let the manager "add more" of any item currently in the store.
![Image description](https://isabellaWang0108.github.io/cli-apps/bamazon/images/8.png)
![Image description](https://isabellaWang0108.github.io/cli-apps/bamazon/images/9.png)
  * If a manager selects `Add New Product`, it should allow the manager to add a completely new product to the store.
![Image description](https://isabellaWang0108.github.io/cli-apps/bamazon/images/10.png)
![Image description](https://isabellaWang0108.github.io/cli-apps/bamazon/images/11.png)
- - -

