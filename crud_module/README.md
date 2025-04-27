# CRUD Module (Project One)

This module connects to a MongoDB animal shelter database to perform Create and Read operations.

- `animal_shelter.py`: Python module containing AnimalShelter class
- `TestAnimalShelter.ipynb`: Jupyter notebook demonstrating module usage

## About
A modular Python CRUD system (animal_shelter.py) built to interface with a MongoDB collection of animal shelter records. Demonstrated via an interactive Jupyter Notebook (TestAnimalShelter.ipynb).

### Key Technologies:
- Python 3.9+
- PyMongo
- MongoDB Atlas or Community Edition
- Jupyter Notebook

### Setup
1. Install dependencies:
`pip install pymongo python-dotenv notebook`
2. Configure your .env file with MongoDB credentials (URI-based connection).
3. Launch Jupyter Notebook and open TestAnimalShelter.ipynb.

### Features
- Create documents (insert animal records)
- Read documents (query animal records with filters)
- Error handling and secure connection management
- Ready for future extension (Update, Delete operations)


