# turbo repo(monorepo) + yarn berry

# command

```bash
  npx create-turbo@latest (select yarn)
  yarn set version stable

  # edit .yarnrc.yml
  nodeLinker: pnp

  yarn install

  # typescript - vscode
  yarn dlx @yarnpkg/sdks vscode

  # typescript - 의존성 자동설치 plugin
  yarn plugin import typescript

  yarn dev
  yarn build
```