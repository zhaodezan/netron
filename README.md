1. upgrade the nodejs to the latest version  
2.
  sudo npm install -g cross-env  
  cross-env npm_config_electron_mirror="https://npm.taobao.org/mirrors/electron" npm_config_electron_custom_dir="13.1.4" npm install  
  make build  
you can read the package.json to see the npm version
3.   
./dist/linux-unpacked/netron  

文件结构  
test  
  --models.js       开始测试，main函数  
  --models.json 测试模型文件  
source  
  --mslite.js 核心文件  
  --mslite-metadata.json 资料，不需要写  
  --mslite-schema.js 不需要写  
tools  
  --mslite 生成主入口  
  --mslite-script.js 生成mslite-metadata.json  
  --flatc.js 生成mslite-schema.js  
