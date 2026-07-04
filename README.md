<img width="902" height="145" alt="image" src="https://github.com/user-attachments/assets/756b258a-2d8a-483f-a99e-26a725f09b78" />

# Ferrum Works

### Deployment
[Coolify](https://coolify.io/) see [./compose.yaml](./compose.yaml)  

### Release
Increment version in `config/modpack-update-checker/config.json`  
Increment version in `config/bcc.json`  
Copy `options.txt` to `config/modpack_defaults/`  
Copy `config/` to `config/modpack_defaults/config/`  

Create `modpack-update-checker/versions/VERSION/changelog.txt`  
Add to `versions` in `modpack-update-checker/meta.json`  
