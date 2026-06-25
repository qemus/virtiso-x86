<h1 align="center">VirtISO x86<br />
<div align="center">
<a href="https://github.com/qemus/virtiso-x86"><img src="https://github.com/qemus/virtiso-x86/raw/master/.github/logo.png" title="Logo" style="max-width:100%;" width="128" /></a>
</div>
<div align="center">
  
  [![Build](https://github.com/qemus/virtiso-x86/actions/workflows/build.yml/badge.svg)](https://github.com/qemus/virtiso-x86/)
  [![Version](https://img.shields.io/github/v/release/qemus/virtiso-x86?label=version&sort=date&display_name=release&color=066da5)](https://github.com/qemus/virtiso-x86/releases)
  [![Size](https://img.shields.io/badge/size-18.0_MB-steelblue?style=flat&color=066da5)](https://github.com/qemus/virtiso-x86/releases)
  
</div></h1>

VirtISO is a slim image of the VirtIO drivers for 32-bit Windows guests as provided by Fedora.

It minimizes the [official ISO](https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/latest-virtio/) from 700 MB to just 18 MB in size.

# Features ✨

  - Stripped all AMD64/ARM64 drivers
  - Stripped all .PDB (debug symbol) files
  - Stripped Guest Agent and Guest Tools

# Download

  You can download the [latest version](https://github.com/qemus/virtiso-x86/releases/download/v0.1.285-1/virtio-win-0.1.285.iso) from the [Releases](https://github.com/qemus/virtiso-x86/releases) page.

# Usage 🚀

  It contains every x86 driver the official image has, and even the .MSI installer, so there is zero loss of functionality.
  
> [!TIP]
> See also [VirtISO x64](https://github.com/qemus/virtiso/) for the x64 drivers, [VirtISO WHQL](https://github.com/qemus/virtiso-whql/) for WHQL certified drivers, and [VirtISO ARM](https://github.com/qemus/virtiso-arm/) for ARM64 drivers.

## Stars 🌟
[![Stargazers](https://raw.githubusercontent.com/star-stats/stars/refs/heads/data/charts/qemus-virtiso-x86.svg)](https://github.com/dobtc/qemus/virtiso-x86)

# Disclaimer ⚖️

  *This project contains binaries provided by Red Hat, Inc. and/or its affiliates.*
