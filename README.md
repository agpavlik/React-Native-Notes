# React Native

<a href='https://reactnative.dev/'>Officical website</a>

---

- [What is React Native?](#1)
- [Two ways of styling](#2)
- [Debugging](#3)
- [Core Components](#4)

---

### 📒 What is React Native? <a name="1"></a>

![](1.png)

There are two ways to creat app.

![](2.png)

---

### 📒 Two ways of styling <a name="2"></a>

Styling language is inspired by CSS and close to CSS, but it's not exactly the same.

![](3.png)

```javascript
<View style={{ flexDirection: "row", height: 100, padding: 20 }}>
  <Text>Hello World!</Text>
</View>
```

Inline style (style prop) is not supported on all elements.

```javascript
<View style={styles.container}>
  <Text>Hello World!</Text>
</View>;

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: "#ddd",
    alignItems: "center",
    justifyContent: "center",
  },
});
```

Style sheet objects allows to clearly separate JSX code and it also makes styles reusable.

### 📒 Debugging <a name="3"></a>

React Native provides an in-app developer menu which offers several debugging options. One of the popular is React Developer Tools

```
sudo npm install -g react-devtools
react-devtools
```

![](4.png)

### 📒 Core Components <a name="4"></a>

🚩 [Udemy-RN-1](https://github.com/agpavlik/Udemy-RN-01). This example containes next components:

- <a href='https://reactnative.dev/docs/next/view'>View</a> - container (equivalent `<div>`)

- <a href='https://reactnative.dev/docs/next/text'>Text</a> - component for displaying text

- <a href='https://reactnative.dev/docs/next/textinput'>TextInput</a> - foundational component for inputting text into the app via a keyboard

- <a href='https://reactnative.dev/docs/next/image'>Image</a> - component for displaying different types of images

- <a href='https://reactnative.dev/docs/next/stylesheet'>StyleSheet</a> - abstraction similar to CSS StyleSheets

- <a href='https://reactnative.dev/docs/next/button'>Button</a> - basic button component that should render nicely on any platform.

- <a href='https://reactnative.dev/docs/next/modal'>Modal</a> - basic way to present content above an enclosing view.

- <a href='https://reactnative.dev/docs/next/pressable'>Pressable</a> - wrapper that can detect various stages of press interactions on any of its defined children.

- <a href='https://docs.expo.dev/versions/latest/sdk/status-bar/'>StatusBar</a> from 'expo-status-bar'. A library that provides the same interface as the React Native StatusBar API, but with slightly different defaults to work great in Expo environments.

🚩 [Guess-Number-Game](https://github.com/agpavlik/Guess-Number-Game). This example containes next components:
