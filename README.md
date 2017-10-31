# AutoStart NodeJS Server
AutoStart NodeJS Server in most reliable way using Windows Services.

### Install Node Windows

```
C:\AutoStartNodeJS> npm install node-windows --save
```

### Wrapper for Easier Way to Run Service

```
C:\> npm install -g qckwinsvc
```

### Installing the service example

```
C:\> qckwinsvc
prompt: Service name: BuildingBlocks
prompt: Service description: Building Blocks of ExpressJS
prompt: Node script path: E:\Practice\NodeJS\BuildingBlocks\app.js
prompt: Should the service get started immediately? (y/n): y
Service installed.
Service started.
```
### Uninstalling the service example

```
C:\> qckwinsvc --uninstall
prompt: Service name: BuildingBlocks
prompt: Node script path: E:\Practice\NodeJS\BuildingBlocks\app.js
Service stopped
Service uninstalled
```

### Install Node Modules from package.json

```
C:\AutoStartNodeJS> npm install
```

### Original Discussion

- [Auto start node.js server on boot](https://stackoverflow.com/questions/20445599/auto-start-node-js-server-on-boot)
