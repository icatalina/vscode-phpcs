# vscode-phpcs

[![Current Version](https://vsmarketplacebadge.apphb.com/version/icatalina.phpcs.svg)](https://marketplace.visualstudio.com/items?itemName=icatalina.phpcs)
[![Install Count](https://vsmarketplacebadge.apphb.com/installs/icatalina.phpcs.svg)](https://marketplace.visualstudio.com/items?itemName=icatalina.phpcs)
[![Open Issues](https://vsmarketplacebadge.apphb.com/rating/icatalina.phpcs.svg)](https://marketplace.visualstudio.com/items?itemName=icatalina.phpcs)

Integrates [phpcs](https://github.com/squizlabs/PHP_CodeSniffer.git) into [Visual Studio Code](https://code.visualstudio.com/).

## Looking for additional maintainers

Due to current work obligations, I am unable to commit enough time to steadily maintain this project, so I am looking for co-maintainers that are familiar with node.js, typescript and vscode plugin authoring.

If you want to help maintain this project, please contact me.

## Setup Development Version

-   install the [Visual Studio Code](https://code.visualstudio.com/) [npm extension](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script)
-   clone this repository and checkout `develop` branch
-   open the cloned repository folder using [Visual Studio Code](https://code.visualstudio.com/)
-   run VS Code task `npm install`

## Run/Debug Development Version

To run the development version of the `phpcs` extension:

-   open the cloned repository folder using [Visual Studio Code](https://code.visualstudio.com/)
-   select sidebar option `Debug`
-   select option `Client + Server` from the Debug drop-down menu
-   press `Start Debugging` button or hit F5

This will launch a new VS Code window named `Extension Development Host`, automatically using the development version of the `phpcs` extension.

> If you don't have an open php file on your `Extension Development Host` the server debug session will timeout and you will need to relaunch it from the debug panel.
