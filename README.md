# Firmware Development Setup Instructions
Written by [@AdrianTarantino](https://github.com/AdrianTarantino)
Last edited July 8, 2026

## Introduction
This tutorial will demonstrate how to setup and use [`STM32CubeIDE for VsCode`](https://e that youmarketplace.visualstudio.com/items?itemName=stmicroelectronics.stm32-vscode-extension) with [`CMake`](https://cmake.org/).

## Prerequisite Software
Download the following software:
- [VsCode](https://code.visualstudio.com/download?_exp_download=fb315fc982)
- [CMake](https://cmake.org/download/)
- [arm-none-eabi development tools](https://developer.arm.com/downloads/-/gnu-rm)
- [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html)

## Create and Select a New VsCode Profile.
This step is optional but highly recommended. Certain VsCode extensions may
interfere with the `STM32CubeIDE for VsCode` extension. If you would like to 
use additional VsCode extensions, complete this setup, verify that it works and
then install any additional extensions that you want.

1. Click the `settings icon` on the bottom left of the screen, then click
`Profile > Profiles`.
2. Click `New Profile` on the top of the pop-up window.
3. Rename the profile to whatever you want. For example, I named the profile
`uwmtr-fw-dev`.
4. Click the `Create` button on the bottom of the screen.
5. Select the profile by clicking the `settings icon`, then clicking 
`Profile > <YOUR PROFILE NAME>`.

## Install and Setup VsCode Extensions.
1. Navigate to the `extensions icon` on VsCode and search for `STM32CubeIDE for VsCode`. Install it.
2. Create the project with `STM32CubeMX` for CMake.
2. In VsCode, type `ctrl+shift+p` then type `CMake: Select Configure Preset` and select `Debug`. git 
