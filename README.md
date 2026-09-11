# Automating Python Projects with Pip, PyPi & Scripting

A lightweight Python automation and CLI utility built with object-oriented principles, external package integration, and file I/O operations.

## Features
- **File Automation**: Generates timestamped log summary text files dynamically.
- **API Integration**: Connects to a public API via the `requests` library to fetch and process data.
- **Dependency Management**: Tracks and locks external packages using `requirements.txt`.

## Project Structure
- `generate_log.py`: Script that handles text file generation and local logging.
- `fetch_data.py`: Script that queries a public API using `requests`.
- `requirements.txt`: Tracks project dependencies.

## Setup and Execution
1. Install dependencies:
   ```bash
   pip install -r requirements.txt