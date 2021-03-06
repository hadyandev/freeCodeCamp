---
title: Ackermann function
id: 594810f028c0303b75339acf
challengeType: 5
videoUrl: ''
localeTitle: Функция Аккермана
---

## Description
<section id="description"><p> Функция Аккермана является классическим примером рекурсивной функции, особенно потому, что она не является примитивной рекурсивной функцией. Он растет очень быстро в стоимости, равно как и размер его дерева вызовов. </p><p> Функция Аккермана обычно определяется следующим образом: </p> $$ A (m, n) = \ begin {cases} n + 1 &amp; \ mbox {if} m = 0 \\ A (m-1, 1) &amp; \ mbox {if} m&gt; 0 \ mbox {и} n = 0 \\ A (m-1, A (m, n-1)) &amp; \ mbox {if} m&gt; 0 \ mbox {и} n&gt; 0. \ end {cases} $$ <p> Его аргументы никогда не отрицательны и всегда заканчиваются. Напишите функцию, которая возвращает значение $ A (m, n) $. Произвольная точность предпочтительнее (поскольку функция растет так быстро), но не требуется. </p></section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>ack</code> - функция.
    testString: 'assert(typeof ack === "function", "<code>ack</code> is a function.");'
  - text: '<code>ack(0, 0)</code> должен возвращать 1.'
    testString: 'assert(ack(0, 0) === 1, "<code>ack(0, 0)</code> should return 1.");'
  - text: '<code>ack(1, 1)</code> должен вернуть 3.'
    testString: 'assert(ack(1, 1) === 3, "<code>ack(1, 1)</code> should return 3.");'
  - text: '<code>ack(2, 5)</code> должен вернуть 13.'
    testString: 'assert(ack(2, 5) === 13, "<code>ack(2, 5)</code> should return 13.");'
  - text: '<code>ack(3, 3)</code> должен вернуть 61.'
    testString: 'assert(ack(3, 3) === 61, "<code>ack(3, 3)</code> should return 61.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function ack (m, n) {
  // Good luck!
}

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
