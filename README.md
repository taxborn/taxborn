# :wave: Hi, I'm Braxton! - [taxborn.com]
I'm a 22-year-old Software Engineer working at [Thomson Reuters] on their Westlaw product.

[taxborn.com]: https://www.taxborn.com
[Thomson Reuters]: https://tr.com

## Currently working on:
- :accessibility: Accessibility on the [Westlaw] project
- :herb: [taxborn.com], my personal garden
- :keyboard: [HSS], experiments in generating hashes as fast as possible
- :coconut: [Coquito], a hobby programming language

[Westlaw]: https://legal.thomsonreuters.com/en/products/westlaw-precision
[taxborn.com]: https://github.com/taxborn/taxborn.com
[HSS]: https://github.com/taxborn/hashing
[Coquito]: https://github.com/taxborn/coquito

```haskell
quicksort :: Ord a => [a] -> [a]
quicksort []     = []
quicksort (x:xs) = quicksort smaller ++ [x] ++ quicksort larger
  where
    smaller = [a | a <- xs, a <= x]
    larger  = [a | a <- xs, a > x]
```

*one of my favorite algorithms, expressed in Haskell. it reminds that simple, elegent
code can wield so much power.*
