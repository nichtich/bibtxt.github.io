---
title: Welcome
---


## What's BibTeX?

```
@Book{Fau86,
  author    = "J.W. Goethe",
  title     = "Faust. Der Trag\"{o}die Erster Teil",
  publisher = "Reclam",
  year      = 1986,
  address   = "Stuttgart"
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
- Multi-line text records compatible e.g. reading records with a "plain-vanilla" ValuesReader (that knows nothing about Bib.TXT conventions) will result in a "well-formed" array of hashes: 

```ruby
{ key:       "Fau86",
  author:    "J.W. Goethe",
  title:     "Faust. Der Tragödie Erster Teil",
  publisher: "Reclam",
  year:      1986,
  address:   "Stuttgart" }
```



## License

The Bib.TXT format and conventions are dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

## Questions? Comments?

Send them along to the [wwwmake mailing list/forum](http://groups.google.com/group/wwwmake). Thanks.
