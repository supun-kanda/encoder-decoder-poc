# encoder-decoder-poc
Creating a LSTM model on Question-Answer Jokes dataset which is about Jokes of the question-answer form from Reddit's r/jokes. The purpose is to get the good understanding on encoder-decoder architecture on natural language processing

The overall process of getting a text-dataset ready for the job can be point down as follows
 - Text Cleaning
 - Put \<BOS\> tag and \<EOS\> tag for decoder input
 - Make Vocabulary (VOCAB_SIZE)
 - Tokenize Bag of words to Bag of IDs
 - Padding (MAX_LEN)
 - Word Embedding (EMBEDDING_DIM)
 - Reshape the Data depends on neural network shape
 - Split Data for training and validation, testing
