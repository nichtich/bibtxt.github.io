---
title: Welcome
---


## What's BibTeX?

```
@BOOK{Fau86,
  AUTHOR="J.W. Goethe",
  TITLE="Faust. Der Trag\"{o}die Erster Teil",
  PUBLISHER="Reclam",
  YEAR=1986,
  ADDRESS="Stuttgart"
}
```


## What's Bib.TXT?

```
[Fau86]
  author:    J.W. Goethe
  title:     Faust. Der Tragödie Erster Teil
  publisher: Reclam
  year:      1986
  address:   Stuttgart
```


What's the difference?

- Uses Unicode
- No quotes required
- No commas required
- More shortcuts (upcoming)
- Multi-line text records compatible e.g. reading records wit a "plain-vanilla" ValuesReader will result in an array of hashes: 

```ruby
{ key:       "Fau86",
  author:    "J.W. Goethe",
  title:     "Faust. Der Tragödie Erster Teil",
  publisher: "Reclam",
  year:      1986,
  address:   "Stuttgart" }
```
