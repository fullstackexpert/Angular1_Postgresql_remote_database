Angular 1 Postgresql remote database bower (Interview)
===========================

This repository consists of both the node.js backend `/server/*` and Angular.js frontend `/client/`.

## Prerequisites

* Node.js: v6.10 or higher
* Global installation of npm, bower, grunt

## Installation instructions

```bash
npm install
bower install
```

Upon successful completion of the installation, modify the database connection string in `server/config/db.js` using the provided credentials. To start the project, execute:

```bash
grunt serve
```

Open the website in Chrome and make sure there are no errors in the developer console.
