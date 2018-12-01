操作系统：windw10
问题描述：npm install 会报 "NODE_ENV"不是内部或外部命令   
解决办法：需要把##youProjectPath##\packages\chrome-extension-measure-viewer\package.json 
##youProjectPath##\packages\meas-ui\package.json 里所有的NODE_ENV=production 改为set NODE_ENV=production
