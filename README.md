# theia-ide

My own custom [Theia IDE](https://theia-ide.org). I run this on a powerful Cloud
desktop, hence I am not worried about the large number of plugins. However, if
you are running it on a not-so-powerful machine, or you simply know exactly what
plugins you need, then you should remove unused plugins from the `package.json`
file.

## Pre-requisites

See
[Prerequisites](https://github.com/eclipse-theia/theia/blob/master/doc/Developing.md#prerequisites)
section on [eclipse-theia/theia](https://github.com/eclipse-theia/theia/blob/master/doc/Developing.md#prerequisites)
GitHub page.

## Building

```shell
yarn
yarn theia build
```

## Running

```shell
yarn start --hostname 0.0.0.0 --port 8080
```

Optionally, you can also provide a path to the workspace:

```shell
yarn start /my-workspace --hostname 0.0.0.0. --port 8080
```

