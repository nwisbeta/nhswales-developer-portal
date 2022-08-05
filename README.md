# NHS Wales Developer Portal Placeholder

This repository contains the content for a static website built with [Jekyll](https://jekyllrb.com/)


## How to add/edit a page

The setup has some limited support for multi-lingual content (Cymraeg/Welsh and English)

When adding a page, include `lang` and `lang-ref` in the page's [front matter](https://jekyllrb.com/docs/front-matter/).

 - The `lang` should be the [two-letter language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes), i.e. `en` or `cy`
 - the `lang-ref` should be some id to reference the page in all languages

For example, here's the front matter for a page in English:
```yml
title: Privacy Policy
lang: en
lang-ref: privacy
```

And here's the front matter for same page in Cymraeg (with the same `lang-ref`)
```yml
title: Polisi Preifatrwydd
lang: cy
lang-ref: privacy
```

## How to support extra languages

Update `_data/i8n.yml` to add support for additional lanauages