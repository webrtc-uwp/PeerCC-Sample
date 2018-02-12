# PeerCC-Sample

## Prerequisites:
- Visual Studio 2017 (Community Edition is fine)
  - Windows SDK 10.0.16299
  - Visual Studio Tools for Unity
  - Visual Studio Tools for Universal Windows Apps

## PeerCC - XAML MediaElement video rendering
1. Clone the repository: git clone -b webrtc_merge_m62_unity https://github.com/webrtc-uwp/PeerCC-Sample.git
2. Open PeerCC-Sample\webrtc\windows\solutions\WebRtc.sln
3. Select build configuration (Release or Debug) and target platform (x86 or x64)
4. Build project PeerConnectionClient.WebRtc

## PeerCC - Unity video rendering
1. Install Unity Editor 2017.2.0f3 with Metro Support
   https://download.unity3d.com/download_unity/46dda1414e51/Windows64EditorInstaller/UnitySetup64-2017.2.0f3.exe
   http://download.unity3d.com/download_unity/46dda1414e51/TargetSupportInstaller/UnitySetup-Metro-Support-for-Editor-2017.2.0f3.exe
2. Clone the repository: git clone -b webrtc_merge_m62_unity https://github.com/webrtc-uwp/PeerCC-Sample.git
3. Open PeerCC-Sample\webrtc\windows\solutions\WebRtcUnity.sln
4. Select build configuration (Release or Debug) and target platform (x86 or x64)
5. Build project PeerConnectionClientUnity.WebRtc
