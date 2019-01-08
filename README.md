<p align="center"><img width="100" src="https://raw.githubusercontent.com/NeutroniumCore/neutronium-vue/master/template/src/assets/logo.png"></p>
<h1 align="center">Neutronium.Simple.Template</h1>

[![Build status](https://img.shields.io/appveyor/ci/David-Desmaisons/neutronium-simple-template.svg?maxAge=2592000)](https://ci.appveyor.com/project/David-Desmaisons/neutronium-simple-template)
[![MIT License](https://img.shields.io/github/license/NeutroniumCore/Neutronium.Simple.Template.svg)](https://github.com/NeutroniumCore/Neutronium.Simple.Template/blob/master/LICENSE)

This project is a template application for Neutronium Vue project.<br>

## Features

### npm script

* `npm run serve`

    Serve files for Neutronium for debug in local browser using `.cjson` files as view-model.

* `npm run live`

    Serve files for Neutronium hot-reload.

* `npm run build`

    Build files to be used in Neutronium application.

### Command line argument

        Usage:
            --mode=live
            -m=dev --url=http://localhost:9090/index.html
            -u=http://localhost:9091/index.html

        Options:
            -m --mode=(live|dev|prod)    Set application mode.
            -u --url=<uri>   Set view url

![Screen shot](./__doc__/Configuration.png)
### Application mode

* Live:

        Debug mode with hot-reload activated using file served by `npm run live` scripts.

* Dev:

        Debug mode using local files.

* Prod:

        No debug, using local files.


### Injected context command

#### To Live

* Only available in `dev` mode.
* Switch to `live` mode by running `npm run live` and reloading the page using the served files.

![Screen shot](./__doc__/screen-3.png)
![Screen shot](./__doc__/screen-4.png)

#### Reload

* Only available in `live` mode.
* Reload the page. Maybe useful on some scenario when page does not automatically reload.

![Screen shot](./__doc__/screen-2.png)


