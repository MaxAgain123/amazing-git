# amazing-git

A simple project with Python scripts and a basic HTML page.

## Project Structure

```
amazing-git/
├── index.html      # Basic HTML page template
├── nuevo.py        # Python placeholder file
├── prueba.py       # Python greeting example
└── prueba02.py     # Python farewell example
```

## Getting Started on Your Local PC

### Prerequisites

- [Git](https://git-scm.com/) installed on your machine
- [Python 3](https://www.python.org/) installed for running the Python scripts
- Any web browser for opening the HTML file

### Clone the Repository

```bash
git clone <repository-url>
cd amazing-git
```

### Running the Python Scripts

```bash
# Run the greeting script
python prueba.py

# Run the farewell script
python prueba02.py
```

### Opening the HTML Page

Open `index.html` directly in your web browser, or serve it locally:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Working with Git

Once you have the project on your PC, you can:

- **See changes**: `git status` and `git diff`
- **Create a new branch**: `git checkout -b my-feature`
- **Stage changes**: `git add .`
- **Commit changes**: `git commit -m "Your message"`
- **Push to GitHub**: `git push origin my-feature`

