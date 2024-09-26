
# My Dev Journey Blog

This repository contains the source code for my personal blog documenting my journey as a full-stack developer. The blog is generated using [Pelican](https://blog.getpelican.com/), a static site generator written in Python, and covers topics like FastAPI, GitHub setup, and more.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)


## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone git@github.com:RezaBG/blog.git
    cd blog
    ```

2. Install the required dependencies (you need Python >= 3.8.1):
    ```bash
    python -m pip install "pelican[markdown]"
    ```

## Usage

### 1. Generate the Site

To generate the static files for your blog, run the following command:

```bash
pelican content
```

This will generate the site files into the `output/` directory.

### 2. Preview the Site Locally

To preview the site, run the following command:

```bash
pelican --listen
```

Open your browser and navigate to:

```bash
http://localhost:8000
```

### 3. Add New Content

To add a new article, create a markdown file in the `content/` directory with the following structure:

```markdown
---
Title: Your Article Title
Date: YYYY-MM-DD HH:MM
Category: Programming
---

# Your Article Title

Content goes here.
```

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are accepted.

1. Fork the project
2. Create a feature branch (`git checkout -b feature-branch-name`)
3. Commit your changes (`git commit -m "Description of changes"`)
4. Push to the branch (`git push origin feature-branch-name`)
5. Open a Pull Request

