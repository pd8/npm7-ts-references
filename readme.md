# Monorepo - NPM 7 Workspaces - TS references - Create React App Test

A test repo that sets up an npm 7 workspace, and builds packages using TS project references, while consuming a dependency from a create-react-app application.

`npm i` from the repository root
`npm run build` to build all the packages (this will only build what needs to be built)
`cd packages/app`
`npm run dev` the app should start!

## Todo

- Figure out how to get CRA's fast refresh working
- Can we get CRA to do a `tsc -b` which would understand its trying to build with references and hopefully build faster
