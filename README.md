# C4D Guide

A simple multilingual documentation site built with MkDocs and Material for MkDocs.

## 🌍 Languages

- **Español** (Default) - [/es/](./docs/es/)
- **English** - [/en/](./docs/en/)
- **Português** - [/pt/](./docs/pt/)

## 🚀 Features

- ✨ Modern Material Design interface
- 🌍 Full multilingual support with language switcher
- 📱 Responsive design for all devices
- 🔍 Integrated search functionality
- 🌙 Dark/light mode toggle
- 🚀 Auto-deployment to GitHub Pages

## 🛠️ Local Development

### Prerequisites

- Python 3.7+
- pip

### Setup

1. Clone the repository:
```bash
git clone https://github.com/lasr21/c4d_guide.git
cd c4d_guide
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Serve locally:
```bash
mkdocs serve
```

4. Open your browser and navigate to `http://127.0.0.1:8000`

### Building

To build the static site:
```bash
mkdocs build
```

The built site will be in the `site/` directory.

## 📁 Project Structure

```
docs/
├── es/index.md  # Spanish (default)
├── en/index.md  # English
└── pt/index.md  # Portuguese
```

## 🚀 Deployment

This project is configured to automatically deploy to GitHub Pages when you push to the `main` branch. The GitHub Actions workflow will:

1. Install dependencies
2. Build the MkDocs site
3. Deploy to GitHub Pages

Make sure to enable GitHub Pages in your repository settings and set the source to "GitHub Actions".

## 📝 Adding Content

To add content to the documentation:

1. Edit the respective `index.md` files in `docs/es/`, `docs/en/`, and `docs/pt/`
2. Keep the content synchronized across languages
3. Commit and push your changes

## 🔧 Configuration

The main configuration is in `mkdocs.yml`. Key features:

- **Theme**: Material for MkDocs with custom color scheme
- **Plugins**: Search and i18n for multilingual support
- **Languages**: Spanish (default), English, Portuguese
- **Navigation**: Simple single-page structure

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

---

Built with ❤️ using [MkDocs](https://www.mkdocs.org/) and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
