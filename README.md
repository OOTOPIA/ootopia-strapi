# OOTOPIA STRAPI CMS

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

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
