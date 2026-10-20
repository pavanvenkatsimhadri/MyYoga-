# MyYoga starter project

This is an original responsive website starter for MyYoga. It can be tested locally and hosted as a website. With HTTPS hosting, the manifest/service worker provide the foundation for an installable Progressive Web App (PWA).

## Run it
1. Unzip this folder.
2. Open `index.html` in a browser to preview the basic app. Some PWA features require hosting over HTTPS.
3. To share it as a website, upload the project files to a static host that supports HTTPS.
4. To install as an app, open the hosted site in a compatible mobile browser and use its browser menu's install/add-to-home-screen option.

## Included now
- Responsive MyYoga home screen
- Daily beginner plan and yoga routine cards
- Local practice session and minutes tracker
- Local demo display-name profile

## Not implemented yet
- Real secure accounts / password handling
- Streaming video library
- AI posture detection
- Smart yoga mat Bluetooth/API connection
- Cloud sync between devices

Do not enter a real password in this demo. Progress and the demo display name are stored only in this browser on this device. For real accounts/cloud sync, choose and configure an authentication/database service and publish a privacy policy. AI posture guidance requires a pose model and careful pose-specific validation; it should not be presented as medical advice. Smart-mat connectivity depends on the exact mat hardware and protocol.

## Suggested next steps
1. Replace the demo routines with yoga content you own or have permission to use.
2. Add a video player and licensed/owned video URLs.
3. Configure real authentication and cloud storage.
4. Add browser pose detection using Google's MediaPipe Pose Landmarker as a separate tested module.
5. Identify the exact smart mat model and its Bluetooth/API documentation before implementing connectivity.
6. Test accessibility, privacy, security, and device compatibility before public release.
