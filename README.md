# 一些笔记


# 如何安装nodejs
如果nodejs已经安装，npm可以运行，请跳过此步
可以考虑先安装nvm，用于nodejs多版本安装和管理
linux和mac可以参考：https://github.com/creationix/nvm
windows可以参考：https://github.com/coreybutler/nvm-windows
```
nvm list
nvm install 8.14.1 32 # 安装32位的nodejs8.14.1
nvm install 8.14.1 64 # 安装64位的nodejs8.14.1
```

# 如何安装yarn
```
cnpm install -g yarn
yarn config set registry https://registry.npm.taobao.org -g
yarn config set sass_binary_site http://cdn.npm.taobao.org/dist/node-sass -g
```

# 如何安装cnpm
```
npm install -g cnpm --registry=https://registry.npm.taobao.org
```

# 如何安装nrm
```
cnpm install -g nrm
nrm ls
nrm use taobao
```
