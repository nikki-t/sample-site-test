# Siddarth Achar - Academic Website

Personal academic website built with [MkDocs](https://www.mkdocs.org/) and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/), deployed to GitHub Pages.

## 🚀 Features

- Clean, modern design matching academic website standards
- Responsive layout that works on all devices
- Green-themed color scheme
- Custom avatar with coffee emoji badge
- Publications page with BibTeX citations
- Experience page with education and work history
- Automated deployment via GitHub Actions

## 📋 Prerequisites

- Python 3.x
- pip (Python package manager)

## 🛠️ Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/siddarthachar/siddarthachar.github.io.git
   cd siddarthachar.github.io
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Serve locally:
   ```bash
   mkdocs serve
   ```

   The site will be available at `http://127.0.0.1:8000`

## 📁 Project Structure

```
.
├── docs/                    # Documentation source files
│   ├── index.md           # Homepage
│   ├── publications.md    # Publications page
│   ├── experience.md      # Experience page
│   ├── assets/            # Images and media files
│   │   ├── avatar.jpg
│   │   └── stacked-peaks.svg
│   ├── publication/       # Publication BibTeX files
│   └── stylesheets/       # Custom CSS
│       └── extra.css
├── mkdocs.yml             # MkDocs configuration
├── requirements.txt       # Python dependencies
└── .github/
    └── workflows/
        └── deploy.yml     # GitHub Actions deployment
```

## 🏗️ Building

To build the site for production:

```bash
mkdocs build
```

The built site will be in the `site/` directory.

## 🚢 Deployment

The site is automatically deployed to GitHub Pages via GitHub Actions when changes are pushed to the `main` branch.

To deploy manually:

1. Build the site: `mkdocs build`
2. Push to GitHub: `git push origin main`
3. GitHub Actions will automatically build and deploy

## 🎨 Customization

### Changing Colors

Edit `mkdocs.yml` to change the color scheme:

```yaml
theme:
  palette:
    - scheme: default
      primary: green  # Change this to your preferred color
      accent: teal
```

### Adding Content

- Edit `docs/index.md` for the homepage
- Edit `docs/publications.md` for publications
- Edit `docs/experience.md` for experience/education
- Add images to `docs/assets/`

### Styling

Custom CSS is in `docs/stylesheets/extra.css`. Modify this file to change the appearance.

## 📝 License

See [LICENSE](LICENSE) file for details.

## 🔗 Links

- Live site: https://siddarthachar.github.io
- MkDocs documentation: https://www.mkdocs.org/
- Material for MkDocs: https://squidfunk.github.io/mkdocs-material/

## 👤 Author

**Siddarth Achar**
- Website: https://siddarthachar.github.io
- GitHub: [@siddarthachar](https://github.com/siddarthachar)

