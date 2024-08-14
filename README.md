How to build modules [doc](https://github.com/reactwg/react-native-new-architecture/blob/main/docs/turbo-modules.md)

## Requirements
node >= 20

## Installation
Run:
`cd MyApp`
`yarn`

iOS:
`cd ios`
`bundle install`
`RCT_NEW_ARCH_ENABLED=1 bundle exec pod install`
`cd ..`
`yarn ios`

Android:
`cd android`
`./gradlew generateCodegenArtifactsFromSchema`
`cd ..`
`yarn android`
