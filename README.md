
# <img src="https://www-assets.particle.io/images/logo.png" width="35"> Particle
Particle projects.

## Development
### Software
- [Particle CLI][cli]
```
npm install -g particle-cli
```

#### Getting Started
##### Login
```bash
particle login
# input credentials
```

##### Add Device
```bash
# Connect device to cellular network
particle device add <ID>
particle rename <ID> <generic-name>
```

##### Compiling code
```bash
particle compile electron path/to/sketch.ino
```
## Hardware
[Electron][electron] 3G

[ide]: https://docs.particle.io/guide/tools-and-features/dev
[cli]: https://docs.particle.io/reference/cli/
[electron]: https://www.particle.io/products/hardware/electron-cellular-dev-kit
