# Steps to push to deployment

  1. open git bash in your current project directory and use

   ```sh
   source ~/.nvm/nvm.sh
   ```

  2. nvm install node (version 16);

  ```sh
   nvm install 16
   ```

  3. if nvm isn't installed, install it first

   ```sh
   curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash
   ```

  4. incase of any errors with graph-ql or anything, read the error log properly and if needed, use --legacy-peer-deps after any install command

  ```sh
  npm install --legacy-peer-deps
  ```

  5. Install yarn

  ```sh
  npm install -g yarn
  ```

  6. Install dependencies

  ```sh
  yarn
  ```

  6. Install Gatsby CLI

  ```sh
  npm install -g gatsby-cli
  ```

  7. Install dependencies

  ```sh
  npm install
  ```

  8. Install GitHub Pages

  ```sh
  npm install gh-pages
  ```
  [Remember: if any error and if needed, use --legacy-peer-deps with install command]

  9. Add changes in the working directory to the staging area

  ```sh
  git add .
  ```

  10. Commit 

  ```sh
  git commit -am "changes"
  ```

  11. Generate a full static production build
  
  ```sh
  gatsby build
  ```

  12. Preview the site as it will appear once deployed

   ```sh
  npm run serve
  ```

  13. Deploy

  ```sh
  npm run deploy
  ```
