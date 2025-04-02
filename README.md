# FastAPI Workspace

This project is a FastAPI application designed to provide an interface for generating embeddings from input text. It includes a Jupyter notebook for experimentation and testing.

## Project Structure

```
fastapi-workspace
├── app
│   ├── main.py               # Entry point of the FastAPI application
│   ├── routers
│   │   └── __init__.py       # Defines and includes application routes
│   └── utils
│       └── embeddings.py      # Utility functions for generating embeddings
├── notebooks
│   └── test.ipynb            # Jupyter notebook for testing and experimentation
├── requirements.txt           # Lists project dependencies
└── README.md                  # Project documentation
```

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   cd fastapi-workspace
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the FastAPI application:
   ```
   uvicorn app.main:app --reload
   ```

4. Access the API documentation at `http://127.0.0.1:8000/docs`.

## Usage

- Use the `/generate-embeddings` endpoint to generate embeddings from input text.
- Refer to the Jupyter notebook for examples and testing of the embedding generation functionality.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or features.