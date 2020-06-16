---
title: Array Prototypes
length: 90
tags: javascript, arrays, prototypes, mutator, accessor
---

## Learning Goals

By the end of this lesson, you'll be able to:
- read documentation and explore array prototype methods
- determine if a given method is a mutator or accessor
- build a process for self-guided learning, and determine which parts are most helpful for _you_

## Vocabulary

- `Array Prototype` - methods that are built specifically for arrays. They help us change the arrays themselves or get certain information out of them.
- `Mutator` - methods that mutate, or change, the original array
- `Accessor` - methods that do not mutate the original array, rather just give us some information about the array

## Warm Up

In your notebook, jot down your answers to the following:

```javascript
var students = ["Estelle", "Katy", "Ian", "Hanna", "Miley", "Ben"];
```

For the array above,
- How would you programmatically find the number of elements?
- Oops! There's not a Miley in our class. NO CODE - what are the **instructions** you would want to tell the computer to take in order to remove the string "Miley" from the array?

### Debrief

Sometimes we need to access information about an array or certain elements in our array. Methods we use to do that are called **accessor** methods. They do not mutate or change the original array - they just give us information, or copies of parts of the array.

In other cases, we will want to change the data our array holds. **Mutator** methods actually mutate, or change, the data in the array. If we needed to remove a student element from the `students` array, we'd need to use a mutator method.

## Protocol

Throughout most of this lesson, you'll be working in small groups to explore both
- some array prototypes
- different ways to learn new technical concepts, and which you like best

### The methods to research

For the rest of this lesson, we will be learning about the following array prototype methods:

- push
- pop
- unshift
- shift
- slice
- splice
- includes
- concat

During the course of our research, we will practice different modes of learning! This is in order to help us gain a better understanding of how we individually learn, and furnish us with some strategies we can fall back on when we get stuck!

<section class="call-to-action">
For each array prototype method, follow this protocol carefully:

1. Read the documentation on MDN.
2. Talk through your understanding of it together.
3. Make a visual representation of the method with your candies and paper.
4. Think: What is **returned** from the method?
5. Think: Does the method mutate the original array?
6. Try It: In a `repl.it`, try out the method. While poking around here, try to verify your predictions from steps 3 and 4.
7. Back to documentation - verify your predictions from steps 3 and 4.
8. Document any remaining questions!
</section>

## Gallery Walk

In your new group of 3, make a poster for your assigned array prototype! It should include:
- Name of method
- What it does (in plain English)
- Does it mutate the original array?
- What does it return
- _Optional: Syntax examples, use-case examples._

After all poster are made, we will do a "Gallery Walk" - walk around the room and look at each others posters and make sure notes are accurate. If you aren't 100% of something you are about to write on your poster - totally ok to ask an instructor! We do want to make sure these provide accurate info for your classmates.

## Wrap Up

### What should you memorize?

Often times, especially when we are starting to code, we put pressure on ourselves to memorize every little thing. This is NOT necessary and not a good use of your brain space! There will be some methods you use so frequently that you just memorize them, but for the most part, the things you "memorize" should be bigger ideas and how things work together.

Some of the methods we learned today are the kind you'll use so often that you'll have down pat (including the syntax): push, pop, shift, unshift.

You should have enough of an understanding of arrays that you know you could google something like "remove a specific element from an array", but maybe you won't memorize exactly what method to use or the exact syntax for it.

### What is not worth memorizing?

It's not a good use of time to attempt to memorize every array prototype and its syntax.

<section class="checks-for-understanding">
## Reflection

1. What from this morning helped you learn? Talking with your partner? Spending time in the docs? Playing with a method in `repl.it`? Visualizing it without code (using candies)?
2. Discuss your best learning techniques with your table/partner.
3. Open your notebooks to the last page, and write "When I'm stuck, I will:" and then add the learning strategies that worked best for you!
</section>
