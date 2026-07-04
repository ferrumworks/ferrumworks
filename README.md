# Ferrum Works

### Deployment
[Coolify](https://coolify.io/) see [./compose.yaml](./compose.yaml)  

### Release
Increment version in `config/modpack-update-checker/config.json`  
Copy `options.txt` to `config/modpack_defaults/`  
Copy `config/` to `config/modpack_defaults/config/`  

Create `modpack-update-checker/versions/VERSION/changelog.txt`  
Add to `versions` in `modpack-update-checker/meta.json`  
