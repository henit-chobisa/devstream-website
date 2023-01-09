# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

## 💻 Start contributing from any browser or Chromebook

  Start developing and make changes to the code via a single click without any prior setup for free **Anytime-Anywhere**!

  [![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/devstream-io/website)

  Some *Recommendations* while using **Gitpod**:

  - Download the [gitpod browser extension](https://www.gitpod.io/docs/configure/user-settings/browser-extension) to start working on any branch,issue or PR via a single click in under a minute!
  - To enjoy *BLAZINGLY FAST* startup times while developing on your forked branches, consider [enabling prebuilds by installing Gitpod's GitHub App](https://www.gitpod.io/docs/configure/projects/prebuilds/#configuring-prebuilds-manually)

  ---

### Installation

**Requirements**

* node@16

```
$ npm install
```

### Local Development

```
$ npm run start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
