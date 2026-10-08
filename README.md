# question-generator-service

> Service for generating quiz questions dynamically, using AI- or database-driven generation.

![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

## Overview

Service for generating quiz questions dynamically, using AI- or database-driven generation.

## Tech Stack

Python, FastAPI

## Features

- Dynamic quiz question generation
- REST API for requesting questions
- Easily consumed by the quiz service

## Getting Started

### Prerequisites

Make sure you have the tools required for this stack installed (e.g. Python 3.10+, Node.js 18+, or Android Studio).

### Installation & Usage

```bash
git clone https://github.com/<your-username>/question-generator-service.git
cd question-generator-service
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```
Interactive API docs: http://localhost:8000/docs
> Adjust `main:app` if your entry module is named differently.

## Contributing

Contributions are welcome. Fork the repo, create a feature branch, and open a pull request.

## License

Distributed under the MIT License (change as needed).

## Author

**Louai**: [GitHub](https://github.com/<louals>)
