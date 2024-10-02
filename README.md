# NLPApp GUI

**NLPApp GUI** is a Python-based desktop application built using **Tkinter** for the GUI and designed to perform various Natural Language Processing (NLP) tasks. It features a user-friendly interface, login and registration functionalities, and the ability to analyze text for sentiment, named entities, and summarization. The app connects to an NLP API for these functionalities and uses a database for storing user information.

## Features

- **Login and Registration**: Users can register and securely log in using their credentials.
- **Sentiment Analysis**: Analyze the sentiment of input text (e.g., positive, neutral, or negative).
- **Named Entity Recognition (NER)**: Identify and extract entities such as people, locations, and organizations from input text.
- **Summarization**: Generate a summary from a given piece of text.
- **User-friendly Interface**: Intuitive and easy-to-use GUI designed with Tkinter.
  
## Technologies Used

- **Python**: Core programming language used.
- **Tkinter**: For creating the graphical user interface.
- **Database**: To store user credentials (you can define your database in the `myDB` module).
- **API**: NLP tasks are performed using external APIs (integrated via the `myapi` module). using NLPCLOUD

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/NLPApp-GUI.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd NLPApp-GUI
   ```

3. **Install required libraries**:
   Ensure you have Python 3 installed, then install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. **Database Setup**:
   You’ll need to set up your database in the `myDB.py` file. The `Database` class handles user data. Modify it according to your database setup.

5. **API Integration**:
   Set up the external APIs for NLP tasks in `myapi.py`. The `API` class connects the app to these APIs to perform sentiment analysis, named entity recognition, and summarization.

## How to Run

1. **Run the Application**:
   ```bash
   python nlpapp.py
   ```

2. The app will launch a graphical user interface where you can log in or register. Once logged in, you can access the following features:
   - **Sentiment Analysis**
   - **Named Entity Recognition**
   - **Summarization**


## File Structure

```bash
NLPApp-GUI/
│
├── myDB.py              # Handles database-related operations
├── myapi.py             # Connects with external NLP API services
├── nlpapp.py            # Main file to run the app
├── README.md            # Project README file
├── requirements.txt     # List of dependencies
└── RESOURCES/           # Favicon and other resources
    └── favicon.ico      # App icon
```


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
