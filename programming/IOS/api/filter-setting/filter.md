---
layout: default-layout
title: Dynamsoft Camera Enhancer - Objective-C & Swift API references
description: This is the documentation - Objective-C & Swift API references page of Dynamsoft Camera Enhancer.
keywords:  Camera Enhancer, Objective-C & Swift API references
needAutoGenerateSidebar: true
breadcrumbText: Java
---

# Dynamsoft Camera Enhancer - Objective-C & Swift API references

## Filter Setting

- [`enableSensorControl`](#enableSensorControl)
- [`enableFrameFilter`](#enableFrameFilter)
- [`setMaxFrameRate`](#setMaxFrameRate)
- [`setFrameListLength`](#setFrameListLength)

### enableSensorControl
    
Turn on(off) sensor control

Objective-C
```objectivec
    [dce enableSensorControl:50];
```

Swift
```Swift
    dce.enableSensorControl(50);
```

### enableFrameFilter

Turn on(off) DCE filter (recommended to be true).

Objective-C
```objectivec
    [dce enableFrameFilter:true];
```

Swift
```Swift
    dce.enableFrameFilter(true);
```

### setMaxFrameRate

Set max frame rate.

Objective-C
```objectivec
    [dce setMaxFrameRate:24];
```

Swift
```Swift
    dce.setMaxFrameRate(24);
```

### setFrameListLength

Filtered frame will be stored in a list for decoding process. Decoder will always get the newest frame for decoding. The default length of frame list will be 10 if you don't make any setting on it.

Objective-C
```objectivec
    [dce setFrameListLength:8];
```

Swift
```Swift
    dce.setFrameListLength(8);
```