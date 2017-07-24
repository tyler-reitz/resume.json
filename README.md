# resume-json

[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

> My personal resume toolkit
This repository provides a starting point for anyone looking to kick off their own resume-toolkit based on [hackmyresume](https://please.hackmyresume.com/)’s node module and the [FRESH](https://github.com/fluentdesk/FRESCA) or [JSONResume](http://jsonresume.org/) schemas. 

See [hackmyresume](https://please.hackmyresume.com/) for more details on customization.

## Table of Contents

- [Install](#install)
- [Usage](#usage)
- [Maintainers](#maintainers)
- [License](#license)

## Install

```
git clone https://github.com/tyler-reitz/resume.json.git
```
and then
```
npm install
```

## Usage

After installation, alter the `resume-fresh.json` file to suit your personal details and needs. Then run:

```
npm run build
```
*outputs to `dist/`*

```
npm run validate
```
*validates the specified resume against either the FRESH or JSON Resume schema. Use it to make sure your resume data is sufficient and complete*

```
npm run analyze
```
*inspects your resume for keywords, duration, and other metrics.* 

## Maintainers

[@tyler-reitz](https://github.com/tyler-reitz)

## License

MIT © 2017 Tyler Reitz
