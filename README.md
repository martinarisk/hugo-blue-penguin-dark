# HUGO Blue Penguin Dark

## _Keep it simple, but not simpler_

**XMin** is a Hugo theme written by [Yihui Xie](https://yihui.org) in about four hours: half an hour was spent on the Hugo templates, and 3.5 hours were spent on styling. The main motivation for writing this theme was to provide a really minimal example to beginners of Hugo templates. This XMin theme contains about 140 lines of code in total, including the code in HTML templates and CSS (also counting empty lines).


```bash
find . -not -path '*/exampleSite/*' \( -name '*.html' -o -name '*.css' \) | xargs wc -l
```

```
       5 ./layouts/404.html
      12 ./layouts/_default/single.html
      20 ./layouts/_default/list.html
      13 ./layouts/_default/terms.html
       0 ./layouts/partials/foot_custom.html
       0 ./layouts/partials/head_custom.html
       9 ./layouts/partials/footer.html
      20 ./layouts/partials/header.html
      51 ./static/css/style.css
       7 ./static/css/fonts.css
     137 total
```

I can certainly further reduce the code, for example, by eliminating the CSS, but I believe a tiny bit of CSS can greatly improve readability. You cannot really find many CSS frameworks that only contain 50 lines of code.

[![Screenshot](https://camo.githubusercontent.com/7758d9b9d6d27adddf82641177de980a80b43671cca8255de3af8b03bd144f45/68747470733a2f2f74796c65722d636172722e636f6d2f696d616765732f6674702f6f75742e706e67)](https://camo.githubusercontent.com/7758d9b9d6d27adddf82641177de980a80b43671cca8255de3af8b03bd144f45/68747470733a2f2f74796c65722d636172722e636f6d2f696d616765732f6674702f6f75742e706e67)
