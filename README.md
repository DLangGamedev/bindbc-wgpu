[![DUB Package](https://img.shields.io/dub/v/bindbc-wgpu.svg)](https://code.dlang.org/packages/bindbc-wgpu)

# bindbc-wgpu
Dynamic binding to [gfx-rs/wgpu-native](https://github.com/gfx-rs/wgpu-native) based on [BindBC](https://github.com/BindBC/bindbc-loader) library loader. Supports Windows, Linux and macOS.

> WebGPU specification is currently a Candidate Recommendation Draft and not a W3C standard yet. API may change and break backward compatibility; use at your own risk. This binding may be not up to date with latest API revisions.

Usage:
```
"dependencies": {
    "bindbc-wgpu": "0.25.0"
}
```

This repository also includes a simple triangle drawing example. More advanced demo can be found [here](https://github.com/gecko0307/wgpu-dlang).

## What is WebGPU?
It is a new low-level graphics and compute API for the Web that works on top of Vulkan, DirectX 12, or Metal. It exposes the generic computational facilities available in today's GPUs in a cross-platform way. 

[wgpu](https://github.com/gfx-rs/wgpu) is a native WebGPU implementation written in Rust that can be compiled to a shared library to use with any language. Its API is based on the [W3C spec](https://www.w3.org/TR/webgpu/). It serves as the core of the WebGPU integration in Firefox, Servo, and Deno.

Some useful links:
* [WebGPU specification](https://www.w3.org/TR/webgpu/)
* [WebGPU Shading Language specification](https://www.w3.org/TR/WGSL/)
* [wgpu documentation](https://docs.rs/wgpu/24.0.3/wgpu/index.html)
