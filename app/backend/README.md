# Backend Documentation

## Overview

This directory contains the backend implementation for the Azure Search OpenAI Demo. The backend is responsible for handling API requests, processing data, and communicating with external services.

## Features

- **API Endpoints**: Provides RESTful APIs for frontend communication.
- **Data Processing**: Handles data transformations and business logic.
- **Integration**: Connects with Azure Search and OpenAI services.

## Prerequisites

- Python 3.8 or higher
- Required dependencies listed in `requirements-dev.txt`

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/azure-search-openai-demo.git
   cd azure-search-openai-demo/app/backend
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r ../../requirements-dev.txt
   ```

## Running the Backend

To start the backend server, run:

```bash
python main.py
```

## Directory Structure

```
backend/
├── main.py          # Entry point for the backend
├── api/             # API endpoint implementations
├── services/        # Business logic and integrations
├── models/          # Data models
├── utils/           # Utility functions
└── tests/           # Unit and integration tests
```

## Testing

Run the following command to execute the tests:

```bash
pytest
```

## Contributing

See the [CONTRIBUTING.md](../../../CONTRIBUTING.md) file for guidelines on how to contribute to this project.

## License

This project is licensed under the terms of the [LICENSE](../../../LICENSE) file.