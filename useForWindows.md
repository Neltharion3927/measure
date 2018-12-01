操作系统：windw10
问题描述：npm install 会报 "NODE_ENV"不是内部或外部命令   
解决办法：需要把##youProjectPath##\packages\chrome-extension-measure-viewer\package.json 
##youProjectPath##\packages\meas-ui\package.json 里所有的NODE_ENV=production 改为set NODE_ENV=production

others:需要安装
npm i measure-export-cli -g 
npm i lerna -g
npm babel-core@6  或以上

部分包版本有误（写此文件时只发现了##youProjectPath##\packages\chrome-extension-measure-viewer\package-lock.json  约3212行 event-stream的版本3.3.6不存在，安装了4.0.1就解决了问题）
