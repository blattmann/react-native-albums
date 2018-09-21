# react-native-albums

> The current React Native CLI requires node >= v8.3.0

## Gettimg started

Check your default node version

```
$ node -v
```

If your default node version is < v8.3.0 you need to update node or use
[nvm](http://dev.topheman.com/install-nvm-with-homebrew-to-use-multiple-versions-of-node-and-iojs-easily/) _(recommended)_

If you use nvm you need to set your default node version to v8.3.0 or later.

```
# Install the version that you would like
$ nvm install 8.3.0

# Set 8.3.0 (or another version) as default
$ nvm alias default 8.3.0
```

If you are using nvm you can - of course - always switch back to your old node version if needed for whatever project!

_Hint_: After you did set the default node version make sure to restart your terminal :)

When you are set you can install React Native CLI globally and it will use the default node version, in this example v8.3.0:

```
$ npm i -g react-native-cli
```

If you are on a Mac and want to build for iOS you probably need to sign the license agreement for Xcode. You can do this also via terminal:

```
$ sudo xcodebuild -license
```

### Build for iOS

```
$ react-native run-ios
```
