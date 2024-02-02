<h1 align="center">Virtiso x86<br />
<div align="center">
<img src="https://github.com/qemus/virtiso-x86/raw/master/.github/logo.png" title="Logo" style="max-width:100%;" width="128" />
</div>
<div align="center">
  
  [![Build](https://github.com/qemus/virtiso-x86/actions/workflows/build.yml/badge.svg)](https://github.com/qemus/virtiso-x86/)
  [![Version](https://img.shields.io/github/v/tag/qemus/virtiso-x86?label=version&sort=semver&color=066da5)](https://github.com/qemus/virtiso-x86/releases)
  [![Size](https://img.shields.io/badge/size-21.8_MB-steelblue?style=flat&color=066da5)](https://github.com/qemus/virtiso-x86/releases)
  
</div></h1>

Virtiso is a slim image of the KVM/QEMU Virtio drivers for 32-bit Windows guests.

It minimizes the [official ISO](https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/latest-virtio/) of 600 MB to just 22 MB in size.

# Methods used

  - Stripped AMD64/ARM64 drivers
  - Stripped all .PDB (debug symbol) files
  - Stripped Guest Agent and Guest Tools

# Usage

  It contains every x86 driver the official image has, and even the .MSI installer, so there is zero loss of functionality.

# Disclaimer

  This project contains binaries provided by Red Hat, Inc. and/or its affiliates.
