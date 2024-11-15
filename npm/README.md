# 设置代理
npm config set proxy=http://127.0.0.1:7890
npm config set registry=http://127.0.0.1:7890

# 取消代理
npm config delete proxy
npm config delete https-proxy

# 查看安装版本
npm view npm version -json

# 设置全局路径/缓存路径
npm config set prefix "D:\nvm\node_global"
npm config set cache "D:\nvm\node_cache"
