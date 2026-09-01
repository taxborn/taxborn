# :wave: hi, i'm braxton!
I'm a 24-year-old software engineer working at [Thomson Reuters] on their Westlaw and CoCounsel products. currently, all my projects
are hosted on a self-hosted Forgejo Git forge at [git.biscuits.at](https://git.biscuits.at), and I mirror these 
repositories to [GitHub].

[Thomson Reuters]: https://tr.com
[GitHub]: https://github.com/taxborn

## Currently working on:
- :robot: Deep Research on the [Westlaw] project
- :robot: Westlaw Brief Builder on the [CoCounsel] project
- :herb: my personal atproto-powered digital garden

[Westlaw]: https://legal.thomsonreuters.com/en/products/westlaw-advantage
[CoCounsel]: https://www.thomsonreuters.com/en/cocounsel

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
