# Native Hadoop Library
## Hadoop 3 Native Library

CMake 3.1 or higher is required for compiling Hadoop 3 native libraries.
### Linux x64
#### Setup
    yum install -y gcc-c++ protobuf-compiler

    wget -O - https://cmake.org/files/v3.12/cmake-3.12.4-Linux-x86_64.tar.gz | tar -C /opt -xz
    export PATH=/opt/cmake-3.12.4-Linux-x86_64/bin:$PATH

    # cmake --version
    cmake version 3.12.4

    # protoc --version
    libprotoc 2.5.0

    # gcc --version
    gcc (GCC) 4.8.5 20150623 (Red Hat 4.8.5-28)

    # mvn --version
    Apache Maven 3.6.0 (97c98ec64a1fdfee7767ce5ffb20918da4f719f3; 2018-10-25T02:41:47+08:00)
    Maven home: /opt/maven-3
    Java version: 1.8.0_192, vendor: Oracle Corporation, runtime: /opt/jdk-8u192/jre
    Default locale: en_US, platform encoding: UTF-8
    OS name: "linux", version: "3.10.0-862.14.4.el7.x86_64", arch: "amd64", family: "unix"

#### Native Library
+ [3.0.3/Linux-x64](3.0.3/Linux-x64)
+ [3.1.1/Linux-x64](3.1.1/Linux-x64)

### Windows x64
#### Setup
    C:\>cmake --version
    cmake version 3.12.4

    C:\>protoc --version
    libprotoc 2.5.0

    C:\>cl
    Microsoft (R) C/C++ Optimizing Compiler Version 19.15.26732.1 for x64
    Copyright (C) Microsoft Corporation.  All rights reserved.

    C:\>link
    Microsoft (R) Incremental Linker Version 14.15.26732.1
    Copyright (C) Microsoft Corporation.  All rights reserved.

    C:\>mvn --version
    Apache Maven 3.6.0 (97c98ec64a1fdfee7767ce5ffb20918da4f719f3; 2018-10-25T02:41:47+08:00)
    Maven home: C:\opt\apache-maven-3.6.0\bin\..
    Java version: 1.8.0_192, vendor: Oracle Corporation, runtime: C:\opt\jdk-8u192\jre
    Default locale: en_US, platform encoding: UTF-8
    OS name: "windows 10", version: "10.0", arch: "amd64", family: "windows"

#### Native Library
+ [3.0.3/Windows-x64](3.0.3/Windows-x64)
+ [3.1.1/Windows-x64](3.1.1/Windows-x64)

## Hadoop 2 Native Library
### Linux x64

Red Hat Enterprise Linux (RHEL) 7 and its derived Linux distributions (e.g. CentOS 7, OEL 7, etc.) are best suited for compiling Hadoop 2 native libraries.
Other Linux distributions require users to download and/or compile the appropriate protoc (2.5.0) and cmake packages themselves.

#### Setup
> yum install -y cmake gcc-c++ protobuf-compiler
```
cmake-2.8.12.2-2.el7.x86_64
gcc-c++-4.8.5-28.el7_5.1.x86_64
protobuf-compiler-2.5.0-8.el7.x86_64
```

#### Native Library
+ [2.7.7/Linux-x64](2.7.7/Linux-x64)
+ [2.8.5/Linux-x64](2.8.5/Linux-x64)
+ [2.9.1/Linux-x64](2.9.1/Linux-x64)
+ [2.9.2/Linux-x64](2.9.2/Linux-x64)
