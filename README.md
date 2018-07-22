# [GitHub Desktop](https://desktop.github.com)

[![Travis](https://img.shields.io/travis/desktop/desktop.svg?style=flat-square&label=Travis+CI)](https://travis-ci.org/desktop/desktop)
[![CircleCI](https://img.shields.io/circleci/project/github/desktop/desktop.svg?style=flat-square&label=CircleCI)](https://circleci.com/gh/desktop/desktop)
[![AppVeyor Build Status](https://img.shields.io/appveyor/ci/github-windows/desktop/master.svg?style=flat-square&label=AppVeyor&logo=appveyor)](https://ci.appveyor.com/project/github-windows/desktop/branch/master)
[![VSTS Build Status](https://github.visualstudio.com/_apis/public/build/definitions/845028c2-21f3-4eb1-80b9-215d3e9b1d08/3/badge)](https://github.visualstudio.com/Desktop/_build/index?definitionId=3)
[![license](https://img.shields.io/github/license/desktop/desktop.svg?style=flat-square)](https://github.com/desktop/desktop/blob/master/LICENSE)
![90+% TypeScript](https://img.shields.io/github/languages/top/desktop/desktop.svg?style=flat-square&colorB=green)

GitHub Desktop is an open source [Electron](https://electron.atom.io)-based
GitHub app. It is written in [TypeScript](http://www.typescriptlang.org) and
uses [React](https://facebook.github.io/react/).

![GitHub Desktop Linux](https://github.com/diegoenriquesantos/GithubDesktop-Linux/blob/master/Captura%20de%20pantalla%20de%202018-07-21%2023-04-29.png)

## Thanks !

Thanks to the original author [shiftkey](https://github.com/shiftkey) from [desktop](https://github.com/shiftkey/desktop)

## How  can I start the project?

We add some dependencies and put a command short list to fast start the project in Linux environment:

sudo git clone https://github.com/diegoenriquesantos/GithubDesktop-Linux.git
sudo chmod -R 777 GithubDesktop-Linux/
cd GithubDesktop-Linux
yarn install
yarn build:dev
yarn start

## Where can I get it?

Download the official installer for your operating system:

 - [macOS](https://central.github.com/deployments/desktop/desktop/latest/darwin)
 - [Windows](https://central.github.com/deployments/desktop/desktop/latest/win32)
 - [Windows machine-wide install](https://central.github.com/deployments/desktop/desktop/latest/win32?format=msi)

There are several community-supported package managers that can be used to install Github Desktop.
 - Windows users can install using [Chocolatey](https://chocolatey.org/) package manager:
      `c:\> choco install github-desktop`
 - macOS users can install using [Homebrew](https://brew.sh/) package manager:
      `$ brew cask install github`
 - Arch Linux users can install the latest version from the [AUR](https://aur.archlinux.org/packages/github-desktop/).

You can install this alongside your existing GitHub Desktop for Mac or GitHub
Desktop for Windows application.

**NOTE**: there is no current migration path to import your existing
repositories into the new application - you can drag-and-drop your repositories
from disk onto the application to get started.

### Beta Channel

Want to test out new features and get fixes before everyone else? Install the
beta channel to get access to early builds of Desktop:

 - [macOS](https://central.github.com/deployments/desktop/desktop/latest/darwin?env=beta)
 - [Windows](https://central.github.com/deployments/desktop/desktop/latest/win32?env=beta)

## More Resources

See [desktop.github.com](https://desktop.github.com) for more product-oriented
information about GitHub Desktop.

## License

**[MIT](LICENSE)**

The MIT license grant is not for GitHub's trademarks, which include the logo
designs. GitHub reserves all trademark and copyright rights in and to all
GitHub trademarks. GitHub's logos include, for instance, the stylized
Invertocat designs that include "logo" in the file title in the following
folder: [logos](app/static/logos).

GitHub® and its stylized versions and the Invertocat mark are GitHub's
Trademarks or registered Trademarks. When using GitHub's logos, be sure to
follow the GitHub [logo guidelines](https://github.com/logos).
