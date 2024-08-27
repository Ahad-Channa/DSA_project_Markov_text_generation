# Markov Text Generator
This Java application generates word suggestions using a Markov Chain model. It allows users to train the model with a source text and receive suggestions for the next possible words based on their input.

## Features

- Train the model with a source text.
- Suggest next possible words based on the current input.
- Retrain the model with a new source text.
- Load text data from a file to train the model.

## How to Use
1 Clone the repository to your local system using the command:
git clone https://github.com/yourusername/markov-text-generator.git

2 Navigate to the project directory:
cd markov-text-generator

3 Compile the Java files:
javac -d bin src/Markov/*.java

4 Run the program:
java -cp bin Markov.MarkovText

The program will prompt you to enter a word. Type a word and press Enter to get suggestions for the next possible words.
Type exit to quit the program and see the list of selected words.
