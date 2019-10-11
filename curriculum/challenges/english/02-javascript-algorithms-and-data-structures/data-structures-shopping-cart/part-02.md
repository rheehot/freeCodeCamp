---
id: 5d804b6121b11cdaa3f6b163
title: Part 02
challengeType: 1
isBeta: true
---

## Description
<section id='description'>

Because each product in our online pastry shop contains a lot of information, we will store it as an object which is another simple data structure.

Inside the products array, add an object with the property `name` and the value "Vanilla buttercream cupcake".

For example, here is an array that contains a similar object:

```js
const users = [
  {
    name: "Phillip"
  }
];
```

</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: See description above for instructions.
    testString: |
      assert.deepStrictEqual(products[0], { name: "Vanilla buttercream cupcake" });

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
const products = [];

```

</div>



</section>

## Solution
<section id='solution'>

```js
const products = [
  {
    name: "Vanilla buttercream cupcake"
  }
];
```

</section>
