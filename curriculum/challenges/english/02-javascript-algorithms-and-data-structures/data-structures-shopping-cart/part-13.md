---
id: 5d9fee54795fd0258cd54dae
title: Part 13
challengeType: 1
isBeta: true
---

## Description
<section id='description'>

const products = [
  {
    id: 0,
    name: "Vanilla buttercream cupcake",
    price: 2.99
  },
  {
    id: 1,
    name: "French Macaroon",
    price: 3.99
  },
  {
    id: 2,
    name: "Fruit sprinkles cupcake",
    price: 3.99
  },
  {
    id: 3,
    name: "Pink flower cupcake",
    price: 5.99
  }
];

class ShoppingCart {
  constructor() {
    this.items = [];
  }

  addItem(id, products) {
    const item = products.find(item => item.id === id);
    this.items.push(item);
  }

  getItems() {
    return this.items;
  }
}

const shoppingCart = new ShoppingCart();

/*
Let's test our `addItem` and `getItems` methods!

Call the `addItem` method from `shoppingCart`.

Pass in the number 2 as our id and the global `products` array.

Then call the `getItems` method to see what's returned from the array.

For example:

```
ourInstance.method(10, clothesArray);
ourInstance.printItems();
```

*/


</section>

## Instructions
<section id='instructions'>
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: See description above for instructions.
    testString: assert(code.match());

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js

```

</div>
</section>


## Solution
<section id='solution'>

```js

```

</section>
