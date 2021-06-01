# hi3516dv300<a name="EN-US_TOPIC_0000001156175291"></a>

-   [Introduction](#section469617221261)
-   [Directory Structure](#section12212842173518)
-   [License Agreement](#section1312121216216)
-   [Repositories Involved](#section641143415335)

## Introduction<a name="section469617221261"></a>

This repository provides the code for building and packaging Hi3516D V300 kernel images.

## Directory Structure<a name="section12212842173518"></a>

```
/device/hisilicon/hi3516dv300
├── build   # Kernel image and multimedia driver build code
├── sdk_linux  # Multimedia patches
└── updater  # Update configuration
```

## License Agreement<a name="section1312121216216"></a>

-   The  **hi3516dv300\\sdk\_linux\\mpp\\bin**  directory stores the HiSilicon-developed libraries, which comply with the end-user license agreement \(EULA\). This directory contains a license file.
-   The  **hi3516dv300\\sdk\_linux\\open\_source\\linux**  directory stores the HiSilicon-developed code, which complies with the HiSilicon \(Shanghai\) copyright statement based on GPL. You can see the following license and copyright information at the beginning of the license file stored in this directory:

    ```
     / *Copyright (c) 2021 HiSilicon (Shanghai) Technologies CO., LIMITED. * ... * /
    ```

-   The  **hi3516dv300\\sdk\_linux\\open\_source\\bin**  directory stores the U-Boot  **.bin**  file. The source code is stored in the  **device\\hisilicon\\third\_party\\uboot\\u-boot-2020.01**  directory. The U-Boot  **.bin**  file complies with the EULA. You can see the following license and copyright information in the license file stored in the  **hi3516dv300\\sdk\_linux\\open\_source\\bin**  directory:

    ```
     / *End User License Agreement ...  Copyright (C) 2021 HiSilicon (Shanghai) Technologies Co., Ltd. All rights reserved. * /
    ```

-   The  **hi3516dv300\\build**  directory stores the HiSilicon-developed code, which complies with the HiSilicon \(Shanghai\) copyright statement based on the Apache License Version 2.0. You can see the following license and copyright information at the beginning of the license file stored in this directory:

    ```
     / *Copyright (c) 2021 HiSilicon (Shanghai) Technologies CO., LIMITED. Licensed under the Apache License,* ... * /
    ```


## Repositories Involved<a name="section641143415335"></a>

**device/hisilicon/hi3516dv300**

