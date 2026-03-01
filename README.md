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

Warning: For pre-5.4 kernel, you should switch to pre5.4 branch and README.md again
