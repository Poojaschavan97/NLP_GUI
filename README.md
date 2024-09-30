
# NLPApp - Natural Language Processing GUI

NLPApp is a GUI-based application built using Python's Tkinter library that allows users to perform various Natural Language Processing (NLP) tasks such as sentiment analysis, named entity recognition, and text summarization. This application interacts with an external API and a database to provide NLP functionalities.

## Features

- **User Authentication**: Register and log in securely.
- **Sentiment Analysis**: Analyze the sentiment of provided text.
- **Named Entity Recognition (NER)**: Identify named entities within the given text.
- **Text Summarization**: Create summaries for long texts.
- **User-friendly Interface**: Easy-to-use GUI built with Tkinter.

## Requirements

- Python 3.6 or later
- Libraries:
  - `tkinter`
  - `messagebox`
  
- Custom modules:
  - `myDB.py` (handles database operations)
  - `myapi.py` (interacts with NLP API)

> **Note**: Ensure `myDB.py` and `myapi.py` files are present in the project directory.

## Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/NLPApp.git
    ```
2. **Navigate to the project directory**
    ```bash
    cd NLPApp
    ```
3. **Install required Python packages**
    ```bash
    pip install tk
    ```

4. **Run the application**
    ```bash
    python nlpapp.py
    ```

## Folder Structure

```
NLPApp/
│
├── nlpapp.py          # Main GUI application file
├── myDB.py            # Database operations (custom module)
├── myapi.py           # API interaction module
├── RESOURCES/         # Folder for resources like icons
│   └── favicon.ico    # Favicon for the application
└── README.md          # ReadMe file
```

## Usage

1. **Starting the Application**
   - Run `nlpapp.py` to launch the GUI.
   
2. **Registration**
   - Enter your name, email, and password to create an account.

3. **Login**
   - Enter your registered email and password to access the application.

4. **Perform NLP Tasks**
   - Use the home page to access features like Sentiment Analysis, Named Entity Recognition, and Text Summarization.

## How It Works

- **Database Operations (`myDB.py`)**:
  - Handles user registration and login authentication.
  
- **API Interaction (`myapi.py`)**:
  - Connects to an external NLP API to perform sentiment analysis, named entity recognition, and text summarization.

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue for suggestions and improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Tkinter](https://docs.python.org/3/library/tkinter.html) for providing the GUI framework.
- Any external API service used for NLP functionalities.
