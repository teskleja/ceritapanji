# Static Website

## Demo
[View demo]([https://hugo-ink.netlify.com](https://ceritapanji.netlify.app/))
![Screenshot]([https://user-images.githubusercontent.com/547147/69119000-3ace9280-0abb-11ea-81bc-5af68433e845.png](https://i.imgur.com/ohWjpth.png) "light theme")

## Features
* Google Analytics integration
* Syntax highlighting
* Twitter cards and opengraph tags support
* Disqus comments
* RSS feeds
* Custom CSS/JS
* Multilingual months support
* 
## Language Settings for the month

Due to the currently unavailable feature for multilingual dates in ``.Date`` from
Go. It is possible to create a ``month.yaml`` in the data folder of your
Hugo site root directory. There is also an example file in
``exampleSite/data/``.

```sh
cat > month.yaml << EOF
1: "Jan"
2: "Feb"
3: "Mar"
4: "Apr"
5: "May"
6: "Jun"
7: "Jul"
8: "Aug"
9: "Sep"
10: "Oct"
11: "Nov"
12: "Dec"
EOF
```

## Credits

* [Ezhil theme](https://github.com/vividvilla/ezhil) from which Ink was forked

Licensed under the MIT license.
