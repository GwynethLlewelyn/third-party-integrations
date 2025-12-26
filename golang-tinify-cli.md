---
collection: "Development"
title: "tinify-go"
platform: "Golang"
type: "CLI"
developer: "GwynethLlewelyn"
developer_url: "https://gwynethllewelyn.net"
price: "Free"
url: "https://github.com/GwynethLlewelyn/tinify-go"
---

CLI tool written in Go, using a fork of the [Go library implementing the Tinify API](https://github.com/gwpp/tinify-go)
by [@gwpp](https://github.com/gwpp) who last updated it in June 2017 and still featured [on the third-party integration list](./golang.md).

This tool should compile on anything that can run Go 1.24+. Testing was done mostly on macOS and Debian/Ubuntu Linux
(both under x86_64 and ARM64 architectures). The CLI itself uses the [urfave/cli](https://github.com/urfave/cli) framework.

Given the Tinify API key in the environment, it implements the API as detailed on the official page, with all known commands and parameters, even accepting the [HEIF](https://en.wikipedia.org/wiki/High_Efficiency_Image_File_Format) format for input files.
