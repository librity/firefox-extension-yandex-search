# Yandex search

## TODO

- [ ] Add configuration modal:
  - [ ] Switch between yandex.com and yandex.ru
  - [ ] Select search language
- [ ] Find a way around the captcha
  - [ ] Maybe by adding the query params: `&lr=10437&search_source=yacom_desktop_common`
    - https://stackoverflow.com/questions/15852238/how-to-construct-complex-google-web-search-query

## Build

Can be built in any OS.

- Install [Node.js](https://nodejs.org/) version 16.17.0
- Install `npm` version 8.15.0
- Clone the repo
- Install dependencies:
  - `npm install`
- Build:
  - `npm run build`

## Remarks

I find it ridiculous that Firefox doesn't let us add an arbitrary search engine with an url template.
Get with the times Mozilla.
