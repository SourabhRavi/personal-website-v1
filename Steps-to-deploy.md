# Steps to push to deployment

  - git clone

  - cd chandrikadeb7.github.io

  - source ~/.nvm/nvm.sh

  - nvm install node (version 16) [eg: nvm install 16]

  - incase of any errors with graph-ql or anything, read the error log properly and if needed, use --legacy-peer-deps after any install command [eg: npm install --legacy-peer-deps]

  - npm install -g yarn

  - yarn

  - npm install -g gatsby-cli

  - npm install

  - npm install gh-pages [remember: if any error and if needed, use --legacy-peer-deps with install command]

  - git add .

  - git commit -am "changes"

  - gatsby build

  - npm run deploy
