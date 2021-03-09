# NativeBase HelloWorld App

This demo app is based on [NativeBase](https://nativebase.io/).

## Setup
Create project:
```
expo init native-base-demo
cd native-base-demo
expo install expo-font
yarn add native-base --save
expo install expo-app-loading
```
Copy `App.js` code from https://docs.nativebase.io/docs/GetStarted.html to
your `App.js` and run your app with `expo start`.

## Explore
You can try the various [NativeBase components](https://docs.nativebase.io/Components.html#Components) (building block) by copying them
to this project and rendering them in `App.js`.

For example, you can create `components/AnatomyExample.js`
```
```
import `AnatomyExample` in `App.js`
```javascript
import AnatomyExample from './components/AnatomyExample';
```
and change `render` in `App.js` to
```javascript
render() {
  if (!this.state.isReady) {
    return <AppLoading />;
  }

  return (
    <Container>
      <AnatomyExample />
    </Container>
  );
}
```
