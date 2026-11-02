<p align="center">
  <img src="https://raw.githubusercontent.com/appy-to/.github/main/profile/assets/appy-banner.svg" alt="Appy — From the first click to the right app experience" width="100%" />
</p>

<p align="center">
  <a href="https://appy.to">Website</a> ·
  <a href="https://appy.to/docs">Documentation</a> ·
  <a href="https://appy.to/docs/sdk">SDKs</a> ·
  <a href="mailto:support@appy.to">Contact</a>
</p>

Appy helps app teams connect campaign links to app experiences and measure the installs, events and revenue that follow.

Use smart links, dynamic QR codes and branded domains across creator campaigns, email, SMS and the web. Send people to the right app store or website, open the right screen when the app is installed, and preserve link context through installation where supported.

### Build with Appy

The SDK is a library for **your own app**; your app keeps its name and identifiers. Start in the Appy dashboard under **Apps & SDK → New app**, then copy **Publishable key** and **Link domain** from **SDK setup**. No terminal registration command is needed. [Which example values do I replace?](https://github.com/appy-to/appy-ios-sdk/blob/main/SETUP.md)

| Platform | SDK | Start here |
| --- | --- | --- |
| iOS · Swift | [AppySDK](https://github.com/appy-to/appy-ios-sdk) | [Quickstart](https://github.com/appy-to/appy-ios-sdk/blob/main/QUICKSTART.md) |
| Android · Kotlin / Java | [to.appy:appy-sdk](https://github.com/appy-to/appy-android-sdk) | [Quickstart](https://github.com/appy-to/appy-android-sdk/blob/main/QUICKSTART.md) |
| Flutter · Dart | [appy_sdk](https://github.com/appy-to/appy-flutter) | [Quickstart](https://github.com/appy-to/appy-flutter/blob/main/QUICKSTART.md) |
| React Native · Expo | [react-native-appy](https://github.com/appy-to/react-native-appy) | [Quickstart](https://github.com/appy-to/react-native-appy/blob/main/QUICKSTART.md) |
| Other runtimes | HTTP endpoints | [Use the API](https://appy.to/docs/sdk/http) |

The iOS SDK installs directly from GitHub. Maven Central, pub.dev and npm distribution is being prepared; the other guides explain current onboarding and source setup. Appy SDK endpoints currently require an Enterprise plan. SDK source licensing and access to the hosted service are separate.

### Follow the journey

**Campaign or QR → Smart link → App or store → Install → In-app event → Revenue**

- **Deep linking:** Universal Links and Android App Links that carry your campaign context into the app.
- **Deferred deep linking:** recover the link after installation when a supported match is available.
- **Install attribution:** understand which Appy links and supported attribution sources brought installs.
- **Events and revenue:** connect in-app activity to acquisition campaigns, with server-side events for backend workflows.
- **Developer tools:** native SDKs, Flutter and React Native wrappers, REST API and an MCP server.

### Small clients, clear controls

The native SDKs handle link delivery, install attribution and queued events. Tracking controls and platform data-disclosure guidance are documented for each integration. Configure consent and data collection for your app's requirements.

Explore [Appy.to](https://appy.to) or read the [developer documentation](https://appy.to/docs).
