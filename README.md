# Leptjson

编写一个JSON库，主要功能包括：

1. 将 JSON 文本解析为一个树状数据结构。
2. 提供接口访问该数据结构。
3. 将数据结构转换成 JSON 文本。

## 项目目录结构
leptjson/

├── build/          # 编译输出目录

├── include/        # 头文件目录

│   └── leptjson.h  # JSON 解析器的头文件

├── src/            # 源代码目录

│   ├── leptjson.c  # JSON 解析实现

│   └── test.c      # 测试代码

├── CMakeLists.txt  # CMake 构建配置文件

└── README.md       # 项目说明文件
