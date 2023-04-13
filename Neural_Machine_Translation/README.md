Neural Machine Translation

In this project, a neural machine translation (NMT) model was implemented to translate English text to French using various techniques such as RNN, LSTM, Attention, and Transformers. The English-to-French dataset used contained multiple lines of English sentences with their corresponding French translations.

The raw text was preprocessed by replacing special symbols, converting characters to lower case, and tokenizing the text into a source list and a target list. Sentences with a length greater than 8 and words occurring less than 5 times in the corpus were filtered out to reduce the memory and training complexity.

A vocabulary was built to convert word strings to indices and vice versa, with four special tokens added (pad, bos, eos, unk). The dataset pipeline was established using Pytorch DataLoader API to process input sentences and pad them with necessary tokens.

The project started with a baseline seq2seq RNN model, which achieved a prediction accuracy of 0.7143 (71.43%). The model was then improved by incorporating LSTMs and the attention mechanism, leading to a significantly better prediction accuracy of 0.9370 (93.70%).

Lastly, the Transformer model was implemented to achieve the benefits of capturing long-range dependencies while being easily parallelizable. The Transformer model comprised of multi-head self-attention, position-wise feed-forward networks, and positional encoding.

This project is important as it demonstrates the effectiveness of various NMT techniques in translating text from one language to another. By comparing the prediction accuracies of different models, it highlights the improvements that can be achieved by employing advanced techniques such as LSTMs, attention mechanisms, and transformers. These models can be applied to various real-world applications, including translation services, chatbots, and natural language understanding systems, among others.
