# flavorTest

Test project to set up flavors in React Native 0.57.2.

Based on [this article](https://medium.com/@ywongcode/building-multiple-versions-of-a-react-native-app-4361252ddde5).

Fresh init project, only 2 modifications:
- add product flavors in `app/build.gradle`
- add flavor specific resources in `android/app/src/main/<flavorName>`

Check above mentioned article for details.
If you get `code:500` with a `react-native-hmr` error on run try doing [this](https://github.com/facebook/react-native/issues/21490#issuecomment-427240356). (It is a known bug with RN 0.57.2)
