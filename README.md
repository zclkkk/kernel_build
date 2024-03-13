# MikaKernel Builder

Meow!


## Usage:

1. Fork this repo.

2. Edit `config.env` :

   |        Arguments        | Note                                              |
   | :---------------------: | ------------------------------------------------- |
   |    ANYKERNEL_SOURCE     | Your Anykernel3 repo                              |
   | ANYKERNEL_SOURCE_BRANCH | Your Anykernel3 branch                            |
   |      KERNEL_SOURCE      | Your kernel source repo                           |
   |  KERNEL_SOURCE_BRANCH   | Your kernel source branch                         |
   |      KERNEL_CONFIG      | Your device config                                |
   |       BUILD_ARGS        | Your kernel compile aguments, separate with space |

3. Click `Run workflow` in `Action->Build MikaKernel`

Warning: For pre-5.4 kernel, you should backport LLVM related changes for ur kernel, or just downgrade toolchains defined in build-kernel.yml to android12-dev branch and remove "LLVM=1 LLVM_IAS=1" flags in config.env
