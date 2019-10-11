---
id: 5d9fee54795fd0258cd54da4
title: Part 03
challengeType: 1
isBeta: true
---

## Description
<section id='description'>

Our delicious vanilla buttercream cupcake needs more information for us to sell it.

Give our cupcake the additional properties of `id` and `price`. Match them with values 0 and 2.99, respectively.

Here is an example object with multiple entries:

```js
{
  name: "Phillip",
  age: 29,
  gender: male
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
    testString: |
      assert.deepStrictEqual(products[0], { id: 0, name: "Vanilla buttercream cupcake", price: 2.99 });

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
const products = [
  {
    name: "Vanilla buttercream cupcake"
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
  }
];
```

</section>
