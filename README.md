# HHI Definitions For Container Interop (PSR11), Container Interface

This repository contains .hhi files for the interfaces defined in Container Interop(PSR-11).

It is based on the PHP interface definitions and comments available here:

https://github.com/php-fig/container

## install 
```bash
$ hhvm --php $(which composer) require ytake/psr-container-hhi
```

or 

```json
"require": {
  "hhvm": ">=3.9.0",
  "ytake/psr-container-hhi": "~1.0"
},
```

```bash
$ hhvm --php $(which composer) update;
# or
$ hhvm --php $(which composer) install;
```
