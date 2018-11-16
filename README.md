mirador-wrapper
===============

A simple deployment of [Mirador](https://github.com/projectmirador/mirador) for the Wikimedia Toolforge.

Deployment
----------

The Ansible playbook will only take you so far. Per [Wikitech](https://wikitech.wikimedia.org/wiki/Help:Toolforge/Web#Running_npm_with_webservice_shell), to deploy the NPM dependencies:

```
webservice --backend=kubernetes nodejs shell
cd $HOME/src
npm install
```
