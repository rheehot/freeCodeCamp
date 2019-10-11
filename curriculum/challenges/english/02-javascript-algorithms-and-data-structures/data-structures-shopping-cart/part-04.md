---
id: 5d9fee54795fd0258cd54da5
title: Part 04
challengeType: 1
isBeta: true
---

## Description
<section id='description'>

We filled up the rest of the products array to speed up the process. Now that our shelves are full, let's build our shopping cart with a JavaScript class.

A class is like a blueprint for an object, and describes the object and what it does. For example, the Car class might have the properties color, make, and model which can create two car objects: a red Hyundai Elantra and an orange Ford Fiesta.

Declare a class called `ShoppingCart` by using the `class` keyword. By convention, class names should start with a capital letter:

```js
class Car {

}
```

</section>

## Instructions
<section id='instructions'>
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: See description above for instructions.
    testString: assert(code.replace(/\s/g, '').includes('classShoppingCart{}') && ShoppingCart.length === 0);

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
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

```

</div>
</section>


## Solution
<section id='solution'>

```js
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

}
```

</section>
