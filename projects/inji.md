# Project Name
Inji - Means knowing or recognizance in [Korean](https://en.wikipedia.org/wiki/Korean_language)

# Project Description
This library contains the implementation for the Digital Wallet with credential download, view, share and perform authorization . Its written in React Native.

# Alignment with the OpenWallet Foundation Mission
This library has the implementation for a digital wallet to download, store, view, share the verifiable credentials and perform authorization with it. It helps the resident to use the credential when in need at crucial situation and avail the service requested. it is written in react native to be usable in both android and ios covering wide range user and be inclusive and it can be used widely.

# Current Code of Conduct
[Code of Conduct](https://docs.mosip.io/1.2.0/community/code-of-conduct)

We will also follow the LF Code of Conduct

# TAC Sponsor
No one Now

# Project License
Currently the project is hosted with  MIT license. We will move to Apache license 2.0 upon approval of the project.

# Source Control
[Repository](https://github.com/mosip/inji)

# Issue Tracker
[Jira](https://mosip.atlassian.net/jira/software/c/projects/INJIMOB/boards/91)

# External Dependencies
```
    implementation("com.facebook.react:react-android")
    implementation 'com.facebook.soloader:soloader:0.10.1+'
    implementation 'com.facebook.fresco:fresco:2.0.0'
    implementation 'com.facebook.fresco:imagepipeline-okhttp3:2.0.0'
    implementation 'com.squareup.okhttp3:okhttp-urlconnection:4.4.1'
    implementation 'com.facebook.fresco:animated-gif:2.0.0'
    implementation 'com.facebook.fresco:webpsupport:2.0.0'
    implementation 'com.facebook.fresco:animated-webp:2.0.0'   
    implementation "androidx.swiperefreshlayout:swiperefreshlayout:1.0.0"
    debugImplementation("com.facebook.flipper:flipper:${FLIPPER_VERSION}")
    debugImplementation("com.facebook.flipper:flipper-network-plugin:${FLIPPER_VERSION}") {
        exclude group:'com.facebook.flipper'
        exclude group:'com.squareup.okhttp3', module:'okhttp'
    }
    debugImplementation("com.facebook.flipper:flipper-fresco-plugin:${FLIPPER_VERSION}") {
        exclude group:'com.facebook.flipper'
    }
    implementation("com.facebook.react:hermes-android")
    implementation jscFlavor
    implementation 'com.jakewharton.timber:timber:4.7.1'
```
npm dependencies

```
    "@digitalbazaar/ed25519-signature-2018": "digitalbazaar/ed25519-signature-2018",
    "@digitalbazaar/ed25519-verification-key-2018": "digitalbazaar/ed25519-verification-key-2018",
    "@digitalbazaar/rsa-signature-2018": "digitalbazaar/rsa-signature-2018#initial",
    "@digitalbazaar/rsa-verification-key-2018": "digitalbazaar/rsa-verification-key-2018#initial",
    "@digitalcredentials/vc": "^1.1.2",
    "@expo-google-fonts/inter": "^0.2.3",
    "@expo-google-fonts/poppins": "^0.2.0",
    "@expo/metro-config": "~0.10.0",
    "@react-native-clipboard/clipboard": "^1.10.0",
    "@react-native-community/netinfo": "9.3.7",
    "@react-native-picker/picker": "2.4.8",
    "@react-navigation/bottom-tabs": "^6.0.7",
    "@react-navigation/native": "^6.0.8",
    "@react-navigation/native-stack": "^6.1.0",
    "@xstate/react": "^3.0.1",
    "base64url-universal": "^1.1.0",
    "buffer": "^6.0.3",
    "crypto-js": "^3.3.0",
    "date-fns": "^2.26.0",
    "expo": "~48.0.18",
    "expo-app-loading": "~1.3.0",
    "expo-barcode-scanner": "~12.3.2",
    "expo-camera": "~13.2.1",
    "expo-constants": "~14.2.1",
    "expo-font": "~11.1.1",
    "expo-local-authentication": "~13.3.0",
    "expo-localization": "~14.1.1",
    "expo-splash-screen": "~0.18.2",
    "expo-status-bar": "~1.4.4",
    "expo-updates": "~0.16.4",
    "i18next": "^21.6.16",
    "iso-639-3": "^3.0.1",
    "jwt-decode": "^3.1.2",
    "node-forge": "^1.3.1",
    "node-jose": "^2.2.0",
    "patch-package": "^6.5.1",
    "postinstall-postinstall": "^2.1.0",
    "react": "18.2.0",
    "react-i18next": "^11.16.6",
    "react-native": "0.71.8",
    "react-native-app-auth": "^7.0.0",
    "react-native-app-intro-slider": "^4.0.4",
    "react-native-argon2": "^2.0.1",
    "react-native-biometrics-changed": "^1.1.8",
    "react-native-bluetooth-state-manager": "^1.3.2",
    "react-native-cli": "^2.0.1",
    "react-native-device-info": "^8.4.8",
    "react-native-dotenv": "^3.3.1",
    "react-native-elements": "3.4.3",
    "react-native-fs": "^2.18.0",
    "react-native-gesture-handler": "~2.9.0",
    "react-native-keychain": "^8.0.0",
    "react-native-linear-gradient": "^2.8.0",
    "react-native-localize": "^3.0.2",
    "react-native-location": "^2.5.0",
    "react-native-mmkv-storage": "^0.9.1",
    "react-native-permissions": "^3.8.0",
    "react-native-popable": "^0.4.3",
    "react-native-qrcode-svg": "^6.2.0",
    "react-native-restart": "^0.0.24",
    "react-native-rsa-native": "^2.0.5",
    "react-native-safe-area-context": "4.5.0",
    "react-native-screens": "~3.20.0",
    "react-native-secure-key-store": "^2.0.10",
    "react-native-secure-keystore": "github:mosip/secure-keystore#v0.1.1",
    "react-native-securerandom": "^1.0.1",
    "react-native-simple-markdown": "^1.1.0",
    "react-native-spinkit": "^1.5.1",
    "react-native-svg": "13.4.0",
    "react-native-swipe-gestures": "^1.0.5",
    "react-native-tuvali": "github:mosip/tuvali#v0.4.6",
    "react-native-vector-icons": "^10.0.0",
    "short-unique-id": "^4.4.4",
    "simple-pem2jwk": "^0.2.4",
    "telemetry-sdk": "git://github.com/mosip/sunbird-telemetry-sdk.git#f762be5732ee552c0c70bdd540aa4e2701554c71",
    "xstate": "^4.35.0"
```

# Release Methodology
[Releases](https://github.com/mosip/inji/releases)

# Initial Maintainers
[Maintainers](https://github.com/mosip/inji/blob/main/MAINTAINERS.md)

# Proposed Project Governance
[Governance Under MOSIP](https://www.mosip.io/governance.php)

# Links to Documented Governance Practices
--

# Preferred Maturity Level
Growth

# Communication Channels
We use Slack & Discourse
[Slack](HTTP://mosip-team.slack.com)
[Community](https://community.mosip.io/)

# Project Website
[Documentation](https://docs.mosip.io/inji/)

# Social Media
[MOSIP](https://www.linkedin.com/company/mosip-project/?originalSubdomain=in)

# Financial Sponsorship
[MOSIP](https://www.mosip.io/)

# Infrastructure
_Include any infrastructure needs or requests._
