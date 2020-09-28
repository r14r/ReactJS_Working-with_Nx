# [Tutorial: ntro to React](https://nx.dev/react/tutorial/01-create-application)

## Create Workspace and App

```sh
$ npx create-nx-workspace@latest getting_started
npx: Installierte 193 in 809.979s
? What to create in the new workspace react             [a workspace with a single React application]
? Application name                    app_nx_react
? Default stylesheet format           SASS(.scss)  [ http://sass-lang.com   ]
? Use the free tier of the distributed cache provided by Nx Cloud? No  [Only use local computation cache]
```

```sh
cd getting-started
nx serve  app-nx-react
```

### Add node.js api app

```sh
npm install --save-dev @nrwl/express
```

### Add Ionic App

```sh
npm install --save-dev @nxtend/ionic-react
```

## [Create Angular App](https://www.htmlelements.com/docs/create-angular-and-react-applications-with-shared-web-components/)

```sh
npx --ignore-existing create-nx-workspace workspace --preset=empty
npx: Installierte 193 in 141.993s
? CLI to power the Nx workspace       Nx           [Recommended for all applications (React, Node, etc..)]
? Use the free tier of the distributed cache provided by Nx Cloud? No  [Only use local computation cache]

yarn add -D @nrwl/angular

nx g @nrwl/angular:application app-angular

```

