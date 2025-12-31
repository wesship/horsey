> [!NOTE]
> This project is a fork of [bevacqua/horsey](https://github.com/bevacqua/horsey). The original project and its contributors can be found there.

# Horsey

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![CI/CD Status](https://github.com/wesship/horsey/actions/workflows/ci.yml/badge.svg)](https://github.com/wesship/horsey/actions/workflows/ci.yml)

> Progressive and customizable autocomplete component. It's small, fast, and supports a wide range of browsers, including IE7+.

---

## ✨ Features

- **Lightweight and Focused**: No bloat, just the features you need.
- **Natural Keyboard Navigation**: Intuitive and user-friendly.
- **Fuzzy Searching**: Smart and flexible search capabilities.
- **Cross-Browser Support**: Works in all sane browsers and IE7+.

---

## 🚀 Getting Started

### Prerequisites

- None

### Installation

You can install `horsey` using npm or bower:

```bash
npm install horsey --save
```

```bash
bower install horsey --save
```

### Usage

```javascript
horsey(document.querySelector('#my-input'), {
  source: function (data, done) {
    done(null, [{
      list: ['one', 'two', 'three']
    }]);
  }
});
```

---

## 🛠️ Built With

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

## 🤝 Contributing

Contributions are welcome! Please see the [contributing guidelines](CONTRIBUTING.md) for more information.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
