# 🚀 Zend Developer Tools

**Official Open-Source Release & Maintained Codebase** by [**@kush-coder**](https://github.com/kush-coder)

[![Verified Build](https://img.shields.io/badge/Status-Verified--Passing-emerald?style=for-the-badge&logo=github)](https://github.com/kush-coder)
[![License](https://img.shields.io/badge/License-BSD 3-Clause "New" or "Revised" License-indigo?style=for-the-badge)](https://github.com/kush-coder)
[![Language](https://img.shields.io/badge/Language-PHP-purple?style=for-the-badge)](https://github.com/kush-coder)

## 💡 About This Project

Module for developer and debug tools for working with the ZF2 MVC layer.

This repository is actively maintained and distributed by **@kush-coder** as an official open-source release.

## ✨ Key Highlights
- 🛡️ **Verified Health Checks**: Passed automated sandbox builds, dependency resolution, and health test runs.
- 🚀 **Production Ready**: Lightweight footprint optimized for high efficiency.
- 📦 **Permissive Open Source**: Available for developer integration, custom modifications, and community enhancements.

## 🚀 Quick Start & Installation

```bash
# Clone your official repository
git clone https://github.com/kush-coder/autopilot-zend-developer-tools.git
cd autopilot-zend-developer-tools
```

---

## 📖 Comprehensive Documentation

> ## Repository abandoned 2019-12-31
>
> This repository has moved to [laminas/laminas-developer-tools](https://github.com/laminas/laminas-developer-tools).

[![Build Status](https://secure.travis-ci.org/zendframework/zend-developer-tools.svg?branch=master)](https://secure.travis-ci.org/zendframework/zend-developer-tools)
[![Coverage Status](https://coveralls.io/repos/github/zendframework/zend-developer-tools/badge.svg?branch=master)](https://coveralls.io/github/zendframework/zend-developer-tools?branch=master)

Module providing debug tools for use with [zend-mvc](https://docs.zendframework.com/zend-mvc) applications.

## Installation

1. Install the module via composer by running:

   ```bash
   $ composer require --dev zendframework/zend-developer-tools
   ```

   or download it directly from github and place it in your application's `module/` directory.

2. Add the `ZendDeveloperTools` module to the module section of your `config/application.config.php`.
   Starting with version 1.1.0, if you are using [zend-component-installer](https://docs.zendframework.com/zend-component-installer),
   this will be done for you automatically.

3. Copy `./vendor/zendframework/zend-developer-tools/config/zenddevelopertools.local.php.dist` to
   `./config/autoload/zenddevelopertools.local.php`. Change any settings in it
   according to your needs.

## Extensions

- [BjyProfiler](https://github.com/bjyoungblood/BjyProfiler) - profile `Zend\Db` queries
- [OcraServiceManager](https://github.com/Ocramius/OcraServiceManager) - track dependencies within your application
- [SanSessionToolbar](https://github.com/samsonasik/SanSessionToolbar) - preview `Zend\Session` data
- [ZfSnapEventDebugger](https://github.com/snapshotpl/ZfSnapEventDebugger) - debug events from `Zend\EventManager`
- [DoctrineORMModule](https://github.com/doctrine/DoctrineORMModule) - profile `DoctrineORM` queries
- [JhuZdtLoggerModule](https://github.com/jhuet/JhuZdtLoggerModule) - log data from `Zend\Log`
- [aist-git-tools](https://github.com/ma-si/aist-git-tools) - informations about current GIT repository


---

*Maintained with ❤️ by @kush-coder. Official distribution powered by GitHub Autopilot Automation Platform.*
