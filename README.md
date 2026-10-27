# Mobile Link — Android starter

This is a **starter project**, not a finished screen-mirroring app.

## What this starter does
- Provides a simple Android screen.
- Requests Android's official screen-capture consent through MediaProjection.
- Starts a foreground service after the user grants permission.

## What it does NOT do yet
- It does not stream video to another phone.
- It does not implement pairing, WebRTC signaling, authentication, or file transfer.
- It cannot bypass Android's system consent prompt. Android may require consent again for a new capture session.
- It has not been built or tested in this environment.

## Build requirements
You need Android Studio or a compatible Android build environment. A phone-only workflow can be difficult; this source ZIP itself is not an APK.

## Next implementation steps
1. Build and test the consent/foreground-service flow.
2. Add WebRTC video transport and authenticated signaling.
3. Add a secure pairing flow.
4. Test on both phones and on mobile-data/Wi-Fi networks.
5. Consider a TURN relay only if direct peer-to-peer connections fail; reliable relay hosting may not be free.

Use only on phones you own or have explicit permission to monitor.
