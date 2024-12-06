# JokeHub: Programming and Dad Jokes with Sentiment Analysis 🤖🤣
This project retrieves programming and dad jokes using Joke APIs, calculates sentiment scores for the jokes, and presents them in a structured, visually appealing format.

**Features:**
- Fetches 10 Programming jokes of type "single."
* Calculates and maps sentiment scores to each joke.
+ Retrieves 5 Dad jokes containing the term "dad."
- Format output with clean separation and JSON pretty printing.

**How It Works**

Programming Jokes:

* Fetches 10 jokes from the Joke API.
* Prints each joke with a numbered format and a blank line between consecutive jokes.
* Calculates sentiment scores for each joke and creates a dictionary mapping joke text to its sentiment value.
* Pretty prints the dictionary in JSON format.

Dad Jokes:

* Fetches 5 jokes containing the term "dad" using the Dad Jokes API.
* Prints each joke, separated by a line containing "******."
