---
-api-id: M:Windows.Graphics.Holographic.HolographicCameraRenderingParameters.SetFocusPoint(Windows.Perception.Spatial.SpatialCoordinateSystem,Windows.Foundation.Numerics.Vector3,Windows.Foundation.Numerics.Vector3)
-api-type: winrt method
---

<!-- Method syntax
public void SetFocusPoint(Windows.Perception.Spatial.SpatialCoordinateSystem coordinateSystem, Windows.Foundation.Numerics.Vector3 position, Windows.Foundation.Numerics.Vector3 normal)
-->

# Windows.Graphics.Holographic.HolographicCameraRenderingParameters.SetFocusPoint

## -description
Sets the stationary point in the holographic space that the user will focus on, as well as the normal for a focus plane through that point.

This is used to improve image quality at the focus point and along its focus plane.

You must set the focus point each frame, or it will reset to its default.

## -parameters
### -param coordinateSystem
The coordinate system of the position and normal vectors.

### -param position
The location of the focus point in the specified coordinate system.

### -param normal
The normal of the focus point in the specified coordinate system, if known. If there is no obvious normal, have it face the user.

## -remarks

## -examples

## -see-also
[SetFocusPoint(SpatialCoordinateSystem, Vector3)](holographiccamerarenderingparameters_setfocuspoint_184506220.md), [SetFocusPoint(SpatialCoordinateSystem, Vector3, Vector3, Vector3)](holographiccamerarenderingparameters_setfocuspoint_1040378076.md)