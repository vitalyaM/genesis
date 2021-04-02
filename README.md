# Genesis Dnepr

[Главная страница](https://vitalyam.github.io/genesis/dist)<br>

**The technology used:** SCSS, PUG.

## INSTALLATION

You shall see the following files and directories:

      assets/               files and libraries
      images/               pictures
      js/                   js code
      pug/                  pug code
      scss/                 scss style
      htaccess              Apache web server config file

---

## REVIEW

### JS

        modules/               stores your js modules
        app.js                 index file

### PUG

        components/             pug components
        layouts/                layouts
        mixins/                 mixins
        index.pug               index page file

### SCSS

**[Sourse](https://matthiasott.com/notes/how-i-structure-my-css)**

```
    components/              style components
    design-tokens/           global theme style
    elements/                build items(form, links)
    generic/                 global rules
    setting/                 global settings
    skeleton/                main styles to building
    tools/                   global mixins and function
    utilities/               helper classes
    _shame.scss              temporary
    style.scss               index style file
```

---

## COMMANDS

```
    npm start  // start your project
    npm build  // create a minimized build
    npm deploy // deploy mod
```

## QUICK START

On command line, type in the following commands:

```
    cd ./yourRepository
    $ npm i
    $ npm start
    ---
    Local: http://localhost:3000
    Tunnel: https://tame-bulldog-69.loca.lt (Example)
```
