# Create React app without using create-react-app

## 🛠 Installation & Set Up
1. Check and install correct version of Node
   ```sh
   nvm install
   ```
   ```sh
   node -v
   ```
2. Install pnpm
   ```sh
   npm install -g pnpm@next-7
   ```
3. Install dependencies
    Webpack
   ```sh
   pnpm i --save-dev webpack webpack-cli webpack-dev-server 
   ```
   Babel
   ```sh
   pnpm install --save-dev @babel/core babel-loader @babel/preset-env @babel/preset-react html-webpack-plugin
   ```
4. Install react, react-dom, react-router, react-hooks, react-icons
   ```sh
   pnpm i --save react react-dom react-router react-hooks react-icons
   ```
5. Start the development server
   ```sh
   pnpm start
   ```

## 🚀 Quick start
    ```
    # Install dependencies
    npm install

    # Run Server
    npm run dev-server
    ```
