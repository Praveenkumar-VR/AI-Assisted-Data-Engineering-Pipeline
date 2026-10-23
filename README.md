# AI-Assisted Data Engineering Pipeline

A Python-based data engineering project that processes multiple file formats and explores AI-assisted data profiling using the Google Gemini API.

## Project Overview

This project is designed to organize incoming datasets, inspect their structure, and support data profiling workflows. It provides a foundation for building automated data ingestion and data quality processes.

## Features

- Supports CSV, JSON, TXT, and Excel file formats.
- Organizes files using dedicated data processing folders.
- Performs data profiling to understand dataset structure.
- Explores AI-assisted data analysis using the Google Gemini API.
- Separates processing, archived, error, and output files.
- Uses Python for data processing and automation.

## Tech Stack

- Python
- Pandas
- Google Gemini API
- CSV, JSON, TXT, and Excel
- Git and GitHub

## Project Structure

```text
Python_dataengineering/
├── script/
│   └── data_profiler.py
├── landing/
├── data/
│   ├── processing/
│   ├── archive/
│   ├── error/
│   └── output/
├── main.py
├── setup_project.py
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md
```

## Prerequisites

- Python installed
- Git installed
- Google Gemini API key if AI-powered features are enabled

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/PraveenKumarvr555/AI-Assisted-Data-Engineering-Pipeline.git
   ```

2. Open the project directory:

   ```bash
   cd AI-Assisted-Data-Engineering-Pipeline
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Configure environment variables in a local `.env` file if required. Use `.env.example` as a template.

5. Place supported sample datasets in the `landing` directory.

## Run the Project

Run the data profiler from the project directory:

```bash
python script/data_profiler.py .
```

Follow the output and instructions displayed by the script.

## Security

- Do not commit `.env` files or API keys.
- Avoid uploading private or sensitive datasets.
- Use sample datasets when sharing the project publicly.

## Author

**Praveenkumar V R**

- GitHub: [PraveenKumarvr555](https://github.com/PraveenKumarvr555)
- LinkedIn: [praveenkumar-v-r](https://linkedin.com/in/praveenkumar-v-r/)
