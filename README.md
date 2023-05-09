<div align="center">
  <h1>monorepo cli</h1>
  <p>Made for fun</p>
</div>

# install pnpm

```
npm install pnpm -g
```

# install dependencies

```
pnpm install
```

# run app

```
pnpm start
```

# link repos

```
pnpm add [repo_name] --filter [target_repo] --workspace
```

# add new repo

```
cd packages
md [repo_name]
cd [repo_name]
pnpm init
```
