# vuepress-base

vuepress init project

## Init method

```bash
npx create-vuepress-site vuepress-base
```
log
```bash
zuo-mac:vuepress zuo$ npx create-vuepress-site vuepress-base
? What's the name of your project? vuepress-base
? What's the description of your project? vuepress init project
? What's your email? xx@xx.com
? What's your name? dev-zuo
? What's the repo of your project? 
   create vuepress-base/docs/.npmignore
   create vuepress-base/docs/package.json
   create vuepress-base/docs/src/.vuepress/components/demo-component.vue
   create vuepress-base/docs/src/.vuepress/components/Foo/Bar.vue
   create vuepress-base/docs/src/.vuepress/components/OtherComponent.vue
   create vuepress-base/docs/src/.vuepress/config.js
   create vuepress-base/docs/src/.vuepress/enhanceApp.js
   create vuepress-base/docs/src/.vuepress/styles/index.styl
   create vuepress-base/docs/src/.vuepress/styles/palette.styl
   create vuepress-base/docs/src/config/README.md
   create vuepress-base/docs/src/guide/README.md
   create vuepress-base/docs/src/guide/using-vue.md
   create vuepress-base/docs/src/index.md
📋 Copied to clipboard, just use Ctrl+V
✨ File Generate Done
zuo-mac:vuepress zuo$ cd vuepress-base
zuo-mac:vuepress-base zuo$ ls
docs
```

## Use
```bash
cd cd vuepress-base;cd docs;
npm install
npm run dev
# 运行成功后 log，访问 http://localhost:8080/ 即可打开基础页面
# success [19:36:34] Build 9c42be finished in 15647 ms! 
# > VuePress dev server listening at http://localhost:8080/
```

## rely on
cat vuepress/docs/package.json 
```json
{
  "name": "vuepress-base",
  "version": "0.0.1",
  "description": "vuepress init project",
  "main": "index.js",
  "authors": {
    "name": "dev-zuo",
    "email": "xx@xx.com"
  },
  "repository": "/vuepress-base",
  "scripts": {
    "dev": "vuepress dev src",
    "build": "vuepress build src"
  },
  "license": "MIT",
  "devDependencies": {
    "vuepress": "^1.5.3"
  }
}
```
