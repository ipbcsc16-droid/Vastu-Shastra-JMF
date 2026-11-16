JMF Vastu Shastra V2 — GitHub Actions Android APK build

This ZIP includes the app source and a GitHub Actions workflow at:
.github/workflows/build-apk.yml

Phone-only build instructions:
1. Create a free GitHub account and a NEW repository named jmf-vastu-shastra. Set it to Private if preferred.
2. In the repository page, use Add file > Create new file.
3. Create .github/workflows/build-apk.yml and paste the complete content from the workflow file in this ZIP. Commit to main.
4. Upload the app files from this ZIP to the repository root: index.html, manifest.webmanifest, sw.js, capacitor.config.json, package.json, README-BN-EN.txt. (Do not upload the ZIP itself.)
5. If GitHub does not run the workflow automatically, open Actions > Build JMF Vastu Shastra APK > Run workflow.
6. Wait for the run to finish successfully (green tick).
7. Open the completed run and download the artifact named JMF-Vastu-Shastra-APK. Extract the downloaded artifact ZIP; it contains app-debug.apk.
8. Open app-debug.apk on the phone and install. If Android asks, allow installation from that browser/file manager.

NOTE: This creates a debug APK for personal testing. It is not a Play Store release APK. Keep your GitHub account private and do not share signing passwords or keys.
