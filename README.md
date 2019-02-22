# KENDRYTE DOCUMENT PROJECT

[![Build Status](https://travis-ci.org/kendryte/kendryte-doc-datasheet.svg)](https://travis-ci.org/kendryte/kendryte-doc-datasheet)

## How to build

Install gitbook.

```bash
npm install gitbook-cli -g
```

Clone this project.

```bash
git clone https://github.com/kendryte/kendryte-doc-datasheet.git
```

Build this project and view it in web browser, ``$LANG`` is your current language.

| \$LANG  | DESCRIPTION |
| ------- | ----------- |
| en      | English     |
| zh-Hans | 简体中文    |
| zh-Hant | 繁體中文    |

```bash
cd kendryte-doc-ds/$LANG
gitbook install
gitbook serve
```
