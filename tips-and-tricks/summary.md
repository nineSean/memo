## 各种技巧与指令汇总

### npm

- 查看全局安装包(不展开目录)

   > npm list -g --depth 0
   npm ls -g --depth=0
   

### 命令行

- window10 端口被占用报错

  ![image](https://user-images.githubusercontent.com/21988006/29250258-044c303a-8072-11e7-9c2d-70009274618c.png)
  
  - 解决办法

    ```js
    //查询占用了8080端口的进程PID
    netstat -ano|findstr "8080"
    
    //通过PID（比如查询PID为2348）杀死进程
    tskill 2348
    ```
   



