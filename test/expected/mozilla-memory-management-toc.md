## In This Article

1. [Introduction](#introduction)
2. [Memory life cycle](#memory-life-cycle)
  1. [Allocation in JavaScript](#allocation-in-javascript)
    1. [Value initialization](#value-initialization)
    2. [Allocation via function calls](#allocation-via-function-calls)
  2. [Using values](#using-values)
  3. [Release when the memory is not needed anymore](#release-when-the-memory-is-not-needed-anymore)
3. [Garbage collection](#garbage-collection)
  1. [References](#references)
  2. [Reference-counting garbage collection](#reference-counting-garbage-collection)
    1. [Example](#example)
    2. [Limitation: cycles](#limitation-cycles)
    3. [Real-life example](#real-life-example)
  3. [Mark-and-sweep algorithm](#mark-and-sweep-algorithm)
    1. [Cycles are not a problem anymore](#cycles-are-not-a-problem-anymore)
    2. [Limitation: objects need to be made explicitly unreachable](#limitation-objects-need-to-be-made-explicitly-unreachable)
4. [See also](#see-also)
