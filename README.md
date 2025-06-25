# 🗂️ bd_fileorganizer

**bd_fileorganizer** is a simple yet powerful Python utility that helps you clean up cluttered folders by automatically moving files into categorized subfolders like `images/`, `documents/`, `archives/`, and more — all based on file extensions.

It’s perfect for tidying up your `Downloads`, `Desktop`, or project folders with just one command.

---

## 📦 Features

- 📁 Automatically sorts files into categories
- 🧠 Smart extension detection (`.jpg` → `images`, `.pdf` → `documents`, etc.)
- 🧪 Dry-run mode to preview changes
- 🐍 Easy-to-use Python API and CLI interface
- ✅ Beginner-friendly code and customizable

---

## 🚀 Installation

Install from source:

```bash
git clone https://github.com/bhuvan0808/bd-fileorganizer
cd bd-fileorganizer
pip install -e .
````

> 📌 Available on PyPI!
> [![PyPI version](https://pypi.org/project/fileorganizer/)](https://pypi.org/project/bd-fileorganizer/)

---

## 🖥️ CLI Usage

```bash
bd-fileorganizer /path/to/folder
```

**Dry-run (preview only):**

```bash
bd-fileorganizer /path/to/folder --dry
```

---

## 🐍 Python API

```python
from bd-fileorganizer import organize_folder

organize_folder("/Users/you/Downloads", dry_run=False)
```

---

## 🧪 Running Tests

```bash
pytest
```

---

## 🗃️ Folder Structure Example

**Before:**

```
Downloads/
├── photo.jpg
├── report.pdf
├── backup.zip
```

**After:**

```
Downloads/
├── images/
│   └── photo.jpg
├── documents/
│   └── report.pdf
├── archives/
│   └── backup.zip
```

---

## 🔧 Extension Mapping

| Category     | Extensions                      |
| ------------ | ------------------------------- |
| `images/`    | `.jpg`, `.jpeg`, `.png`, `.gif` |
| `documents/` | `.pdf`, `.docx`, `.txt`         |
| `archives/`  | `.zip`, `.tar`, `.gz`, `.rar`   |
| `videos/`    | `.mp4`, `.mov`, `.mkv`          |
| `audio/`     | `.mp3`, `.wav`                  |
| `others/`    | Everything else                 |

---

## 📄 License

Licensed under the [License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)

---

## 🤝 Contributing

Contributions, feature ideas, and bug reports are welcome!
Feel free to open an [issue](https://github.com/your-username/bd-fileorganizer/issues) or a [pull request](https://github.com/your-username/bd-fileorganizer/pulls).

---

## 👤 Author

**Your Name**
GitHub: [@Bhuvan](https://github.com/bhuvan0808)

---

> 🧹 Make your folders smarter, not messier — with `fileorganizer` 🗂️
