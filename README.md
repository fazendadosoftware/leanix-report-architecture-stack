# Architecture Stack

Shows a matrix that is formed based on the properties and/or tags of factsheets. Depending on the configuration, X and Y axes as well as the coloring are adjustable.

Developed and maintained by [LeanIX GmbH](https://www.leanix.net/) and [incowia GmbH](https://www.incowia.com/).

## Table of Contents

- [License](#license)
- [Browser compatibility](#browser-compatibility)
- [Project setup](#project-setup)
- [Available scripts](#available-scripts)

## License

This report and most of the source code is free for everyone to use with the exception of all artifacts in `src/common`, which can be exclusively used for this report only. Please contact [info -at- incowia.com](mailto:info@incowia.com?subject=LeanIX%20Custom%20Reports:%20Common%20artifacts), if you want to use these code artifacts elsewhere.

Copyright (c) 2018 LeanIX GmbH & incowia GmbH

## Browser compatibility

- Chromium & derivatives: 50 or higher
- Firefox & derivatives: 50 or higher
- Microsoft Edge: 38 or higher
- Safari: 11 or higher
- Internet Explorer: not supported, but might work for version 11 (not tested)

## Project setup

This project was bootstrapped with [leanix-reporting-cli](https://github.com/leanix/leanix-reporting-cli).

1. `npm install -g @leanix/reporting-cli`
1. `npm install` in project directory
1. create a `lxr.json` file in project directory (please see [Getting started](https://github.com/leanix/leanix-reporting-cli#getting-started))

## Available scripts

In the project directory, one can run:

`npm start`

This command will start the local development server. Please make sure you have properly configured `lxr.json` first.
It will take the specified API Token from `lxr.json` and automatically do a login to the workspace.

`npm run build`

Builds the report and outputs the build result into `dist` folder.

`npm run upload`

Uploads the report to the workspace configured in `lxr.json`.
Please see [Uploading to LeanIX workspace](https://github.com/leanix/leanix-reporting-cli#uploading-to-leanix-workspace).
