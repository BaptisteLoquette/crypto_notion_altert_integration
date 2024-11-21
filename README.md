## Crypto Notion Alert Integration

This project aims to integrate a crypto price alert system with Notion tables (or everywhere else). It fetches the price of a given cryptocurrency from the CoinGecko API and updates the price in a Notion database.

### Prerequisites

- Python 3.x
- pip (Python package installer)
- Poetry (Python dependency management tool)

### Installation

1. Install Poetry if you haven't already:
```bash
curl -sSL https://install.python-poetry.org | python3 -
```

2. Clone the repository and install dependencies:
```bash
git clone <repository-url>
cd crypto-notion-alert
poetry install
```

### Configuration

1. Create a `.env` file in the project root with the following variables:
```env
NOTION_API_KEY=your_notion_api_key
NOTION_DATABASE_ID=your_database_id
```

### Usage

Run the application using Poetry:
```bash
poetry run python main.py
```
