# :wave: Hi, I'm Braxton! - [taxborn.com]
I'm a 24-year-old Software Engineer working at [Thomson Reuters] on their Westlaw and CoCounsel products. Currently, all my projects
are hosted on a self-hosted Forgejo Git forge at [git.mischief.town](https://git.mischief.town), and I mirror these 
repositories to [GitHub].

[taxborn.com]: https://www.taxborn.com
[Thomson Reuters]: https://tr.com
[GitHub]: https://github.com/taxborn

## Currently working on:
- :robot: Deep Research on the [Westlaw] project
- :herb: [taxborn.com], my personal at-proto powered digital garden

[Westlaw]: https://legal.thomsonreuters.com/en/products/westlaw-advantage
[taxborn.com]: https://git.mischief.town/taxborn/taxborn.com

```haskell
quicksort :: Ord a => [a] -> [a]
quicksort []     = []
quicksort (x:xs) = quicksort smaller ++ [x] ++ quicksort larger
  where
    smaller = [a | a <- xs, a <= x]
    larger  = [a | a <- xs, a > x]
```

*One of my favorite algorithms, expressed in Haskell. It reminds that simple, elegant
code can wield so much power.*
