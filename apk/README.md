# APK Distribution Folder

Place your built APK here as `neighbornet.apk`.

## How to update the app download

1. Build a release APK in Android Studio:
   `Build → Generate Signed Bundle / APK → APK → Release`

2. Rename the output file to `neighbornet.apk`

3. Replace this file:
   `NeighborNet/apk/neighbornet.apk`

The website's "Get App" and "Download NeighborNet APK" buttons
all point to `apk/neighbornet.apk` — so replacing the file here
is all you need to do to push an update.
