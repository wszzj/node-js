# node.js.server使用说明

## 启动应用
1. 命令行 node server.js 8888
* 命令行显示效果：
![成功](%E5%91%BD%E4%BB%A4%E8%A1%8C%E7%BB%93%E6%9E%9C1.jpg)
* 网页显示效果：
![成功](网页结果1.jpg)
1. 命令行 node server.js 8888 /123(任意字) 
* 命令行显示效果：
![成功](%E5%91%BD%E4%BB%A4%E8%A1%8C%E7%BB%93%E6%9E%9C2.jpg)
* 网页显示效果：
![成功](%E7%BD%91%E9%A1%B5%E7%BB%93%E6%9E%9C2.jpg)
  
## 添加路由
1. 编辑server。js，添加if else语句
2. 重新运行node server.js 8888 /(你设置的参数)

### 使用代码

    console.log("path:" + path);
    
检查bug