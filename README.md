# NVD_CHECK

Trial to check NVD data<br>
Get NVD data via [go-cve-dictionary](https://github.com/vulsio/go-cve-dictionary)

![GitHub issue custom search in repo](https://img.shields.io/github/issues-search/witchcraze/NVD_CHECK?color=%23C2E0C6&label=NVD%20Data%20Updated&query=label%3A0_ADOPTED)
![GitHub issue custom search in repo](https://img.shields.io/github/issues-search/witchcraze/NVD_CHECK?color=%23F9D0C4&label=Waiting%20NVD%20side%20review&query=label%3A0_REQUESTED)

## Target

### OS

#### Kernel

- Official
  - `https://www.kernel.org/`
- CPE
  - `cpe:/a:linux:kernel`
  - `cpe:/o:linux:kernel`
  - `cpe:/a:linux:linux_kernel`
  - `cpe:/o:linux:linux_kernel`
  - `cpe:/a:kernel:linux_kernel`
  - `cpe:/o:kernel:linux_kernel`

### Language

#### Go

- Official
  - `https://github.com/golang/go/milestones/*`
- CPE
  - `cpe:/a:golang:go`

#### Node.js

- Official
  - `https://github.com/nodejs/node/tree/main/doc/changelogs/*`
  - `https://github.com/nodejs/security-wg/tree/main/vuln/core/*`
- CPE
  - `cpe:/a:iojs:io.js`
  - `cpe:/a:nodejs:node.js`


#### PHP

- Official
  - `https://github.com/php/php-src/blob/*/NEWS`
  - `https://github.com/php/php-src/blob/*/ChangeLog`
- CPE
  - `cpe:/a:php:php`
  - `cpe:/a:php_group:php`

#### Python

- Official
  - `https://github.com/python/cpython/blob/*/Misc/NEWS.d/*.rst`
  - `https://github.com/python/cpython/blob/*/Misc/NEWS`
  - `https://github.com/python/cpython/blob/*/Misc/HISTORY`
  - `https://bugs.python.org/` (title)
- CPE
  - `cpe:/a:python:python`
  - `cpe:/a:python_software_foundation:python`

#### Ruby

- Official
  - `https://www.ruby-lang.org/en/downloads/releases/`
- CPE
  - `cpe:/a:ruby-lang:ruby`

### Midleware

#### Apache HTTP Server

- Official
  - `https://httpd.apache.org/security/vulnerabilities_*.html`
  - `http://archive.apache.org/dist/httpd/CHANGES_*`
- CPE
  - `cpe:/a:apache:http_server`

#### nginx

- Official
  - `https://nginx.org/en/security_advisories.html`
  - `https://nginx.org/en/CHANGES*`
- CPE
  - `cpe:/a:f5:nginx`
  - `cpe:/a:nginx:nginx`

#### Redis

- Official
  - `https://github.com/redis/redis/releases`
  - `https://github.com/redis/redis/blob/*/00-RELEASENOTES`
- CPE
  - `cpe:/a:pivotal_software:redis`
  - `cpe:/a:redislabs:redis`
  - `cpe:/a:redis:redis`

#### Samba

- Official
  - `https://www.samba.org/samba/security/CVE-*.html`
  - `https://www.samba.org/samba/history/samba-*.html`
- CPE
  - `cpe:/a:samba:samba`

### Database

#### MariaDB

- Official
  - `https://mariadb.com/kb/en/security/`
  - `https://mariadb.com/kb/en/mariadb-server-release-dates/`
- CPE
  - `cpe:/a:mariadb:mariadb`
  - `cpe:/a:mariadb_project:mariadb`

#### PostgreSQL

- Official
  - `https://www.postgresql.org/support/security/`
  - `https://www.postgresql.org/docs/release/`
- CPE
  - `cpe:/a:postgresql:postgresql`

#### MongoDB

- Official
  - `https://www.mongodb.com/resources/products/mongodb-security-bulletins`
  - `https://www.mongodb.com/alerts/rss`
- CPE
  - `cpe:/a:mongodb:mongodb`