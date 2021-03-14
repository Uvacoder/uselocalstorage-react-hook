[![NPM](https://img.shields.io/npm/v/uselocalstorage-react-hook.svg?style=flat-square)](https://www.npmjs.com/package/react-select)
![](https://img.shields.io/github/license/saviomartin/uselocalstorage-react-hook?style=flat-square)
[![](https://img.shields.io/npm/dw/uselocalstorage-react-hook?style=flat-square)](https://www.npmjs.com/package/react-select)

# Uselocalstorage-React-Hook

![](/assets/working.gif)

This is an amazing package that will help you add local storage variables easily in your react app.

## 🛠️ Installation

1. Install using npm

```bash
npm i uselocalstorage-react-hook
```

2. Add to your project

```js
import useLocalStorage from "uselocalstorage-react-hook";
```

3. Start using `uselocalstorage-react-hook`

```js
const [name, setName] = useLocalStorage("name", "John Doe");
```

## 💻 Example Code

```js
import React from "react";
import "./styles.css";
import useLocalStorage from "uselocalstorage-react-hook";

const App = () => {
  const [name, setName] = useLocalStorage("name", "John Doe");

  return (
    <div>
      <input
        type="text"
        value={name}
        onChange={(e) => setName(e.target.value)}
      />
      <h1>{name}</h1>
      <p>Refresh this page, the name remains the same. 🤟</p>
    </div>
  );
};

export default App;
```

## 🦄 Live Demo

- [https://codesandbox.io/s/uselocalstorage-react-hook-85h9r](https://codesandbox.io/s/uselocalstorage-react-hook-85h9r) (Begginner 📌)

[![](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/uselocalstorage-react-hook-85h9r)

- [https://codesandbox.io/s/uselocalstorage-react-hook-yy2nf](https://codesandbox.io/s/uselocalstorage-react-hook-yy2nf) (Intermediate 📌)

[![](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/uselocalstorage-react-hook-yy2nf)

- [https://codesandbox.io/s/uselocalstorage-react-hook-h12tq](https://codesandbox.io/s/uselocalstorage-react-hook-h12tq) (Advanced 📌)

[![](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/uselocalstorage-react-hook-h12tq)

## 🙌 Thanks

Thanks to everyone who contributed to the development of this project.

If you enjoyed, go follow me on [Twitter](https://twitter.com/saviomartin7) 💖

## 🛡️ License

[MIT](LICENSE) Licensed. Copyright (c) [Savio Martin](http://github.com/saviomartin/).
