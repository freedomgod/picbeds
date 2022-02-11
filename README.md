jsDelivr+Npm图床，通过如下方式更新图片：

```
git add .
git commit -m "npm publish"
# 更新package版本号
npm version patch
# 推送至github触发action
git push
```

