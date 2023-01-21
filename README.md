# SeetaFace6OpenBinary

SeetaFace6Open和ViewFaceBridge编译静态二进制文件。
SeetaFace6Open包含的平台以及路径：

| 平台  |  操作系统 | 路径  | 备注  |
| ------------ | ------------ | ------------ | ------------ |
| x64  | Windows  |  SeetaFace\index\build\bin\x64 |   |
| x86  | Windows  |  SeetaFace\index\build\bin\x86 |   |
| x64  | Linux  | SeetaFace\index\build\lib64  |   |
| ARM  | Linux  | SeetaFace\index\build\lib\arm  |   |
| ARM64  | Linux  | SeetaFace\index\build\lib\arm64  |   |

### 主要目录结构
```shell
.
├─CPU
│  ├─SeetaFace
│  │  └─index
│  │      └─build
│  │          ├─bin
│  │          │  ├─x64
│  │          │  └─x86
│  │          ├─lib
│  │          │  ├─arm
│  │          │  ├─arm64
│  │          │  ├─x64
│  │          │  └─x86
│  │          └─lib64
│  │              └─auto
│  └─SeetaFace6Sharp
│      └─Bridges
│          ├─Linux
│          │  └─SeetaFace6Bridge
│          │      └─bin
│          │          ├─Debug
│          │          │  ├─ARM
│          │          │  ├─ARM64
│          │          │  └─x64
│          │          └─Release
│          │              ├─ARM
│          │              ├─ARM64
│          │              └─x64
│          └─Windows
│              └─SeetaFace6Bridge
│                  └─bin
│                      ├─Debug
│                      │  ├─x64
│                      │  └─x86
│                      └─Release
│                          ├─x64
│                          └─x86
└─GPU
    ├─SeetaFace
    │  └─index
    │      └─build
    │          ├─bin
    │          │  └─x64
    │          └─lib
    │              └─x64
    └─SeetaFace6Sharp
        └─Bridges
            ├─Linux
            │  └─SeetaFace6Bridge
            │      └─bin
            │          ├─Debug
            │          │  ├─ARM
            │          │  ├─ARM64
            │          │  └─x64
            │          └─Release
            │              ├─ARM
            │              ├─ARM64
            │              └─x64
            └─Windows
                └─SeetaFace6Bridge
                    └─bin
                        ├─Debug
                        │  └─x64
                        └─Release
                            └─x64
```

### 如何使用
将`CPU`或`GPU`目录下面的两个文件夹（SeetaFace、SeetaFace6Sharp）复制到项目`src`目录下面即可。提示替换时，可直接替换。

### 注意
GPU版本只支持Windows x64平台，其它平台未编译和测试，可以自行编译。目前已经编译好的CUDA版本，编译工具链基于CUDA 12.0.0，使用GPU请先安装CUDA 12.0且需要显卡支持，应该最低需要GT 1030。
