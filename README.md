# imgUpload
a plug of imgUpload
.
├── build/                      # webpack配置文件
│   └── ...
├── config/
│   ├── index.js                # 主要项目配置
│   └── ...
├── src/
│   ├── main.js                 # 应用入口文件
│   ├── App.vue                 # 主应用程序组件
│   ├── components/             # ui组件
│   │   └── ...
│   └── assets/                 # 模块资源（由webpack处理）
│       └── ...
├── static/                     # 纯静态资源（直接复制）
├── test/
│   └── unit/                   # 单元测试
│   │   ├── specs/              # 测试spec文件
│   │   ├── index.js            # 测试构建条目文件
│   │   └── karma.conf.js       # 测试跑步者配置文件
│   └── e2e/                    # e2e测试
│   │   ├── specs/              # 测试spec文件
│   │   ├── custom-assertions/  # e2e测试的自定义断言
│   │   ├── runner.js           # 测试跑步脚本
│   │   └── nightwatch.conf.js  # 测试跑步者配置文件
├── .babelrc                    # babel 配置
├── .postcssrc.js               # postcss 配置
├── .eslintrc.js                # eslint 配置
├── .editorconfig               # editor 配置
├── index.html                  # index.html模板
└── package.json                # 构建脚本和依赖关系
