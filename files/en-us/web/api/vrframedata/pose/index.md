---
title: VRFrameData.pose
slug: Web/API/VRFrameData/pose
tags:
  - API
  - Deprecated
  - Property
  - Reference
  - VR
  - VRFrameData
  - Virtual Reality
  - WebVR
  - pose
browser-compat: api.VRFrameData.pose
---
{{APIRef("WebVR API")}}{{Deprecated_Header}}

The **`pose`** read-only property of the {{domxref("VRFrameData")}} interface returns the {{domxref("VRPose")}} of the {{domxref("VRDisplay")}} at the current {{domxref("VRFrameData.timestamp")}}.

> **Note:** This property was part of the old [WebVR API](https://immersive-web.github.io/webvr/spec/1.1/). It has been superseded by the [WebXR Device API](https://immersive-web.github.io/webxr/).


## Value

A {{domxref("VRPose")}} object.

## Examples

See [`VRDisplay.getFrameData()`](/en-US/docs/Web/API/VRDisplay/getFrameData#examples) for example code.

## Specifications

This property was part of the old [WebVR API](https://immersive-web.github.io/webvr/spec/1.1/) that has been superseded by the [WebXR Device API](https://immersive-web.github.io/webxr/). It is no longer on track to becoming a standard.

Until all browsers have implemented the new [WebXR APIs](/en-US/docs/Web/API/WebXR_Device_API/Fundamentals), it is recommended to rely on frameworks, like [A-Frame](https://aframe.io/), [Babylon.js](https://www.babylonjs.com/), or [Three.js](https://threejs.org/), or a [polyfill](https://github.com/immersive-web/webxr-polyfill), to develop WebXR applications that will work across all browsers [\[1\]](https://developer.oculus.com/documentation/oculus-browser/browser-vr-xr/).

## Browser compatibility

{{Compat}}

## See also

- [WebVR API homepage](/en-US/docs/Web/API/WebVR_API)
- <https://mixedreality.mozilla.org/> — demos, downloads, and other resources from the Mozilla VR team.
