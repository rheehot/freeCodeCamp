---
id: 5d9fee54795fd0258cd54dab
title: Part 10
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
    for(let i = 0; i < products.length; i++) {
      /*  
      This code functions but can we make this better? We could use built in method called `find` to make our code more concise and easier to read.

      The `find` method returns the first item when a given condition is satisfied. 

      Create a variable called `item`, and set it equal to the item returned by the `find` method.
      
      For example:

      ```
      const match = arr.find(item => item.name === name);
      myArr.push(match);
      ```

      */
      if(id === products[i].id) {
        this.items.push(products[i]);
      }
    }
  }
}


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
