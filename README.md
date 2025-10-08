# Palindrome Detector

A simple web application built with Sinatra that detects whether a given phrase is a palindrome. This project was created as part of the [Learn Enough Ruby to Be Dangerous](https://www.learnenough.com/ruby) tutorial by Michael Hartl.

## About

A palindrome is a word, phrase, or sequence that reads the same backward as forward (ignoring spaces, punctuation, and capitalization). Examples include:
- "A man, a plan, a canal: Panama"
- "Madam, I'm Adam"
- "racecar"

This application allows users to enter any text and check if it forms a palindrome.

## Features

- **Web-based interface**: Simple HTML form for entering text
- **Real-time palindrome detection**: Instant feedback on whether input is a palindrome
- **Case-insensitive matching**: Ignores capitalization differences
- **Punctuation and space handling**: Strips out non-alphanumeric characters
- **Integer support**: Can also check if numbers are palindromes (e.g., 12321)

## Technologies Used

- **Ruby**: Programming language
- **Sinatra**: Lightweight web framework
- **Palindrome Gem**: Custom Ruby gem for palindrome detection logic
- **HTML/CSS**: Front-end interface
- **Embedded Ruby (ERB)**: Templating
- **Heroku**: Deployment platform (optional)

## Installation

### Prerequisites

- Ruby (version 2.5 or higher recommended)
- Bundler gem

### Setup

1. Clone this repository:
```bash
git clone https://github.com/yourusername/palindrome-app.git
cd palindrome-app
```

2. Install dependencies:
```bash
bundle install
```

3. Run the application locally:
```bash
ruby app.rb
```

4. Open your browser and navigate to:
```
http://localhost:4567
```

## Usage

1. Navigate to the Palindrome Detector page Is it a palidrome?
2. Enter a word or phrase in the text field
3. Click "Check" or submit the form
4. The application will display whether your input is a palindrome
```

## Learning Outcomes

This project demonstrates:
- Building web applications with Sinatra
- Creating and publishing Ruby gems
- Using Embedded Ruby (ERB) for templating
- Implementing HTML forms and POST requests
- Deploying Ruby applications to production
- Test-driven development practices

## Credits

This project was created as part of the [Learn Enough Ruby to Be Dangerous](https://www.learnenough.com/ruby) tutorial by Michael Hartl.

## Contact

For questions or feedback, please open an issue on GitHub.
