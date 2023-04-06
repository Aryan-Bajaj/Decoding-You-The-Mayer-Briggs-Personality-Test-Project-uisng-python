# Decoding You: The Mayer Briggs Personality Test Project uisng python

<img src="https://github.com/Aryan-Bajaj/Decoding-You-The-Mayer-Briggs-Personality-Test-Project-uisng-python/blob/main/download.png" alt="Mayer Briggs Personality Test" width="350" height="350">

This project is a Python implementation of the Myers-Briggs Type Indicator (MBTI) personality test. It uses a console-based interface to present a series of questions to the user, where the user responds by selecting between two options (A or B). The test consists of 20 questions, each of which has two options.

## Index

- [Built With](#built-with)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Features](#features)
- [Algorithm](#algorithm)
- [Data](#data)
- [Disclaimer](#disclaimer)
- [Feedback](#feedback)
- [Installation](#installation)
- [Contribution](#contribution)
- [Author](#author)
- [License](#license)

## Built With

- [Python](https://www.python.org/) - A high-level programming language used for general-purpose programming.
- [sys](https://docs.python.org/3/library/sys.html) - A Python library that provides access to some variables used or maintained by the interpreter and to functions that interact strongly with the interpreter.

## Prerequisites

This project requires Python 3.x and the sys library. The sys library is included with Python by default, so no additional installation is necessary.

## Getting Started

To get started with this project, you will need to have Python installed on your local machine. You can download and install Python from the official website: https://www.python.org/downloads/

Once you have Python installed, you can clone this repository to your local machine using the following command:

```
git clone https://github.com/Aryan-Bajaj/Decoding-You-The-Mayer-Briggs-Personality-Test-Project-using-python.git
```

After cloning the repository, navigate to the project directory and run the following command to start the application:

```
python decoding_you_the_mayer_briggs_personality_test_project.py
```

This will start the application and present you with the option to take the test or exit.

## Usage

To use this application, simply follow the on-screen prompts and select between options A or B for each question. After answering all 20 questions, your personality type will be displayed on the screen.

## Features

- Console-based interface
- 20 questions with two answer options (A or B)
- Calculates personality type based on user's responses
- Displays personality type to the console

## Algorithm

The algorithm implemented in this code follows the standard MBTI test, which is based on the dichotomies of extraversion (E) vs. introversion (I), sensing (S) vs. intuition (N), thinking (T) vs. feeling (F), and judging (J) vs. perceiving (P). Each of these dichotomies is determined by the user's responses to specific sets of questions.

After processing all 20 questions, the code determines the user's personality type based on the number of A and B responses for each dichotomy. It concatenates the appropriate letter (E or I, S or N, T or F, J or P) based on whether the user selected more A or B options for each set of five questions. Finally, it displays the user's personality type to the console.

## Data

This project does not collect or store any user data.

## Disclaimer

This project is for educational purposes only and is not intended to provide professional psychological advice.

## Feedback

If you have any feedback or suggestions for this project, please feel free to open an issue or submit a pull request.

## Installation

To install this project on your local machine, simply clone this repository and run `python decoding_you_the_mayer_briggs_personality_test_project.py` from within the project directory.

## Contribution

If you would like to contribute to this project, please feel free to fork this repository and submit a pull request with your changes.

## Author

**ARYAN BAJAJ**

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Aryan-Bajaj/Decoding-You-The-Mayer-Briggs-Personality-Test-Project-uisng-python/blob/main/LICENSE) file for details.
