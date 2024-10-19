# **LSTM-based Text Generator**

## **Description**  
This project is a text generation model built using Long Short-Term Memory (LSTM) networks. The model generates word in a sequence based on input prompt, trained on user-provided text. It can generate creative sequences by learning the patterns and structures within the given data.

Users can input their own text corpus, which will be preprocessed and used to train the model. The model then takes a seed text and generates the specified number of words following the style of the training text.

## **Installation Instructions**  
1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>

## **Features**
Character-Based Text Generation: Generates text by predicting each character one by one.
Word-Based Text Generation: Generates text by predicting the next word in a sequence.
Custom Text Corpus: Users can provide any text for training.
Customizable Generation: Users can specify the number of words to be generated and provide seed text to start the generation.
Model Saving: The model can be saved in a readable format for later use.

## **Limitations by Now (Please make sure to not make epochs changes)**
The model may not generate meaningful text unless trained on a sufficiently large and relevant dataset.
Longer training times for larger datasets can occur, depending on hardware. (Since time complexity for tokenization and Training is O(N)^2)
