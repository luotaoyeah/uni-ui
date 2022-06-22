# 发布

1. 修改 uni_modules/uni-ui/package.json 中的 version
2. 执行 `npm run build:lib`
3. 执行 `npm run publish:npm`

```
npmrc thymine && npm publish ./packages --registry https://registry.npmjs.org/ --access public
```