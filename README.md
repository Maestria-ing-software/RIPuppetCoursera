# RIPuppet
A node js library for GUI Ripping on web applications

# Executing
To execute the testing tool use the following command:

```
node index.js url headless

```

For example:

```
node index.js https://github.com true

```

Hola a todos si tienen linux y tienen problemas con RIPuppet a me me sirvio hacer lo siguiente:
git clone https://github.com/TheSoftwareDesignLab/RIPuppetCoursera.git
ubicarse en la carpeta del proyecto
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
reiniciar el terminal
nvm --version
nvm install 14.4.0.
npm init playwright@latest
despues ingresar al archivo index.js y en la linea 135 cambiar networkidle2 por networkidle0
por ultimo ejecutar
node index.js
