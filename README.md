Site du PEReN
=============

## Installation

```bash
cp -r themes/design-system-gouvfr/node_modules/@gouvfr/dsfr/dist/ ./static/design-system-gouvfr
```

Get Hugo at https://github.com/gohugoio/hugo/releases and run `hugo` to
generate the site.


## Developing

```
rm -rf public; ./hugo -b https://jupyter.peren.fr/user/$USER/proxy/1313/public/ && python3 -m http.server 1313
```

Go to `https://jupyter.peren.fr/user/$USER/proxy/1313/public/` to see the website.


## Building

To build for `peren.gouv.fr` website, use:

```
rm -rf public; ./hugo -b https://peren.gouv.fr
```
