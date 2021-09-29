[![Foo](https://static.wixstatic.com/media/ca276f_2ad7374dcb514aa78c9d35bd3e0c364f~mv2.png/v1/fill/w_295,h_87,al_c,q_85,usm_0.66_1.00_0.01/logo%20OO%2001%20horz%20blue%20small.webp)](https://www.ootopia.org/)

# OOTOPIA STRAPI CMS

[![GitHub license](https://img.shields.io/github/license/OOTOPIA/ootopia-strapi)](https://github.com/OOTOPIA/ootopia-strapi/blob/main/LICENSE)
[![.github/workflows/github-ci.yml](https://github.com/OOTOPIA/ootopia-strapi/actions/workflows/github-ci.yml/badge.svg?branch=develop)](https://github.com/OOTOPIA/ootopia-strapi/actions/workflows/github-ci.yml)
[![GitHub stars](https://img.shields.io/github/stars/OOTOPIA/ootopia-strapi)](https://github.com/OOTOPIA/ootopia-strapi/stargazers)
![GitHub repo size](https://img.shields.io/github/repo-size/OOTOPIA/ootopia-strapi)
![GitHub last commit](https://img.shields.io/github/last-commit/OOTOPIA/ootopia-strapi)

### Project description

- This CMS is used by client to create Learning Tracks and the data created here will be consumed by Ootopia's API.


### Confluence
- [Get Stated](https://devmagic.atlassian.net/wiki/spaces/~102890266/pages/2248540213/Get+Started+-+Ootopia)


### Requirements
-  Node LTS (v12 or V14) Note that odd Node versions will never be supported (eg v13, v15).

- NPM v6 or higher

- Typical default build tools for your operating system (the build-essentials package on most Debian-based systems)

- At least 1 CPU core (highly recommended at least 2)

- At least 2 GB RAM (Moderately Recommended 4)

- Minimum required storage space recommended by your operating system or 32 GB of free space

- A supported database version

	- MySQL >= 5.6

	- MariaDB >= 10.1

	- PostgreSQL >= 10

	- SQLite >= 3

	- MongoDB >= 3.6

- A supported operating system

	- Ubuntu >= 18.04 (LTS-Only)

	- Debian >= 9.x

	- CentOS/RHEL >> 8

	- macOS Mojave or newer (ARM not supported)

	- Windows 10

- Have an editor to work with code like [VSCode](https://code.visualstudio.com/).
- Set the environment variables - [find here](https://devmagic.atlassian.net/wiki/spaces/~102890266/pages/2225176585)


### 🎲 Running the Back End

```bash
# Clone this repository 
$ git clone <https://github.com/OOTOPIA/ootopia-strapi.git>

# Access the project folder
$ cd ootopia-strapi

# Install dependencies
$ npm ci

# Run the application in development mode
$ npm run develop (or yarn develop)

# Deploy
$ NODE_ENV=production npm run build

# The server will start on port:1341 - access <http://localhost:1341>
```
