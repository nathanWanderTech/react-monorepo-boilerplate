# Intro

This is boilerplate for typescript react monorepo using yarn workspaces without any 3rd library or you may want to check out rush.io or lerna.

# Usage

All workspaces is in folder packages, you can create more react app with create-react-app then declare it in root package.json.

Shared folder is for shared components that you want to re-use its codebase. 

All you need to do is create new folder for new component in Shared folder, copy tsconfig and package.json for new component. 

Run yarn build for new component when finish coding. 

Go to which react app need to use that component and declare new dependencies.

Run yarn install for react app and yarn start.

# Author

Nathan Le
