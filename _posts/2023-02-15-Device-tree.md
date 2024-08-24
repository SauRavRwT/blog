---
layout: post
title: "Device Tree"
author: "SR"
comments: false
---

# About the Android Open Source Project

<img align="center" src="https://source.android.com/static/images/android_stack_720.png" width="500">

Android is an open source operating system for mobile devices and a corresponding open source project led by Google. This site and the Android Open Source Project (AOSP) repository offer the information and source code needed to create custom variants of the Android OS, port devices and accessories to the Android platform, and ensure devices meet the compatibility requirements that keep the Android ecosystem a healthy and stable environment for millions of users.

As an open source project, Android's goal is to avoid any central point of failure in which one industry player can restrict or control the innovations of any other player. To that end, Android is a full, production-quality operating system for consumer products, complete with customizable source code that can be ported to nearly any device and public documentation that is available to everyone (in English at source.android.com and in Simplified Chinese at source.android.google.cn).

Just as you can contribute code to AOSP, you can also contribute to AOSP documentation—and we want your input! Android's flexibility and ever-changing codebase means this site needs your feedback to keep content fresh, accurate, and relevant to Android implementors. We encourage you to check the changelog for details on recent AOSP updates and to report bugs or offer suggestions using the Site Feedback at the bottom of every page (or by visiting g.co/androidsourceissue).

# Generic Kernel Image (GKI) Development

The Generic Kernel Image (GKI) project addresses kernel fragmentation by unifying the core kernel and moving SoC and board support out of the core kernel into loadable vendor modules. GKI also presents a stable Kernel Module Interface (KMI) for vendor modules, so modules and kernel can be updated independently.

Get up-to-date, detailed information and tips on optimizing the Generic Kernel Image (GKI) for your implementation.

<img align="center" src="https://developer.android.com/static/images/cluster-illustrations/success-guide-16-9.svg">

# Device Tree

The Device Tree (DT) is a hierarchical configuration data format that describes the hardware components of a device. Each device is assigned a Device Tree blob (DTB) that describes the hardware components of the device.
The Device Tree is the foundation of the Device Tree Overlay (DTO) technology. DTO lets you add hardware components to a device without changing the core kernel.

The primary purpose of Device Tree in Linux is to provide a way to describe non-discoverable hardware. This information was previously hard coded in source code.

Some more background on what Device Tree is, advantages, and competing solutions, see this page. Most of the contents of this page was previously located at Device_Tree, which now redirects to Device_Tree_Reference.

# Device Tree Overlay (DTO)

The Device Tree Overlay (DTO) technology lets you add hardware components to a device without changing the core kernel.
DTO lets you add hardware components to a device without changing the core kernel.
