
# Poetry Generator

This project is an NLP-based poetry generator that uses a Markov model to create new lines of poetry inspired by the works of Robert Frost.

## Dataset

The dataset consists of poems by Robert Frost, which are used to train the Markov model. The dataset is downloaded from the following URL:
[Robert Frost Poems](https://raw.githubusercontent.com/lazyprogrammer/machine_learning_examples/master/hmm_class/robert_frost.txt)

## Project Overview

The project involves the following steps:

1. **Data Acquisition**: Download the dataset of Robert Frost's poems.
2. **Data Preprocessing**: Clean and preprocess the text data by removing punctuation and normalizing the text.
3. **Markov Model Construction**: Build first and second-order Markov models to understand word transitions.
4. **Poetry Generation**: Use the constructed Markov models to generate new lines of poetry.

## Key Functions and Their Descriptions

- `remove_punctuation(s)`: Removes punctuation from a given string.
- `add2dict(d, k, v)`: Helper function to add entries to the dictionary for the Markov model.
- `sample_word(d)`: Samples a word based on the distribution in the dictionary.
- `generate()`: Generates poetry using the Markov models.

## Example Usage

To generate a poem with the trained Markov model, you can run the following code snippet:

```python
 generate()
```

This will generate and print a 4-line poem.

## Requirements

- Python 3
- numpy
- string

You can install the required packages using the following command:

```bash
pip install numpy
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/nihalmorshed/Poetry-Generator
   ```
2. Navigate to the project directory:
   ```bash
   cd poetry-generator
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Poetry_Generator.ipynb
   ```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
