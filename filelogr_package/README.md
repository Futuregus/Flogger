# 📂filelogr

**Simple, reliable logging for your Python projects.**

---

## 💡 What’s filelogr?

`filelogr` is a lightweight Python logging module that writes actions to a file and optionally prints them to the console. It auto-creates a logs folder if needed, and lets you customize where your logs are stored.

Perfect for tracking your app's activity without the hassle.

---

## ✨ Features

- 🕒 Logs actions with timestamps
- 🖥️ Optional real-time console output
- 📁 Customizable log folder and filename
- 🛠️ Auto-creates log directory and file
- ⚡ Built with Python’s standard libraries only (zero dependencies)

---

## 📦 Installation

```bash
pip install filelogr
````

---

## 🚀 Quickstart

```python
from filelogr import Logger

# Configure your log directory and filename
Logger.configure(data_dir="my_logs", log_file="app.log")

# Log without a tag
Logger.log_action("Started the app")

# Log with no tag and no timestamp (just a separator)
Logger.log_action("----- New Session -----", separator=True)

# Log with a tag
Logger.log_action("An important event", tag="INFO")
```

---

## ❓ Why use filelogr?

Because logging shouldn't feel like setting up a rocket launch. `filelogr` gives you just what you need: a simple and readable way to track what’s going on in your app.

---

## 📄 License

[MIT License](https://github.com/Futuregus/filelogr/blob/main/LICENSE)

---

## 💬 Questions or ideas?

Open an issue or suggest a feature here:
👉 [GitHub: Futuregus/filelogr/issues](https://github.com/Futuregus/filelogr/issues)

