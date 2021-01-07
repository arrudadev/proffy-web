<h1 align="center">
    <img alt="Proffy" title="Proffy" src=".github/assets/logo.svg" width="220px" />
</h1>

<h4 align="center">
  🚀 Next Level Week #02 - Web
</h4>

> Proffy is an online study platform that helps people find teachers online. This is the web version.

<div align="left">

[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
</div>

# :pushpin: Table of Contents

* [Screenshots](#camera-screenshots)
* [Installation](#construction_worker-installation)
* [Getting Started](#runner-getting-started)
* [Found a bug? Missing a specific feature?](#bug-issues)
* [Contributing](#tada-contributing)
* [License](#closed_book-license)

# :camera: Screenshots

Click to expand.<br>

<img src=".github/assets/landing.png" width="49%"/>
<img src=".github/assets/teachers.png" width="49%"/>
<img src=".github/assets/form.png" width="49%"/>

# :construction_worker: Installation

**You need to install [Node.js](https://nodejs.org/en/download/) and [Yarn](https://yarnpkg.com/) first, then in order to clone the project via HTTPS, run this command:**

```
git clone https://github.com/monteiro-alexandre/proffy-web.git
```

SSH URLs provide access to a Git repository via SSH, a secure protocol. If you use a SSH key registered in your Github account, clone the project using this command:

```
git clone git@github.com:monteiro-alexandre/proffy-web.git
```

**Install dependencies**

```
yarn install
```

Or

```
npm install
```

Create your environment variables based on the examples of ```.env.example```

```
cp .env.example .env
```

After copying the examples, make sure to fill the variables with new values.

key|description|example
---|---|---
REACT_APP_API_BASE_URL|API's url|`http://localhost:3333`

# :runner: Getting Started

Run the following command to start the application in a development environment:

```yarn start```

# :bug: Issues

Feel free to **file a new issue** with a respective title and description on the the [Proffy API](https://github.com/monteiro-alexandre/proffy-web/issues) repository. If you already found a solution to your problem, **I would love to review your pull request**! Have a look at our [contribution guidelines](https://github.com/monteiro-alexandre/proffy-web/blob/master/CONTRIBUTING.md) to find out about the coding standards.

# :tada: Contributing

Check out the [contributing](https://github.com/monteiro-alexandre/proffy-web/blob/master/CONTRIBUTING.md) page to see the best places to file issues, start discussions and begin contributing.

# :closed_book: License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.