# Contributing to Mason Organizer

Thank you for your interest in contributing to Mason Organizer.

Mason Organizer is an early-stage TripZero Labs project focused on building a clean, practical desktop organizer with Python.

---

## Ways to Contribute

- Report bugs
- Suggest new features
- Improve documentation
- Refactor code
- Add tests
- Improve UI/UX
- Help with packaging for Windows or Linux

---

## Development Setup

Clone the repository:

```bash
git clone https://github.com/TripZeroLabs/Mason-Organizer.git
cd Mason-Organizer
```

Create a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

Install dependencies:

```bash
pip install -r requirements.txt
```

If you are working on development or testing tasks, install development dependencies when available:

```bash
pip install -r requirements-dev.txt
```

Run the application:

```bash
python main.py
```

---

## Safety Rules

Mason Organizer works with user files, so safety is the top priority.

- Keep file operations safe by default.
- Do not delete user files automatically.
- Prefer preview, confirmation, undo, and logging for file actions.
- Keep AI features local-first unless the user explicitly chooses an external provider.
- Test organizer changes on copied folders before release.

---

## Contribution Guidelines

Before submitting changes:

1. Keep code readable and beginner-friendly.
2. Use clear names for files, functions, and variables.
3. Avoid committing local settings, secrets, virtual environments, or cache files.
4. Test your changes before opening a pull request.
5. Keep pull requests focused on one improvement at a time.

---

## Pull Request Checklist

- [ ] The application still runs locally
- [ ] File operations were tested safely on copied test folders
- [ ] The change is clearly described
- [ ] Documentation was updated if needed
- [ ] No secrets or local settings were committed
- [ ] The pull request focuses on one clear change

---

## Project Direction

Mason Organizer is built around practical productivity, local-first workflows, safe file organization, and simple automation. Future releases may include improved file automation, plugins, AI assistance, and cross-platform installers.
