sudo apt install nodejs npm
npm install
npm install expo
npm install expo-cli
npm run predeploy

=== After any update:
npm run deploy
(cd web-build && python3 -m http.server)

