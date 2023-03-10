# 供应商信用风险评估项目

```bash
# 克隆项目
git clone git@gitlab.cnsodata.com:data/risk-assessment-front.git

# 进入项目目录
cd risk-assessment-front

# 安装依赖
npm install

# 建议不要直接使用 cnpm 安装以来，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

浏览器访问 [http://localhost:9528](http://localhost:9528)

## 发布

```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```

## 其它

```bash
# 预览发布环境效果
npm run preview

# 预览发布环境效果 + 静态资源分析
npm run preview -- --report

# 代码格式检查
npm run lint

# 代码格式检查并自动修复
npm run lint -- --fix
```

## 本项目基于[vue-element-admin 4.4.0](https://github.com/PanJiaChen/vue-element-admin)

## TableList的参考文档
` https://gitcode.net/mirrors/njt1340953658/TableList/-/tree/master/src `
