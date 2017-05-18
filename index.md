---
title: Welcome
---


## What's BibTeX?

```
@Book{Fau86,
  author    = {J.W. Goethe},
  title     = "Faust. Der Trag\"{o}die Erster Teil",
  publisher = "Reclam",
  year      = 1986,
  address   = "Stuttgart"
}
```


## What's Bib.TXT?

```yaml
Fau86:
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

Bib.TXT can be parsed into a key-value structure by any YAML parser (there's a library for virtually every programming languages). 

```javascript
{ 
  Fau86: {
    author:    "J.W. Goethe",
    title:     "Faust. Der Tragödie Erster Teil",
    publisher: "Reclam",
    year:      1986,
    address:   "Stuttgart"
  }
}
```

```ruby
{ 
  "Fau86" => {
    "author" =>     "J.W. Goethe",
    "title" =>      "Faust. Der Tragödie Erster Teil",
    "publisher" =>  "Reclam",
    "year" =>       1986,
    "address" =>    "Stuttgart"
  }
}
```

...

## Limitations

* Values cannot include line breaks
* The first character of a value must not be one of `"`, `'`, `|`, `>`, `[` and `{`.

## License

The Bib.TXT format and conventions are dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

## Questions? Comments?

Send them along to the [wwwmake mailing list/forum](http://groups.google.com/group/wwwmake). Thanks.


<!-- todo: move footer to layouts -->

Brought to you by [Manuscripts](https://github.com/manuscripts) and friends.
