# MulL

![MulL](https://enuwbt.neocities.org/images/ic_mull.png)

![English](https://img.shields.io/badge/English-inactive?style=for-the-badge)
[![Japanese](https://img.shields.io/badge/Japanese-informational?style=for-the-badge)](README-ja.md)

MulL is an unofficial Minecraft:PE utility client created to provide users with rendering customization, simple scripting, and special features.

## Table of contents

- [Attention](#attention)
- [Security](#security)
- [Install](#install)
- [Usage](#usage)
- [Introduction](#Introduction)
- [Feature](#feature)
- [Issue](#issue)

## Attention

In order to prevent the creation of a Hacked Client for Minecraft:PE, I will refrain from releasing the source code for MulL.

## Security

This application is designed to allow users to extend the functionality of Minecraft:PE by launching and operating the application. This application is not affiliated with Mojang Studios or Microsoft Corporation. The developer is not responsible for the quality, functionality, safety, or legality provided by this application. Use of this application is at the user's own discretion and risk.

The Developer does not guarantee the stability, reliability, accuracy, or completeness of this application. The Developer is not responsible for any defects, errors, viruses, or other harmful components that may be present in this application. Developer is not liable for any direct or indirect damages (including but not limited to loss of data, damage to your device, loss of profits, etc.) resulting from the use of this software.

The Developer reserves the right to change, update, or terminate this application and its related services at any time without prior notice to the User.

When using this application, the User shall comply with all relevant laws and regulations, respect the intellectual property and privacy rights of others, and shall not use the Application for any illegal or infringing activities. The developer shall not be liable for any damage caused to a third party or any claims made by a third party in violation of the above provisions by the user.

## Install

You can obtain the apk of this application from [release]()

## Usage

### Launch Tab
![Launch Tab](https://enuwbt.neocities.org/images/mull_launch_tab.jpg)

・Press "Launch" button to start minecraft

### System Tab
![System Tab](https://enuwbt.neocities.org/images/mull_system_tab.jpg)

・Configure settings related to the system. This allows the user to use special functions. However, these may become incompatible and unavailable with Minecraft updates.

### Setting Tab
![Setting Tab](https://enuwbt.neocities.org/images/mull_setting_tab.jpg)

・Configure settings related to the application.

## Introduction

Like Toolbox for Minecraft and BlockLauncher, MulL is a comprehensive launcher-type client, but unlike them, which require regular maintenance of the application itself whenever Minecraft is updated, **MulL will not lose launch compatibility unless a destructive update is made to Minecraft.**

At the same time, MulL is meant to be a pilot application and stability cannot be guaranteed. In addition, most of the special features offered by MulL rely on low-level layers and are more susceptible to Minecraft updates.

Note that regular updates will be released before MulL adapts to these issues.

## Feature

### MaterialBin Override

When "MaterialBin Override" is enabled, the following features are provided

- Load material.bin from resource packs

### Client Modules

When "Client Modules" is enabled, the following features are provided

![Features](https://enuwbt.neocities.org/images/mull_features.jpg)

- New video setting
- Render chunkmap
- Disable render entities
- Disable render block entities
- Disable render weather
- Disable render particles

## Issue

### Crash when signing in to Xbox

It is speculated that the bug is caused by a difference in the versions of WebView used by MulL and Minecraft.
However, the sign-in itself continues and the operation is successfully completed.

### Licence error

This is caused when MulL is unable to successfully negotiate with the Minecraft/GooglePlay servers.
Please restart after some time.

### Resource pack loading crash

MulL does not support launching an intent startup.
Therefore, in order to load a resource pack in MulL, you must start Minecraft on MulL before loading it.
This issue will be resolved in a subsequent update.
