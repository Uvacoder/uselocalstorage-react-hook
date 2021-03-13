# uselocalstorage-react-hook

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

- [https://codesandbox.io/s/uselocalstorage-react-hook-85h9r](https://codesandbox.io/s/uselocalstorage-react-hook-85h9r)

[![](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/uselocalstorage-react-hook-85h9r)

## 🛡️ License

[MIT](LICENSE)
