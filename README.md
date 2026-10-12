# Homey dashboard releases

Signed flutter-pi bundles for the Homey wall dashboard, published by CI.
Panels fetch `channels` release assets (`beta.json`, `stable.json`) and the
bundle each one names, and install it only if its ed25519 signature checks out.
There is no source code here.
