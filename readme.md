<h1 align="center">Virtiso x86<br />
<div align="center">
<a href="https://github.com/qemus/virtiso-x86"><img src="https://github.com/qemus/virtiso-x86/raw/master/.github/logo.png" title="Logo" style="max-width:100%;" width="128" /></a>
</div>
<div align="center">
  
  [![Build](https://github.com/qemus/virtiso-x86/actions/workflows/build.yml/badge.svg)](https://github.com/qemus/virtiso-x86/)
  [![Version](https://img.shields.io/github/v/tag/qemus/virtiso-x86?label=version&sort=semver&color=066da5)](https://github.com/qemus/virtiso-x86/releases)
  [![Size](https://img.shields.io/badge/size-21.8_MB-steelblue?style=flat&color=066da5)](https://github.com/qemus/virtiso-x86/releases)
  
</div></h1>

Virtiso is a slim image of the KVM/QEMU Virtio drivers for 32-bit Windows guests.

The drivers are WHQL signed (unlike those in the [official ISO](https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/latest-virtio/)) and reduced from 600 MB to just 22 MB in size.

# Methods used

  - Stripped AMD64/ARM64 drivers
  - Stripped all .PDB (debug symbol) files
  - Stripped Guest Agent and Guest Tools

# Usage

  It contains every x86 driver the official image has, and even the .MSI installer, so there is zero loss of functionality.
  
  See also [Virtiso x64](https://github.com/qemus/virtiso/) if you need x64 drivers and [Virtiso ARM](https://github.com/qemus/virtiso-arm/) for  ARM64 drivers.

# Stars
[![Stars](https://starchart.cc/qemus/virtiso-x86.svg?variant=adaptive)](https://starchart.cc/qemus/virtiso-x86)

# Disclaimer

  This project contains binaries provided by Red Hat, Inc. and/or its affiliates.
