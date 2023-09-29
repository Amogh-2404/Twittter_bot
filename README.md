# Internet Speed Twitter Bot

The Internet Speed Twitter Bot is a Python script that automates the process of checking your internet speed and tweeting your internet service provider when it doesn't meet the promised speed. It uses Selenium to perform the speed test and interact with Twitter.

## Table of Contents
- [Introduction](#introduction)
- [Project Files](#project-files)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [License](#license)

## Introduction

Have you ever wondered if your internet service provider is delivering the promised speed? With the Internet Speed Twitter Bot, you can automate the process of testing your internet speed and notifying your provider on Twitter when it falls short. This bot uses Selenium to perform the speed test and tweet the results to your provider.

## Project Files

The main components of this project are:

- **main.py**: This Python script contains the bot's logic. It checks your internet speed, composes a tweet with the results, and posts it to Twitter. You can configure your email, password, promised download/upload speeds, and the path to your Chrome WebDriver in this file.

## Getting Started

To get started with the Internet Speed Twitter Bot, follow these steps:

1. Clone this repository to your local machine.
2. Install the required Python packages, including Selenium:
   `pip install selenium`
3. Configure the bot by editing the variables in the main.py file:
    - **'PROMISED DOWN'**: Promised download speed from your internet service provider.
    - **'PROMISED_UP'**: Promised upload speed from your internet service provider.
    - **'CHROME_DRIVER_PATH'**: Path to your Chrome WebDriver executable.
    - **'TWITTER_EMAIL'**: Your Twitter email or username.
    - **'TWITTER_PASSWORD'**: Your Twitter password.
  
## Usage

To run the Internet Speed Twitter Bot:  

1. Open a terminal and navigate to the project directory.
2. Execute the main.py script:
   'python main.py'
3. The bot will perform a speed test and tweet your internet service provider if the speed doesn't meet the promised values.

   Remember to use this bot responsibly and only with your internet service provider's permission.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/Amogh-2404/Twittter_bot/blob/fb8deee4290570bf7dd8a36e15214180a8272d01/LICENSE) file for details.  
Enjoy automated internet speed testing and let your provider know when they fall short!
