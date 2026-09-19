# MASA OmniSearch Engine

Desktop multi-source research hub integrating Wikipedia, DuckDuckGo, and web indexing APIs

## Technical Architecture

The application is architected with modular separation of concerns adhering to modern clean code standards:

- **Component Layering**: Isolated view layouts, state managers, and service controllers.
- **Defensive Engineering**: Robust input sanitization and exception management.
- **Modern Design Standards**: High-contrast dark-mode interface styled for optimal usability and visual polish.

## Preview

![Application Interface](screenshots/app_interface.png)

## Features

- Asynchronous research querying with Wikipedia summary extraction.
- Categorized knowledge cards with direct browser external URL dispatching.
- Search history cache and query suggestion dropdown.
- High-contrast dark-mode reading workspace with font scaling.

## Prerequisites

- Python 3.10 or higher
- Required packages:

```bash
pip install customtkinter pillow requests
```

## Execution

Launch the application via Python:

```bash
python "Search Engine Program using Tkinter in Python/index.py"
```

## Project Structure

```
.
├── Search Engine Program using Tkinter in Python
├── screenshots/
│   └── app_interface.png
├── .gitignore
├── LICENSE             # MIT License
└── README.md           # Developer documentation
```

## License

This project is licensed under the terms of the MIT License. Refer to the `LICENSE` file for details.
