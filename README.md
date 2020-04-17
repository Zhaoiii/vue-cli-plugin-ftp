# vue-cli-plugin-ftp

```JavaScript
// 1.安装插件
  vue add ftp

// 2.vue.config.js中设置配置
  pluginOptions: {
    ftp: {
      host: "192.168.31.147", // ftp地址
      remoteFtpPath: "DISK-D/soft/tomcat8/webapps/product/" // 项目地址
     }
  },

// 3.package.json中 build的命令修改为
  vue-cli-service build --no-clean && vue-cli-service ftpdeploy

  ```
