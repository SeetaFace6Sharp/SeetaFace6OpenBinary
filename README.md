# SeetaFace6OpenBinary

SeetaFace6Open��ViewFaceBridge���뾲̬�������ļ���
��������ϵͳ�Լ�ƽ̨��

| ƽ̨  |  ����ϵͳ | ·��  | ��ע  |
| ------------ | ------------ | ------------ | ------------ |
| x64  | Windows  |  SeetaFace\build\bin\x64 |   |
| x86  | Windows  |  SeetaFace\build\bin\x86 |   |
| x64  | Linux  | SeetaFace\build\lib64  |   |
| ARM  | Linux  | SeetaFace\build\lib\arm  |   |
| ARM64  | Linux  | SeetaFace\build\lib\arm64  |   |

### ��ҪĿ¼�ṹ
```shell
.
����CPU
��  ����Bridges
��  ��  ����Linux
��  ��  ��  ����ViewFaceBridge
��  ��  ��      ����bin
��  ��  ��          ����Debug
��  ��  ��          ��  ����ARM
��  ��  ��          ��  ����ARM64
��  ��  ��          ��  ����x64
��  ��  ��          ����Release
��  ��  ��              ����ARM
��  ��  ��              ����ARM64
��  ��  ��              ����x64
��  ��  ����Windows
��  ��      ����ViewFaceBridge
��  ��          ����bin
��  ��              ����Debug
��  ��              ��  ����x64
��  ��              ��  ����x86
��  ��              ����Release
��  ��                  ����x64
��  ��                  ����x86
��  ����SeetaFace
��      ����build
��          ����bin
��          ��  ����x64
��          ��  ����x86
��          ����cmake
��          ����include
��          ����lib
��          ��  ����arm
��          ��  ����arm64
��          ��  ����x64
��          ��  ����x86
��          ����lib64
����GPU
    ����Bridges
    ��  ����Windows
    ��      ����ViewFaceBridge
    ��          ����bin
    ��              ����Debug
    ��              ��  ����x64
    ��              ����Release
    ��                  ����x64
    ����SeetaFace
        ����index
            ����build
                ����bin
                ��  ����x64
                ����cmake
                ����include
                ����lib
                    ����x64
```

### ���ʹ��
��`Bridges`��`SeetaFace`���Ƶ���Ŀ`src`Ŀ¼���漴�ɡ���ʾ�滻ʱ����ֱ���滻��

### ע��
GPU�汾ֻ֧��Windows x64ƽ̨������ƽ̨δ����Ͳ��ԣ��������б��롣�����GPU����CUDA 11.7.1��ʹ��GPU�汾���Ȱ�װCUDA 11.7����Ҫ�Կ�֧�֡�