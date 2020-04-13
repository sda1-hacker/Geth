Geth区块链端

==================

一个完整的健康数据上链、访问和交易的区块链生态，去中心化、数据不可篡改就是我们依托于区块链技术的特色。



geth v1.9.12-stable

node v10.16.1+



### 部署步骤

启动脚本：

双击Geth/node1/start_eth.bat



### 项目结构描述

└─Geth  
    ├─.puppeth  
    ├─ganache_node                  // ganache节点，用于测试  
    ├─node1                         // geth节点  
    │   ├─data  
    │   ├─healthchain.json          // 创世文件   
    │   ├─init_eth.bat              // 初始化创世文件脚本  
    │   ├─start_eth.bat             // 运行脚本  
    │   └─data                      // 存储区块链信息  
    │  
    ├─node2                         // geth节点  
    │   ├─data  
    │   ├─healthchain.json          // 创世文件   
    │   ├─init_eth.bat              // 初始化创世文件脚本  
    │   ├─start_eth.bat             // 运行脚本  
    │   └─data                      // 存储区块链信息  
    └─healthchain.json              // 创世文件   
