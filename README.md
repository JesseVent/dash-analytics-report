# Dash Analytics Report

This is a Dash application designed to visualize and report on time-series analytics data from various marketing and traffic sources like Facebook, Twitter, Mailchimp, Google Display Network, and search platforms.

## Setup and Run

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd dash-analytics-report
    ```

2.  **Create and activate a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the application:**
    ```bash
    python app.py
    ```

    The application will typically be available at `http://127.0.0.1:8050/` in your web browser.

## Data

The `data/` directory contains sample CSV and Excel files for various platforms, including `adwords.csv`, `gdn.csv`, `facebook.csv`, `twitter.csv`, `traffic.csv`, `search.csv`, and `mailchimp.csv`.