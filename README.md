
![SPFx WebParts CICD with Office 365 CLI](https://github.com/pankajsurti/spfx-cicd-template/workflows/SPFx%20WebParts%20CICD%20with%20Office%20365%20CLI/badge.svg)

## spfx-CI/CD-Template

This repo is a template to CI/CD for SPFx web parts.
Please follow the SPFx documentation for setting up the development environments.

### How to use this template for your SPFx code?

1. First clone this repo like 
```bash
git clone the repo
```
2. Copy your SPFx code.




### Building the code

```bash
git clone the repo
npm i
npm i -g gulp
gulp
```

This package produces the following:

* lib/* - intermediate-stage commonjs build artifacts
* dist/* - the bundled script, along with other resources
* deploy/* - all resources which should be uploaded to a CDN.

### Build options

gulp clean - TODO
gulp test - TODO
gulp serve - TODO
gulp bundle - TODO
gulp package-solution - TODO
