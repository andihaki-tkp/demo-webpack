This is a bare minimum project with react and unify. You have to fork this repo and create webpack config to meets the basic requirements below. There are modules and plugins installed by default on packages.json, but feel free to adjust based on your needs.

The basic requirements:
- [x] Support css
- [ ] Create multiple bundle output with this criteria:
  - [x] Dependency react, react-dom, react-emotion, and emotion use chunk name `framework.[contenthash].js`
  - [x] All unify dependencies use chunk name `unify.[contenthash].js`
  - [x] The rest node_modules dependencies use chunk name `vendor.[contenthash].js`
  - [x] The runtime code use chunk name `runtime.[contenthash].js`
- [x] All assets should be minified in production build, except in development env
- [x] All chunk name should has `contenthash` in production build, except in development env
