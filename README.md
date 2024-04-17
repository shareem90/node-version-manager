# node-version-manager (Windows)
Node-Version-Manager allows you to effortlessly switch between different versions of Node.js for your projects without needing to uninstall the current version.

1. Go to "Add and remove programs" and uninstall Nodejs

2. Download and install nvm-setup.exe from
https://github.com/coreybutler/nvm-windows/releases

3. Open a command prompt.
Check the nvm version.
> nvm --version

4. Install a node version. E.g. the version used for emotion analytics.
> nvm install 16.20.2

5. List available node versions
> nvm ls
All node versions are installed at C:\Users\Admin\AppData\Roaming\nvm

6. Switch to a node version
> nvm use 16.20.2
Windows should prompt you for adminstrator rights. If it doesn't, rerun cmd as administrator and repeat the step. This will create the symbolic link C:\Program Files\nodejs.

7. Check the node version.
> node --version

8. Install another node version and switch to it. E.g. the current LTS version.
> nvm install lts
> nvm use lts

Updated as of 18 April 2024
