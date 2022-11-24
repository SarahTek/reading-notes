# Reading

getting started with react native

1. Name three Core Components of React Native and describe what they do.

- `<view>` A container that supports layout with flexbox, style, some touch handling, and accessibility controls.
- `<Text>` Displays, styles, and nests strings of text and even handles touch events.
- `<Image>`  Displays different types of images.

2. What problem does React Native solve (why call it native)?

- React Native runs on React, a popular open source library for building user interfaces with JavaScript. To make the most of React Native, it helps to understand React itself.

3. What are the building blocks of a React Native app? How does that compare to a React app?

- view is the basic building block of UI: a small rectangular element on the screen which can be used to display text, images, or respond to user input.

expo

1. What solution does expo provide?

- Expo is a bundle of tools created around React Native to help you start an app very fast. It provides you with a list of tools that simplify the creation and testing of React Native app. It equips you with the components of the user interface and services.

2. Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the `managed` workflow.
3. What is the difference between React Native and Expo?

expo snack

1. Checkout this tool. What does snack allow you to do?

ejecting

1. What does “eject” mean within the context of Expo?

- The Expo Eject Step is necessary to eject your app to install any missing native dependencies. 

2. When should you not eject?

- All you need is to distribute your app in the iTunes Store or Google Play. Expo can build binaries for you in that case. If you eject, we can't automatically build for you any more.
- You require Expo's push notification services. After ejecting, since Expo no longer manages your push credentials, you'll need to manage your own push notification pipeline.
- You are uncomfortable writing native code. Ejected apps will require you to manage Xcode and Android Studio projects.
- You enjoy the painless React Native upgrades that come with Expo. After your app is ejected, breaking changes in React Native will affect your project differently, and you may need to figure them out for your particular situation.

3. Why might you choose to eject?

- You might want to eject your project from the respective Expo clients if your project needs a native module that Expo doesn't currently support. This happens especially if your app has very specific and uncommon native demands.
