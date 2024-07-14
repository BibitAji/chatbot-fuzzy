# chatbot-fuzzy
# Basic AI Chatbot

## Introduction
This project is a basic AI chatbot prototype designed to assist users with common queries in the customer support domain. It uses the `fuzzywuzzy` library for fuzzy string matching to understand and respond to user queries. The project is built using Flask for the web server and includes a simple web interface for interaction.

## Features
- Handles basic greetings and farewells.
- Answers five frequently asked questions (FAQs) related to customer support.
- Provides a fallback response for questions it cannot answer.

## Technologies Used
- **Flask**: Web framework for Python.
- **fuzzywuzzy**: Library for fuzzy string matching.
- **NLTK**: Natural Language Toolkit for text processing.
- **Bootstrap**: CSS framework for a responsive and modern interface.
- **HTML/CSS/JavaScript**: Front-end technologies.

## Setup Instructions
1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-repo/basic-ai-chatbot.git
    cd basic-ai-chatbot
    ```

2. **Create a virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Run the application**:
    ```sh
    python app.py
    ```

5. **Open your browser and navigate to**:
    ```
    http://127.0.0.1:5000/
    ```

## Challenges Faced
- **String Matching**: Ensuring accurate responses for user queries required tuning the fuzzy matching threshold.
- **Interface Design**: Creating a user-friendly and responsive chat interface with Bootstrap.
- **Data Preprocessing**: Efficient preprocessing of text to improve the accuracy of the chatbot responses.

## Conclusion
This project demonstrates a basic AI chatbot that uses fuzzy string matching to assist users with common queries. It highlights the integration of AI concepts into a web application, providing a foundation for more complex chatbot systems.

## License
This project is licensed under the MIT License.
