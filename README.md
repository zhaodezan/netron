1. upgrade the nodejs to the latest version  
2.
  sudo npm install -g cross-env  
  cross-env npm_config_electron_mirror="https://npm.taobao.org/mirrors/electron" npm_config_electron_custom_dir="13.1.4" npm install  
  make build  
you can read the package.json to see the npm version
3.   
./dist/linux-unpacked/netron  
