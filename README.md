# customPelias

## Initial Setup 
1. **Uninstall Snap Version of Docker**
     The Snap version of Docker was removed because it cannot properly read `.env` files. ```bash sudo snap remove docker ```
2. **Remove Snap from PATH**
     This ensures the Snap binary path is no longer included. ```bash export PATH=$(echo $PATH | sed 's/:\/snap\/bin//') ```
3. **Install Docker via Official Repository**
      Follow the official Docker installation guide for Ubuntu: 👉 [Docker Installation Guide](https://docs.docker.com/engine/install/ubuntu/#install-using-the-repository) ```
