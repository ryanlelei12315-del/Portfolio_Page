# CreatiSphere Install Guide

## Node.js
1. Download LTS from https://nodejs.org/en/download/prebuilt-installer/current
2. Run installer (includes npm)
3. Restart terminal

## Flutter
1. Download ZIP: https://storage.googleapis.com/flutter_infra_release/releases/stable/windows/flutter_windows_3.24.3-stable.zip
2. Extract to `C:\flutter`
3. Add `C:\flutter\bin` to PATH:
   - Win+R > sysdm.cpl > Advanced > Environment Variables > Path > Edit > New > OK
4. Restart PowerShell/VSCode

## Verify
```
node --version
npm --version
flutter doctor
```

## Firebase
```
npm i -g firebase-tools
firebase login
firebase projects:create creatisphere
```

## Next
Share `flutter doctor` output. Full code incoming.

OpenAI key from platform.openai.com/api-keys

