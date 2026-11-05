DJI Simulator iOS project

BUILD AN UNSIGNED IPA ON GITHUB (NO MAC REQUIRED LOCALLY)
1. Create a GitHub repository. Keep it private if you do not want the source code to be public.
2. Upload the contents of this folder to the repository.
3. Open the repository's Actions tab, select "Build unsigned iOS IPA", and choose "Run workflow".
4. When the run finishes, download the "DJI-Simulator-unsigned-IPA" artifact from its summary page.

GitHub provides hosted macOS runners. Standard runners are free for public repositories; private repositories use included GitHub Actions compute and can incur charges if that allowance is exceeded.

The generated IPA is unsigned. It is useful as a build artifact, but iOS will not install it directly until it is signed. Installing on a personal iPhone requires signing and provisioning; App Store distribution requires Apple Developer Program membership.

The HTML and Three.js library are included locally, so the app does not need the CDN at runtime. The project targets iOS 15.0 and later.
