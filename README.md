# ionic-react-whatsapp-clone


[![Downloads](https://img.shields.io/github/downloads/nguoianphu/ionic-react-whatsapp-clone/total.svg?style=flat)](https://GitHub.com/nguoianphu/ionic-react-whatsapp-clone/releases/) [![Latest release](https://img.shields.io/github/release/nguoianphu/ionic-react-whatsapp-clone.svg?style=flat)](https://GitHub.com/nguoianphu/ionic-react-whatsapp-clone/releases/) [![Site](https://github.com/nguoianphu/ionic-react-whatsapp-clone/actions/workflows/build.yml/badge.svg)](https://github.com/nguoianphu/ionic-react-whatsapp-clone/actions/workflows/build.yml) [![CodeQL](https://github.com/nguoianphu/ionic-react-whatsapp-clone/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/nguoianphu/ionic-react-whatsapp-clone/actions/workflows/codeql-analysis.yml) [![Publish (Electron)](<https://github.com/nguoianphu/ionic-react-whatsapp-clone/actions/workflows/Publish%20(Electron).yml/badge.svg?branch=main>)](<https://github.com/nguoianphu/ionic-react-whatsapp-clone/actions/workflows/Publish%20(Electron).yml>) [![Publish (Capacitor - Android)](<https://github.com/nguoianphu/ionic-react-whatsapp-clone/actions/workflows/Publish%20(Capacitor%20-%20Android).yml/badge.svg>)](<https://github.com/nguoianphu/ionic-react-whatsapp-clone/actions/workflows/Publish%20(Capacitor%20-%20Android).yml>) [![CodeFactor](https://www.codefactor.io/repository/github/nguoianphu/ionic-react-whatsapp-clone/badge)](https://www.codefactor.io/repository/github/nguoianphu/ionic-react-whatsapp-clone)

---

An example of a WhatsApp UI clone using Ionic React (Dark Mode, IOS only... for now)
<br />
If you'd like to support, you can <a className="link" href="https://www.buymeacoffee.com/ionicreacthub" target="_blank" rel="noopener">buy me a coffee</a> ☕️

![Ionic React WhatsApp UI Clone](https://repository-images.githubusercontent.com/377881498/918f0300-d3a7-11eb-8600-1063361aaeb7)

### Included in this Ionic React Template/UI
* Status, Settings, Starred Messages, Chats, View Chat, View Contacts, Calls pages
* Reply-To in chat message using Ionic Animations and gestures (both swipe and long press)
* Star messages and view them in starred from settings
* Notification badges (on chat list)
* Read Receipts of chats
* Notification counts
* Send message
* Camera functionality in chat to send photo (using CapacitorJS)
* Gallery functionality in chat to send image from gallery
* State management with Pullstate
* Custom animations
* SASS Modules & Ionic CSS utilities

### To run

```javascript
npm install
npm run build
ionic serve
```

Alternatively, you can add the iOS, Android platform and run natively.


```javascript
npm install
npm run build
npx cap add android
npx cap sync
cd android
./gradlew assembleDebug
./gradlew assemble
./gradlew bundleRelease
```

Run ```npx cap sync``` to update folder ```android``` whenever you make changes.

# Are you on Twitter? Lets connect [@93alan](https://twitter.com/93alan)
# Have you checked out Ionic React Hub yet? [Ionic React Hub](https://ionicreacthub.com)
