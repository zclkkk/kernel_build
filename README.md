# MikaKernel Builder

轻轻一点，内核出现！

## 使用方法:

1. Fork 本仓库.

2. 修改 `config.env` 的参数：

   |          参数           | 说明                                 |
   | :---------------------: | ------------------------------------ |
   |    ANYKERNEL_SOURCE     | 你要使用的Anykernel3的仓库           |
   | ANYKERNEL_SOURCE_BRANCH | 你要使用的Anykernel3的仓库的代码分支  |
   |      KERNEL_SOURCE      | 你要编译的内核的源代码仓库            |
   |  KERNEL_SOURCE_BRANCH   | 你要编译的内核的源代码的分支          |
   |      KERNEL_TARGET      | 你的目标机型代号                     |
   |      BUILD_ARGS         | 你的内核编译参数                     |

3. 选中 Actions 选项卡中你要运行的 workflows, 点击 Run workflow 运行.

## 注意事项:

使用 AOSP GCC 4.9 & AOSP Clang r450784d.
