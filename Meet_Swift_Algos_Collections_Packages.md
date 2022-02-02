# Meet the Swift Algorithms and Collections packages

[Link](https://developer.apple.com/videos/play/wwdc2021/10256/)

Swift stdlib team are very keen on Lazy Adapters, to calculate elements on demand.

Using the Ordered variants of Array, Dictionary or Set may not make sense for all cases.

## 3 types

1. Deque
   1. Deque = Double-ended Queue (deck)
2. OrderedSet
   1. .unordered to get Set view
3. OrderedDictionary
   1. Access by key, NOT index.