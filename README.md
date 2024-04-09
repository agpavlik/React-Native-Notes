# React Native

https://reactnative.dev/

---

- [What is React Native?](#1)
- [Two ways of styling](#2)

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
