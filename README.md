# Markov Text Generator
This Java application generates word suggestions using a Markov Chain model. It allows users to train the model with a source text and receive suggestions for the next possible words based on their input.

## Features

- Train the model with a source text.
- Suggest next possible words based on the current input.
- Retrain the model with a new source text.
- Load text data from a file to train the model.

## How to Use
1. Clone the repository to your local system using the command:<br>
git clone https://github.com/Ahad-Channa/markov-text-generator.git

2. Navigate to the project directory:<br>
cd markov-text-generator

3. Compile the Java files:<br>
javac -d bin src/Markov/*.java

4. Run the program:<br>
java -cp bin Markov.MarkovText

The program will prompt you to enter a word. Type a word and press Enter to get suggestions for the next possible words.
Type exit to quit the program and see the list of selected words.

## Example
Enter a word (or 'exit' to quit): hello
Suggestions: world, there, friend

Enter a word (or 'exit' to quit): world
Suggestions: is, is not

Enter a word (or 'exit' to quit): exit
Selected words: hello world


## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes. Make sure to follow the project's coding standards and include tests where applicable.

