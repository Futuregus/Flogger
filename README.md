# floggerX

**Simple, reliable logging for your Python projects.**

---

## What’s floggerX?

floggerX is a lightweight Python logging module that writes actions to a file and can print logs to the console. It creates a logs directory if you need it and lets you customize where your logs live. Perfect for keeping track of what your app is up to, without the hassle.

---

## Features

- Logs actions with timestamps
- Optional console printing for real-time updates
- Easy configuration of log directory and filename
- Auto-creates log folder and file if missing
- Clean, minimal dependency (just Python standard libs)

---

## How to install

```bash
pip install floggerX==1.0.0
````



---

## Quickstart

```python
from floggerX import Logger

# Set where your logs go
Logger.configure(data_dir="my_logs", log_file="app.log")

# Log without a tag
Logger.log_action("Started the app")

# Log with no tag and no timestamp (separator)
Logger.log_action("----- New Session -----", separator=True)

# Log with a tag
Logger.log_action("An important event", tag="INFO")
```

---

## Why use floggerX?

Because you deserve a logging tool that just works without drowning you in config headaches. It’s straightforward.

---

## License

MIT License

---

## Questions or ideas?

just reach out with a issue.
