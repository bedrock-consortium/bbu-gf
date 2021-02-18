# Bedrock Business Utility Governance Framework

This repo contains the content resources for the management of the Bedrock Business Utility (BBU) Governance Framework along with the tools necessary to generate two renderings (printed, online) of the BBU-GF documents.

The BBU is a public identity utility operated by the [Bedrock Consortium Project](https://bedrockconsortium.org/).

## Contents

1. Online Governance Framework Docs
    * [GitHub Pages](https://bedrock-consortium.github.io/bbu-gf/)
    * [BBU GF Website Alias](bbu.bedrockconsortium.org/)
2. BBU Governance Framework Docs ([PDF Version](https://github.com/bedrock-consortium/bbu-gf/blob/master/pdf/bedrock-business-utility-gf.pdf))

## Build Process
This repo uses **GitHub Pages** to host the static HTML content that is generated by MkDocs. The ```gh-pages``` branch reflects the latest committed docs. See ```make pages```.

Use  ```make``` to manage the build process for this repo.

```
$ make
```

### Prepare Development Environment (MacOS)

1. Clone repository
2. Setup Environment

```
$ make setup
```

### Develop and test content

```
$ make dev
```

### Generate HTML and PDF Docs
This repo uses ```mkdocs gh-deploy``` to push generated HTML content to GitHub. This process also creates a single PDF document in the ```pdf``` folder but the file is not pushed.

```
$ make pages
```
>Note: You can ignore the DEBUG and WARNING messages during the PDF generation.

## Commit Code
To complete the development process, follow normal **git commit** and **git push** processing. The ```.gitignore``` file will prevent the pushing of the static HTML content.


## Help
Please refer to [mkdocs-pdf-export-plugin](https://github.com/zhaoterryy/mkdocs-pdf-export-plugin) for PDF tooling configuration help.
