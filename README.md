# 商城 HBuilderX 工程转换 Vue-Cli 工程模板

#### 本项目创建使用命令
```shell
# 使用默认模版创建
vue create  -p dcloudio/uni-preset-vue hbs-preset-template
```

### 使用环境部署
```shell
# 复制 HBuilderX 源码到 Vue-Cli 工程 src 目录下
git clone https://gitee.com/xxxxxx/hbx2vue-project-template.git
cp -rp uniapp项目文件/* hbx2vue-project-template/src/

cd hbx2vue-project-template
rm -rf src/node_modules src/unpackage
npm install --registry=https://registry.npm.taobao.org
npm install --save js-md5 tim-wx-sdk --registry=https://registry.npm.taobao.org
npm install node-sass --registry=https://registry.npm.taobao.org
npm install sass-loader --registry=https://registry.npm.taobao.org
```

### 编译使用
```shell
# 微信小程序编译
npm run build:mp-weixin
```

