# :wave: Hi, I'm Braxton! - [taxborn.com]
I'm a 24-year-old Software Engineer working at [Thomson Reuters] on their Westlaw product.

[taxborn.com]: https://www.taxborn.com
[Thomson Reuters]: https://tr.com

## Currently working on:
- :robot: Gen AI on the [Westlaw] project
- :herb: [taxborn.com], my personal garden
- :keyboard: [HSS], experiments in generating hashes as fast as possible

[Westlaw]: https://legal.thomsonreuters.com/en/products/westlaw-advantage
[taxborn.com]: https://git.mischief.town/taxborn/taxborn.com
[HSS]: https://git.mischief.town/taxborn/hashing

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
