# React Native

<a href='https://reactnative.dev/'>Officical website</a>

---

- [What is React Native?](#1)
- [Two ways of styling](#2)
- [Debugging](#3)

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

React Native provides an in-app developer menu which offers several debugging options.

>

> React Developer Tools

```
sudo npm install -g react-devtools
react-devtools
```

![](4.png)

<a href='https://reactnative.dev/docs/debugging#accessing-the-in-app-developer-menu'>Debugging on the official website</a>
