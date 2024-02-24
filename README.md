# TTSFactor: A Django-based Text-to-Speech Application
Dynamic Text-to-Speech (TTS) web application built with Django and Python 3.12. Our application is designed to convert text into natural-sounding audio, offering a user-friendly interface for generating speech from written content. TTSFactor leverages advanced TTS technologies to provide high-quality audio outputs

## Features
- Text-to-Speech Conversion: Convert any text into spoken words with a click of a button.
- Multiple Languages Support: Supports several languages, making it versatile for global use.
- Adjustable Voice Parameters: Users can adjust the speed, pitch, and volume of the speech output


## Getting Started
These instructions will guide you through the setup process and get TTSFactor up and running on your local machine for development and testing purposes.

### Prerequisites
Before you begin, ensure you have the following installed on your system:

- Python 3.12
- pip (Python package manager)
- Virtualenv (optional but recommended for creating isolated Python environments)

### Installation
1- Clone the Repository

```bash
  git clone https://github.com/achrafka/ttsfactor.git
  cd ttsfactor
```
2- Set Up a Virtual Environment (Optional) using Virtualenv (or mkvirtualenv)

```bash
python3 -m venv ttsfactor-env
source ttsfactor-env/bin/activate
```

3- Install Dependencies

Install all the required packages using pip:

```bash
pip install -r requirements.txt
```

3- Run the Development Server

You can now run the development server to start the application:

```bash
python manage.py runserver
```
## License

[APACHE 2.0 ](https://choosealicense.com/licenses/apache-2.0/)
