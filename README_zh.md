# hi3516dv300 build组件<a name="ZH-CN_TOPIC_0000001156175291"></a>

-   [简介](#section469617221261)
-   [目录](#section12212842173518)
-   [协议说明](#section1312121216216)
-   [对应仓库](#section641143415335)

## 简介<a name="section469617221261"></a>

hi3516dv300内核镜像编译打包。

## 目录<a name="section12212842173518"></a>

```
/device/hisilicon/hi3516dv300
├── build   # 内核镜像及多媒体驱动编译
├── sdk_linux  # 多媒体相关patch
└── updater  # 升级相关配置
```

## 协议说明<a name="section1312121216216"></a>

-   hi3516dv300\\sdk\_linux\\mpp\\bin里面为上海海思的自研库，遵从End User License Agreement许可，目录下有对应LICENSE文件。
-   hi3516dv300\\sdk\_linux\\open\_source\\linux目录下为上海海思自研代码，使用基于GPL许可的Hisilicon \(Shanghai\) 版权声明，在该目录下有License目录，许可信息和版权信息通常可以在文件开头看到：

    ```
     / *Copyright (c) 2021 HiSilicon (Shanghai) Technologies CO., LIMITED. * ... * /
    ```

-   hi3516dv300\\sdk\_linux\\open\_source\\bin目录下为uboot bin文件，源码在device\\hisilicon\\third\_party\\uboot\\u-boot-2020.01路径下，uboot bin文件遵从End User License Agreement许可，在该目录下有End User License Agreement 的LICENSE文件，许可信息和版权信息通常可以在文件中看到：

    ```
     / *End User License Agreement ...  Copyright (C) 2021 Hisilicon (Shanghai) Technologies Co., Ltd. All rights reserved. * /
    ```

-   hi3516dv300\\build目录为自研代码，使用基于Apache License Version 2.0许可的Hisilicon \(Shanghai\) 版权声明，在该目录下有Apache License Version 2.0的LICENSE文件，许可信息和版权信息通常可以在文件开头看到：

    ```
     / *Copyright (c) 2021 HiSilicon (Shanghai) Technologies CO., LIMITED. Licensed under the Apache License,* ... * /
    ```


## 对应仓库<a name="section641143415335"></a>

**device/hisilicon/hi3516dv300**

