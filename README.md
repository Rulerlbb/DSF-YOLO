# DSF-YOLO
the source code of DSF-YOLO algorithm and the full source code of the associated data set. DSF-YOLO(Dynamic Small Object Focused-YOLO) is an enhanced one-stage detection model, which improves small object detection performance and keeps efficient inference via Dynamic Upsampling and Multi-Scale Prediction Heads

## 项目结构

# 项目介绍
    本项目是针对代码工具链生成的DDS服务文件所建立的。
 
    能够将多个DDS服务文件进行合并，构建DDS基本服务端以及客户端程序框架。包含生成server.cpp、client.cpp、CMakeLists.txt
 
# 环境依赖

PyTorch  1.11.0

Python  3.8(ubuntu20.04)

Cuda  11.3
 
# 目录结构描述

## 项目结构
project/
├── data/         # 数据集

        ├── RSOD
        
        ├── Pest24

        ├── Ai Pest Detection Contest
        

├── src/          # 源代码

├── tests/        # 测试用例

└── README.md     # 项目说明文档

    
    │   ├── include_src     // 包含各版本的include、src文件夹
    
    │       ├── V1.0
    
    │           ├── include
    
    │           └── src
    
    │       └── V......
    
    │   └── lib             // 包含各版本的lib文件夹
    
    │       ├── arm64       // 支持arm64系统版本的lib文件夹
    
    │           ├── V1.0
    
    │           └── V......
    
    │       └── x86         // 支持x86系统版本的lib文件夹
    
    │           ├── V1.0
    
    │           └── V......
    
    ├── target              // 合成结果存放的文件夹
    
    └── temp                // 存放待合并的服务的服务文件夹
 
