# React Native Legacy Custom Components

This is a module for legacy "CustomComponents" to gracefully deprecate.

## Navigator

The navigator component in this module will behave identically as the one in old version of React native, with one exception:

Latest documentation is available here: https://facebook.github.io/react-native/docs/0.43/navigator.html


### Breaking Changes from react-native

- Navigator.props.sceneStyle must be a plain object, not a stylesheet!

(this breaking change is needed to avoid calling React Native's private APIs)
