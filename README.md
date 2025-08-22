# 🛡️ NetGuardJS

**NetGuard** is an open-source project dedicated to protecting apps, bots, and communities from **phishing, scams, and malicious links**.  
Our goal is to make security simple, accessible, and effective for developers everywhere.  

---

## ✨ Features

- 🚫 **Block known scam & phishing domains**  
- 🔄 **Auto-updating blocklist** (optional)  
- ⚡ **Lightweight & fast** for bots, apps, and web projects  
- 🛠️ **Easy integration** with JavaScript, Discord bots, and web apps  
- 📖 **Fully open-source** under a dual license (MIT or GPLv3)  

---

## 📦 Installation

Coming soon – package will be available on **npm**:  

```bash
npm install netguardjs
````

---

## 🚀 Usage Example

```js
import { isMalicious } from "NetGuardJS";

const url = "http://example-scam.com";

if (isMalicious(url)) {
  console.log("⚠️ Blocked: Malicious link detected!");
} else {
  console.log("✅ Safe link");
}
```

---

## 📚 Projects

* **NetGuardJS** – Core phishing & scam link detection library
* *(more coming soon!)*

---

## 🤝 Contributing

We welcome contributions of all kinds — bug reports, code improvements, or new scam domain submissions.
See our [Contributing Guide](CONTRIBUTING.md) for details.

---

## 📜 License

This project is dual-licensed under:

* [MIT License](LICENSE.md#mit-license)
* [GNU GPL v3](LICENSE.md#gnu-general-public-license-v30)

You may choose which license best fits your needs.

---

## 🌐 Community

* GitHub Issues – Report bugs or request features
* Discussions – Coming soon
* Website – Coming soon
* Discord – Coming soon

---

🔒 **NetGuard: Open-source security for everyone.**
