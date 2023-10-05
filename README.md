## README
![INTERNATIONALSPEAKERS LOGO](https://github.com/international-speakers/internationalspeakers.github.io/blob/main/static/images/logo.png)

Website of the International Speakers Toastmasters Club. Created with [Hugo](https://gohugo.io/) from the [Bigspring theme](https://github.com/themefisher/bigspring-light).

## Install
```bash
$ git clone https://github.com/international-speakers/internationalspeakers.github.io.git

$ hugo server -D
```
(opens http://localhost:1313/ on browser)

## Changing page content
```bash
$ cd content/'page_to_modify'

$ open _index.md
```
## Publish changes
```bash
$ hugo 

$ cd ..

$ mv -f site/public/* site/

$ cd site/

$ rm -r public/

$ git add .

$ git commit -am "change"

$ git push