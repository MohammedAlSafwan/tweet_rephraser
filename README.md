# Tweet Rephraser

Tweet Rephraser is a Python-based application that fetches tweets from a specified Twitter list, rephrases them using OpenAI's GPT-4 API, and then translates them from English to Arabic without translating URLs and emojis. The translated tweets are then posted to a specified Twitter account. The application runs on an hourly schedule using a loop and the `time` module.

## Requirements

- Python 3.9 or later
- Tweepy library
- OpenAI's GPT-4 API
- A Twitter developer account and API keys

## Installation

To install the required dependencies, use pip:

```bash
pip install tweepy openai
```

## Configuration

Before running the application, you will need to set up a `config.py` file with your Twitter API keys and specify the Twitter list ID and target account username in the `tweet_rephraser.py` script.

## Usage

To run the application, simply execute the `tweet_rephraser.py` script:

```bash
python tweet_rephraser.py
```

The application will fetch 10 tweets from the specified Twitter list, rephrase them using GPT-4, translate them to Arabic without translating URLs and emojis, and post them to the specified Twitter account. The process will then repeat every hour.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgements

This project was inspired by the GPT-4 API and Tweepy library, and was created for educational purposes only.