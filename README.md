# yarn-offline

## Quick Start

First, add packages to `package.json` at online.

```shell
yarn add <package_name>
```

or

```shell
yarn add -D <package_name>
```

Second, download all packages as tar ball to [offline-cache][] at online.

```shell
yarn online:download
```

Finally, install packages from [offline-cache][] at offline.

```shell
yarn offline:install
```

[offline-cache]: ./offline-cache