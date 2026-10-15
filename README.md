# Country Capital API

## Overview

The Country Capital API is a Python-based API built with Flask that returns the name of a country when a capital city is provided. It is served using Uvicorn and can also be consumed by other projects in the organization through a hosted microservice endpoint.

## Prerequisites

Before running the application locally, ensure that you have:

- Python installed.
- pip, the Python package installer.
- Flask and Uvicorn installed.

## Local Setup

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
    
   ```bash
   cd country-capital-api
   ```

3. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   ```

   On Windows:

   ```bash
   venv\Scripts\activate
   ```

   On macOS or Linux:

   ```bash
   source venv/bin/activate
   ```

4. Install the required dependencies:

   ```bash
   pip install flask uvicorn
   ```

5. Start the application using the project's configured Uvicorn command.

   **Note:** Use the actual application module and entry point specified in the repository.

## Hosted API

The API is also available as a microservice endpoint:

`https://example.com/country-capital/<query-params>`

Other projects within the organization can consume this endpoint to retrieve the country corresponding to a supplied capital city.

