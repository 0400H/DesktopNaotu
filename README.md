# DesktopNaotu

## Steps

1. Setup Node.js
    ```
    https://nodejs.org/dist/v10.24.1/node-v10.24.1-x64.msi
    ```

2. Install packages

    ```
    # npm config set strict-ssl false
    # npm config set registry https://registry.npmmirror.com
    # npm config set ELECTRON_MIRROR "https://npm.taobao.org/mirrors/electron/"
    # npm config set ELECTRON_BUILDER_BINARIES_MIRROR "http://npm.taobao.org/mirrors/electron-builder-binaries/"

    npm install -g gulp@3.9.1
    npm install -g bower

    npm install
    bower install
    ```

3. Build

    ```
    gulp
    ```

4. Test

    ```
    npm run demo
    ```

5. Pack it

    ```
    npm run packwin64dev
    npm run packwin64
    ```