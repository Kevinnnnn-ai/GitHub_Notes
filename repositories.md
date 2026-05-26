# What is a GitHub repository?

A GitHub repository, also known as a "*repo*," is a digital storage space on GitHub that holds all the files for a specific project, including its entire revision history.

<br>



# How are GitHub repositories structured?

GitHub repos can be structured in many ways and vary according to the project. However, the common directory is structured as follows:

```bash
project/
├── .git/            # Version control metadata
├── .gitignore       # Files/folders to ignore in Git
├── README.md        # Project documentation and setup guide
├── LICENSE          # Legal usage and copyright
├── requirements.txt # Project dependencies (Python)
├── src/             # Source code (the heart of the app)
│   ├── api/         # Network requests and backend integration
│   ├── assets/      # Static files (images, fonts, icons)
│   ├── components/  # Reusable UI elements or micro-modules
│   ├── config/      # Environment and configuration variables
│   ├── styles/      # Global stylesheets or themes
├── public/          # Publicly accessible static assets
├── tests/           # Unit and integration test suites
│   ├── unit/        # Individual function tests
│   └── integration/ # Component interaction tests
├── docs/            # Additional project documentation
└── build/           # Compiled/minified output files (ignored in Git)
```