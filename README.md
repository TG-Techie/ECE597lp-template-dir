# Nordic Thingy:52 SDK

Welcome to the Nordic Thingy:52 software development kit.
This kit is designed to assist users in developing their own custom firmware for Thingy.
Please see http://www.nordicsemi.com/thingy for the latest news and software releases.

Consult the [firmware documentation](https://nordicsemiconductor.github.io/Nordic-Thingy52-FW/documentation/index.html) for more details.

## Prerequisites

Before running the scripts below, make sure you have the following software installed:
1. Git v2.xx.xx, Available from https://git-scm.com/. Use default configurations.
2. Install GNU ARM embedded toolchain v4.9-2015q3. Available from https://launchpad.net/gcc-arm-embedded/4.9/4.9-2015-q3-update. Use default configurations.
3. Make must be installed and be in system path. For example http://gnuwin32.sourceforge.net/packages/make.htm.
4. Create a user at https://www.invensense.com/. Under "Downloads" download "Embedded MotionDriver 6.12". Unzip the downloaded `motion_driver_6.12` folder and navigate to `motion_driver_6.12/mpl libraries/arm/Keil`.
Unzip the folder `libmpllib_Keil_M4FP.zip`. Copy the extracted library `libmpllib.lib` into `<your Thingy folder>/libs/libmpllib_Keil_M4FP/`. Finally, unzip `/motion_driver_6.12/mpl libraries/arm/gcc4.9.3/liblibmplmpu_m4_hardfp.zip` and copy the extracted library `liblibmplmpu.a` into the folder `<your Thingy folder>/libs/liblibmplmpu_m4_hardfp/`.

### Bluetooth SoftDevice
Thingy FW version 2.0.0 is compatible with softdevice [s132 v4.0.2](https://www.nordicsemi.com/eng/nordic/Products/nRF52832/S132-SD-v4/58803)

## Setting up the SDK
Run `setup_sdk.bat` on Windows or `setup_sdk.sh` on Linux/Mac.

These scripts will download and compile the [micro-ecc](https://github.com/kmackay/micro-ecc/archive/master.zip) library and set up symbolic links.

## Compiling the code
To compile the code, please consult the compiling new [firmware page](https://nordicsemiconductor.github.io/Nordic-Thingy52-FW/documentation/firmware_compile.html) in the [firmware documentation](https://nordicsemiconductor.github.io/Nordic-Thingy52-FW/documentation/index.html).



## Getting started

To make it easy for you to get started with GitLab, here's a list of recommended next steps.

Already a pro? Just edit this README.md and make it your own. Want to make it easy? [Use the template at the bottom](#editing-this-readme)!

## Add your files

- [ ] [Create](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#create-a-file) or [upload](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#upload-a-file) files
- [ ] [Add files using the command line](https://docs.gitlab.com/ee/gitlab-basics/add-file.html#add-a-file-using-the-command-line) or push an existing Git repository with the following command:

```
cd existing_repo
git remote add origin https://gitlab.com/amahmed/ece697lp-tutorial0.git
git branch -M main
git push -uf origin main
```

## Integrate with your tools

- [ ] [Set up project integrations](https://gitlab.com/amahmed/ece697lp-tutorial0/-/settings/integrations)

## Collaborate with your team

- [ ] [Invite team members and collaborators](https://docs.gitlab.com/ee/user/project/members/)
- [ ] [Create a new merge request](https://docs.gitlab.com/ee/user/project/merge_requests/creating_merge_requests.html)
- [ ] [Automatically close issues from merge requests](https://docs.gitlab.com/ee/user/project/issues/managing_issues.html#closing-issues-automatically)
- [ ] [Enable merge request approvals](https://docs.gitlab.com/ee/user/project/merge_requests/approvals/)
- [ ] [Automatically merge when pipeline succeeds](https://docs.gitlab.com/ee/user/project/merge_requests/merge_when_pipeline_succeeds.html)

## Test and Deploy

# Nordic Thingy:52 SDK

Welcome to the Nordic Thingy:52 software development kit.
This kit is designed to assist users in developing their own custom firmware for Thingy.
Please see http://www.nordicsemi.com/thingy for the latest news and software releases.

Consult the [firmware documentation](https://nordicsemiconductor.github.io/Nordic-Thingy52-FW/documentation/index.html) for more details.

## Prerequisites

Before running the scripts below, make sure you have the following software installed:
1. Git v2.xx.xx, Available from https://git-scm.com/. Use default configurations.
2. Install GNU ARM embedded toolchain v4.9-2015q3. Available from https://launchpad.net/gcc-arm-embedded/4.9/4.9-2015-q3-update. Use default configurations.
3. Make must be installed and be in system path. For example http://gnuwin32.sourceforge.net/packages/make.htm.
4. Create a user at https://www.invensense.com/. Under "Downloads" download "Embedded MotionDriver 6.12". Unzip the downloaded `motion_driver_6.12` folder and navigate to `motion_driver_6.12/mpl libraries/arm/Keil`.
Unzip the folder `libmpllib_Keil_M4FP.zip`. Copy the extracted library `libmpllib.lib` into `<your Thingy folder>/libs/libmpllib_Keil_M4FP/`. Finally, unzip `/motion_driver_6.12/mpl libraries/arm/gcc4.9.3/liblibmplmpu_m4_hardfp.zip` and copy the extracted library `liblibmplmpu.a` into the folder `<your Thingy folder>/libs/liblibmplmpu_m4_hardfp/`.

### Bluetooth SoftDevice
Thingy FW version 2.0.0 is compatible with softdevice [s132 v4.0.2](https://www.nordicsemi.com/eng/nordic/Products/nRF52832/S132-SD-v4/58803)

## Setting up the SDK
Run `setup_sdk.bat` on Windows or `setup_sdk.sh` on Linux/Mac.

These scripts will download and compile the [micro-ecc](https://github.com/kmackay/micro-ecc/archive/master.zip) library and set up symbolic links.

## Compiling the code
To compile the code, please consult the compiling new [firmware page](https://nordicsemiconductor.github.io/Nordic-Thingy52-FW/documentation/firmware_compile.html) in the [firmware documentation](https://nordicsemiconductor.github.io/Nordic-Thingy52-FW/documentation/index.html).

