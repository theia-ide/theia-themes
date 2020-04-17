<div align="center">

This repository is now **archived** since theming support in Theia-based applications are now contributed directly by VS Code theme extensions. Please see the relevant [issue](https://github.com/theia-ide/theia-themes/issues/3).


<br/>
<img src='./assets/images/theia-logo.svg' width="100">
<h3>THEIA THEME PACK</h3>
</div>

## Themes

### Dark Themes

<!-- Themes -->
<div align='center'>


`Dracula`

<img src='./assets/images/dracula-screenshot.png' width="500" alt="dracula">

`Nightfall`

<img src='./assets/images/nightfall-screenshot.png' width="500" alt="dracula">


</div>

### Light Themes

<!-- Themes -->
<div align='center'>

`Aqua`

<img src='./assets/images/aqua-screenshot.png' width="500" alt="aqua">


`Github`

<img src='./assets/images/github-screenshot.png' width="500" alt="github">


</div>


## Getting started

Install [nvm](https://github.com/creationix/nvm#install-script).

    curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.5/install.sh | bash

Install npm and node.

    nvm install 8
    nvm use 8

Install yarn.

    npm install -g yarn

## Running the browser example

    yarn rebuild:browser
    cd browser-app
    yarn start

Open http://localhost:3000 in the browser.

## Running the Electron example

    yarn rebuild:electron
    cd electron-app
    yarn start