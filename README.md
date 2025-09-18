# FC Ukraine München

This is an official FC Ukraine München website.

## Build instructions for productions

```shell
rm -rf docs/ && hugo
```

## Build instructions for development

```shell
hugo server --disableFastRender
```

## Content Management System (CMS)

### Admin console

Use the following URL to modify content online:
https://fc-ukraine-muenchen.netlify.app/admin/

### Local development

Modify `static/admin/config.yml`:
```
local_backend: true
```

And run locally: `npx decap-server`.
