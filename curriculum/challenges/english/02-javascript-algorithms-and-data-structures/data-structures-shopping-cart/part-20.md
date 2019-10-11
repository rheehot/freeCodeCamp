---
id: 5d9fee54795fd0258cd54db5
title: Part 20
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
    this.discountPercentage = 30;
  }

  addItem(id, products) {
    const item = products.find(item => item.id === id);
    this.items.push(item);
  }

  getItems() {
    return this.items;
  }
  
  getCount() {
    return this.items.length;
  }
  
  removeItem(id) {
    const index = this.items.indexOf(id);
    this.items.splice(index, 1);
  }
  
  clearCart() {
    this.items = [];
  }
  
  applyDiscount(amount) {
    return this.discountPercentage / 100 * amount
  }
}

/*
Let's print to the console to see the output of the `applyDiscount` method:

```
const shoppingCart = new ShoppingCart();
console.log(shoppingCart.applyDiscount(2.99));
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
