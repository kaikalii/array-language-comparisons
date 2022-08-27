## The Essence of Array Programming

### 1. "Higher Order Functions"

||Name||Reduce||Scan||Outer Product|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|APL|Operators <br> Adverbs|:green_circle:|`/ (reduce)` <br> `⌿ (reduce first)`|:green_circle:|`\ (scan)` <br> `⍀ (scan first)`|:green_circle:|`∘. (outer product)`|
|J|Adverbs & <br> Conjunctions|:green_circle:|`/ (insert)`|:green_circle:|`\ (prefix)`|:green_circle:|`/ (table)`|
|BQN|Modifiers|:green_circle:|`´ (fold)`<br>`˝ (insert)`|:green_circle:|`` ` (scan)``|:green_circle:|`⌜ (table)`|
|Q|Iterators|:green_circle:|`/`<br>`over`|:green_circle:|`\`<br>`scan`|:green_circle:|`/:\:`|
|Julia|Functions|:green_circle:|`reduce`|:green_circle:|`accumulate`|:yellow_circle:|`broadcast`
|NumPy|Functions|:green_circle:|`_.reduce()`|:green_circle:|`_.accumulate()`|:green_circle:|`_.outer()`|
|R|Functions|:green_circle:|`Reduce`|:green_circle:|`Reduce(accumulate=TRUE)`|:green_circle:|`outer`|
|Nial|Transformers|:green_circle:|`REDUCE`|:green_circle:|`ACCUMULATE`|:green_circle:|`OUTER`|
|Futhark|Functions<br>SOAC|:green_circle:|`foldl/r`<br>`reduce(_comm)`|:green_circle:|`scan`|:yellow_circle:|`outer_product`|
|SaC||:red_circle:|-|:red_circle:|-|:red_circle:|-|

### 2. Language Features

||Booleans = 0 & 1|Strings are Character Arrays|
|:-:|:-:|:-:|
|APL|:green_circle:|:green_circle:|
|J|:green_circle:|:green_circle:|
|BQN|:green_circle:|:green_circle:|
|Q|:green_circle:|:green_circle:|
|Julia|:yellow_circle:|:red_circle:|
|NumPy|:yellow_circle:|:red_circle:|
|R|:yellow_circle:|:red_circle:|
|Nial|:green_circle:|:green_circle:|
|Futhark|:red_circle:|:green_circle:|
|SaC|:red_circle:|:red_circle:|